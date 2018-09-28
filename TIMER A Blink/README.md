# TIMER A Blink
Two LEDs were set to be output. Since, using a timer the CCR0 interrupt was enabled. Next the value of CCR0 was set to 62500. TACTL = With this line TASSEL_2 + ID_3+ MC_1 the SMCLK was acivated to count up and divider of 8. With this information we can calucalte the time in seconds. Timer counts 62500x8us=500000us (0.5s). In the if statement a loop was used to blink the LEDs at differnt rates. The first counter counted to 8 which is 8x0.5= 4sec on/off and the second 4x0.5= 2 sec on/off.

