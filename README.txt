This is an atempt to simulate the process of controling a DC motor using stm32f103c8.
It begins with reading the frequnecy on microcontroller's external interrupt pin which is considered as motors RPM then it will be compared with the refrence speed and if there's an error ,a PWM signal is going to be generated to control the DC motor's speed.
