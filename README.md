# utx-embedded-launchpad-lab4
UTx-6.10 Lab 4

Purpose
The purpose of this second lab is to introduce a simple debugging process. We ask you to debug a simple program involving input from switches and output to LEDs. The essence of debugging is to first understand what the system is supposed to do. Second, you will run or debug the system and take careful measurements of what the system is actually doing. In particular, for each input what is the output? If the actual response does not match expectations, you will then hypothesize what is wrong and use the hypothesis to make corrections to the software. You then repeat the careful measurements on the modified system. If the new measurements are closer to the desired response, you keep the software corrections. If the new measurements lead you further from the desired response you discard the software corrections. Either way, you iterate on the “1) measurements, 2) hypothesis, 3) software change” cycle until the desired response is obtained.

System Requirements
The system will have two inputs and three outputs. The inputs are switches called SW1 and SW2, which are connected port pin PF4 and PF0 respectively. Three outputs (PF3, PF2, PF1) are connected to one multi-color LED. The color of the LED is determined by the 3-bit value written to the outputs. 

https://www.youtube.com/watch?v=cYoTOHT02T8
