
# step_driver
- stm32f103 ( blue pill )
![stm32](https://user-images.githubusercontent.com/22659037/110656134-3f5c1480-81f2-11eb-936f-16f0f31df7e9.png)
#axis x ( motor 0 )
-   PA0 PULSE pin
-   PA1 DIR pin
-   PB12 LIMIT0 ( active low )
-   PB13 LIMIT1 ( active low )
#axis y (motor 1)
-   A6 PULSE pin
-   PA5 DIR pin
-   PB14 LIMIT2 ( active low )
-   PB15 LIMIT3 ( active low )
-   PA9 tx pin
-   PA10 rx pin
# COMMAND
- have to 8 byte to send over uart band 9600
- ![Untitled](https://user-images.githubusercontent.com/22659037/110591470-b28e6800-81ab-11eb-91b5-e42c9e1bb719.png)

![Untitled](https://user-images.githubusercontent.com/22659037/110590740-c4bbd680-81aa-11eb-952e-f4dc5b0a9269.png)



(This version can't setting pulse frequency default frequency is 10 kHZ)
