# SSD1306 OLED display Project written for STM32L476RG MCU

Credits: Software Interface (Firmware) for SSD1306 OLED display is at most copied from Nima Mohammadi's github account.
Thanks to Nima Mohammadi!
Nima Mohammadi:	https://github.com/NimaMX
Nima's project with SSD1306 OLED: https://github.com/NimaMX/STM32F103-SSD1306

******    USERS GUIDE    ******
You can actualy just run code for this MCU: STM32L476RG, and it will work I guess. It works for me, you just have to connect second I2C peripheral (I2C2) (which are pins: PB13 = I2C2_SCL and PB14 = I2C2_SDA) to the SSD1306 OLED display (to pins: SCL and SDA) and it should work nice! In the main.c file you can edit function DISPLAY_Show_Test_Page to show any text you want on display. Also you always can add another layer of software to apstract some more compicated funcionalities to improve functionality of this project to that what you need exactly. Have a good luck. I will add later photos how this project work. Have a good luck, and every work will pay out somewhen!
