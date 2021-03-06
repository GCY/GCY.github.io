---
title: "GPS-Nixie-clock"
excerpt: "This is GPS Nixie clock, include IN12B, IN14, IN16, and IN2 version. <br/> <img src='/res/GPS-Nixie-clock/nixie clock.jpg' width='600' height='500'>"
collection: portfolio
---

<p align='center'>
<a href="https://github.com/GCY/GPS-Nixie-Clock">Github</a>
</p>

This is GPS Nixie clock, include IN12B, IN14, IN16, and IN2 version.

![alt text](/res/GPS-Nixie-clock/nixie%20clock.jpg)

## Firmware
### Parameter

__SERIAL__ : output info to serial port.
DOT : use nixie tube dot.
__GPS__ : time sync with Neo-6M - u-blox chip, this function only for IN14 IN16 version, and time sync separator is GPGGA[7] = {'$','G','P','G','G','A',','};
<pre><code>
#define __SERIAL__ 1
#define DOT 1
#define __GPS__ 1
</code></pre>

gps_update : gps sync period, unit is ms, 300000ms = 5min. 
<pre><code>
const unsigned long gps_update = 300000;
</code></pre>

Type select, IN_14 == IN_16. 
<pre><code>
enum{
  IN_12B = 100,
  IN_14,
  IN_2
};
</code></pre>

### Command

case '1' : clock mode

case '2' : temperature mode

case '3' : humidity mode

case '4' : flash mode

case '5' : counter mode

case '6' : '1' + '2' + '3'

case 's' | 'S' : set time


## Android time sync tool
Android App modified BlueTerm project. 

## PC Software - wxNixieClock

wxNixieClock is time sync tool for Nixie Clock project.(Only MAC-OS-X)
### Build
g++ -o2 -o wxnixieclock.app wxnixieclock.cpp serialport.cpp connectargsdlg.cpp \`wx-config --cxxflags --libs\` -m64



![alt text](/res/GPS-Nixie-clock//wxNixieClock/pic.png)




[![Audi R8](http://img.youtube.com/vi/tJzohsqhTxs/0.jpg)](https://youtu.be/tJzohsqhTxs)

### Use

1. Pair BT of MAC and Nixie Clock.
2. Open wxNixieClock to select tools -> Connect Device -> cu.BT device driver
3. Click SyncTime button
4. Done!

### Dependency

Install wxWidgets dependency in terminal

1. user$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
2. brew install wxwidgets 
