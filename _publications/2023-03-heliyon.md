---
title: "A novel smart photoelectric lock system: Speech transmitted by laser and speech to text"
collection: publications
permalink: /publication/2023-03-heliyon
excerpt: '<p align="center"> <img src="/images/heliyon1.png" width="800" height="600"> </p>'
date: 2023-03-01
venue: 'Heliyon'
paperurl: 'https://doi.org/10.1016/j.heliyon.2023.e14510'
citation: '<B>Guo, C. Y.</B>, Hsieh, T. L., Chang, C. C., & Perng, J. W. (2023). &quot;A novel smart photoelectric lock system: Speech transmitted by laser and speech to text.&quot; <i>Heliyon</i>. 2023 Mar 15;9(3):e14510. <B>(First author)</B><br>'
---
We propose a circuit that modulates a speech signal to a laser, using which the speech signal can be transmitted using the laser. Also, it shows the use of a platform based on embedded ARM (Advanced RISC Machine), running a small deep learning model based on TDNN (Time delay neural network) and LSTM (Long short-term memory), and converting speech to text, and use the text cipher for unlocking. This research implements a smart lock system that can set a pre-record speech cipher and verify the similarity through a laser transmission speech cipher to unlock it. In our experiment result, the English speech of laser transmission can reach a WER (Word error rate) of 14.06% through the deep learning model to recognize the content of the speech cipher. We also design a similarity comparison algorithm based on LCS (Longest common subsequence) to compare the character set of the laser transmission speech compare and the prerecord speech cipher to calculate the similarity rate. Through the similarity comparison algorithm, when the WER is 27.27%, the male speech samples used in this study still have a 95% unlocking success rate, while the female speech samples have a 100% unlocking success rate. Compared with only using automatic speech recognition (ASR) to unlock, the method we propose is to compare the similarity of the content of speech cipher. The method significantly improves the unlocking fault tolerance of using lasers to transmit audio. Therefore, by using the laser to transmit the speech cipher, the usability of the photoelectric smart lock system has been significantly improved. At the same time, the characteristics of the laser are not easy to eavesdrop on the cipher, which can also improve security.

Keywords: Photoelectric smart lock, TDNN, LSTM, LCS, Speech recognition.

[Download paper here](https://doi.org/10.1016/j.heliyon.2023.e14510)

Recommended citation: Guo, C. Y., Hsieh, T. L., Chang, C. C., & Perng, J. W. (2023). A novel smart photoelectric lock system: Speech transmitted by laser and speech to text. Heliyon. 2023 Mar 15;9(3):e14510.
