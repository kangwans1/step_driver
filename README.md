
# step_driver
- can use with DRV8825,A4988 
![Untitled](https://user-images.githubusercontent.com/22659037/110693039-97f2d800-8219-11eb-8dea-9c09a60b1174.png)
![Schematic_STM32F103 step driver_2021-03-11](https://user-images.githubusercontent.com/22659037/110694390-18660880-821b-11eb-86d9-27ff053ea6e1.png)
# AXIS X ( motor 0 )
-   PA0 PULSE pin
-   PA1 DIR pin
-   PB12 LIMIT0 ( active low )
-   PB13 LIMIT1 ( active low )
# AXIS Y (motor 1)
-   A6 PULSE pin
-   PA5 DIR pin
-   PB14 LIMIT2 ( active low )
-   PB15 LIMIT3 ( active low )
# UART PORT
-   PA9 TX pin
-   PA10 RX pin
# COMMAND
- have to 8 byte to send over uart band 9600
- ![Untitled](https://user-images.githubusercontent.com/22659037/110591470-b28e6800-81ab-11eb-91b5-e42c9e1bb719.png)

![Untitled](https://user-images.githubusercontent.com/22659037/110590740-c4bbd680-81aa-11eb-952e-f4dc5b0a9269.png)

# USE ST-Link to Upload
![stlink](https://user-images.githubusercontent.com/22659037/110663800-5f430680-81f9-11eb-8502-b24e722c7dc3.png)

(This version can't setting pulse frequency default frequency is 10 kHZ)
