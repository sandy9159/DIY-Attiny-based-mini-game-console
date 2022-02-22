# DIY-Attiny-based-mini-game-console

![image](https://user-images.githubusercontent.com/19898602/155065638-6da6d0b8-7cda-4732-97bd-cd1601b1fa44.png)


Hello friends in this post we’ll se how easily we can build a Attiny based mini game console.

In this mini game console you can play some retro games, which is obviously not very high tech but yes you get a good experience of making your own game console.

So in post I’ll tell you in detail how to can build you game console what components you need and how to program Attiny 85 microcontroller.

# Components required for Attiny based mini game console


Here is the list of component you need to build your Attiny 85 based game console.

> Attiny 85 microcontroller

> 10K Ohm x 2

> 6.8K Ohm resistor x 1

> 1K Ohm resistor x 1

> LED 5MM x 1

> 6mm tactile PB X 3

> 0.96 Oled display( gnd,vcc,scl,sda) x 1

> slide switch x 1

> CR2032 battery x 1

> CR2032 battery holder x 1

> 3V Buzzer x 1

#  For uploading code to Attiny 85

> Any arduino board ( I am using Arduino UNO)

> Data cable

> Some jumper wires


![image](https://user-images.githubusercontent.com/19898602/155065785-21501fc5-886b-42d0-ae82-83a20e6c660d.png)


# PCB version of mini game console

![image](https://user-images.githubusercontent.com/19898602/155065818-714f8e0a-430b-4594-a0f2-441e6635d1e3.png)

Download gerber file :- https://drive.google.com/file/d/1kmdUMyGZZynyx7tNjBdYXktDiOe2jRE6/view 


Game console look too god in PCB so if you think to order PCB you can consider [JLCPCB](https://jlcpcb.com/IAT ) because
If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly.
If you get yourself registered today at [JLCPCB](https://jlcpcb.com/IAT ) you get coupons worth of 27$ from [JLCPCB](https://jlcpcb.com/IAT ).



# Brief intro about Attiny 85

Attiny 85 is a tiny 8 bit Microcontroller which is high performance and low power.

Attiny 85 is 8 PIN microcontroller, most of its I/O pins are multifunctional. if you are familiar with arduino borads like NANO, UNO or MEGA, you can easily relate Attiny 85 with them.

You can program attiny 85 same as you program Arduino board using Arduino IDE.

Due to its compact size Attiny 85 is best for compact projects where you not need many IO’s and need to keep size of project as small as possible.


![image](https://user-images.githubusercontent.com/19898602/155066173-bb65ec5f-ee1f-446c-b33a-74cd4193f49f.png)



# Programming Attiny 85

So its time to program Attiny 85 means we need to load the code of game which we want to play on the game console.

For this we need code for game either you have to write your own game code or you can download it from anywhere from internet.

Writing code for game on your own is not piece of cake you need a pro level of coding skills, so we are going to use ready made game code for attiny 85 microcontroller.

Thanks to Andyhighnumber he already wrote many game codes and available for free to use, you can download Attiny Arduino game code from here.

As of now we have downloaded the code for games which we need to upload in attiny microcontroller, but this is not this easy because we cannot connect attiny 85 directly to PC/Laptop we need to us Arduino borad as ISP to load code to Attiny 85.

# Preparing Arduino as ISP to program Attiny

We need to get ready arduino as ISP so we have to upload ArduinoISP code to the arduino board

Simply connect your arduino board (in may case it is Arduino UNO) with laptop via data cable.

Go to the File > Examples > ArduinoISP > ArduinoISP

and upload this code to the arduino board I am using arduino UNO to load code to Attiny85 so you must have to select proper board before uploading the ISP code


![image](https://user-images.githubusercontent.com/19898602/155066210-565bd397-083f-48e3-9a06-c0c4b9ef9d77.png)



# Downloading Attiny board in Arduino IDE

By default Arduino don’t have any board option for attiny 85 microcontroller so we need to first add the board for Attiny 85 board for this kindly follow below steps.

first add below line of code to the preference option in Arduino IDE

Go to File > Preferences and add the below line of code in board URL place

https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json

![image](https://user-images.githubusercontent.com/19898602/155066240-f6ffadc4-3f47-4ce7-90a2-27f73bc014b0.png)

After completing above step now go to

Tools > Board > Board manager

and search for Attiny

and install the board by clicking on install option



![image](https://user-images.githubusercontent.com/19898602/155066293-ba61b5f4-6023-4013-9eaf-66d75b9489ea.png)

![image](https://user-images.githubusercontent.com/19898602/155066312-d8deaa17-1e4c-48b5-91a8-d70b4f3bddeb.png)


As of now attiny board is succesfully installed in our Arduino IDE, So now we need to wire Attiny with Arduino boras as per below diagram to upload game code.

![image](https://user-images.githubusercontent.com/19898602/155066336-e76ee76d-bc62-4edb-a9f5-5134b7226bef.png)

![image](https://user-images.githubusercontent.com/19898602/155066350-d17d956d-ea6f-44b2-abdf-e11153ca69fc.png)


After doing wiring as per above Image connect arduino board with laptop and open the game code which we have downloaded earlier and select the board option as shown in images below and upload the code.


![image](https://user-images.githubusercontent.com/19898602/155066378-c971fd8b-59ae-4d31-821a-6c6b42bb5232.png)

![image](https://user-images.githubusercontent.com/19898602/155066395-3520d85c-c293-4585-bdfe-b6bd5904279f.png)


UNCATEGORIZED

How to make Attiny based mini game console
Posted by sandeep on November 16, 2020


 
Hello friends in this post we’ll se how easily we can build a Attiny based mini game console.

In this mini game console you can play some retro games, which is obviously not very high tech but yes you get a good experience of making your own game console.

So in post I’ll tell you in detail how to can build you game console what components you need and how to program Attiny 85 microcontroller.

Components required for Attiny based mini game console
Here is the list of component you need to build your Attiny 85 based game console.

Attiny 85 microcontroller
10K Ohm x 2
6.8K Ohm resistor x 1
1K Ohm resistor x 1
LED 5MM x 1
6mm tactile PB X 3
0.96 Oled display( gnd,vcc,scl,sda) x 1
slide switch x 1
CR2032 battery x 1
CR2032 battery holder x 1
3V Buzzer x 1
For uploading code to Attiny 85
Any arduino board ( I am using Arduino UNO)
Data cable
Some jumper wires
Attiny based mini game console
Attiny based mini game console
components
PCB version of mini game console
I have made this project on zero PCB but prototype PCB really make your project professional and cool, For that I like to introduce PCBWAY.COM

You can download the gerber file and order it from PCBWAY.COM

DOWNLOAD GERBER FILE

PCBWAY.COM have very affordable rates for PCB like 5$ for 10 boards of 1 -2 layer PCB, they also have very fast production time of only 24 hours.
PCBWAY is expert in manufacturing 1 to 14 Layer PCB also they have option of 9 different colors of PCB to choose from.

You can get quote for PCB very easily just Upload your gerber file to there website and get instant quote for you PCB https://www.pcbway.com/orderonline.aspx

Not only PCB they also have SMD assembly service for there customers means you can now get pre-solder SMD components on you PCB https://www.pcbway.com/pcb-assembly.html



 
Brief intro about Attiny 85
Attiny 85 is a tiny 8 bit Microcontroller which is high performance and low power.

Attiny 85 is 8 PIN microcontroller, most of its I/O pins are multifunctional. if you are familiar with arduino borads like NANO, UNO or MEGA, you can easily relate Attiny 85 with them.

You can program attiny 85 same as you program Arduino board using Arduino IDE.

Due to its compact size Attiny 85 is best for compact projects where you not need many IO’s and need to keep size of project as small as possible.

Attiny based mini game console
Attiny 85 pin detail
Programming Attiny 85
So its time to program Attiny 85 means we need to load the code of game which we want to play on the game console.

For this we need code for game either you have to write your own game code or you can download it from anywhere from internet.

Writing code for game on your own is not piece of cake you need a pro level of coding skills, so we are going to use ready made game code for attiny 85 microcontroller.

Thanks to Andyhighnumber he already wrote many game codes and available for free to use, you can download Attiny Arduino game code from here.

As of now we have downloaded the code for games which we need to upload in attiny microcontroller, but this is not this easy because we cannot connect attiny 85 directly to PC/Laptop we need to us Arduino borad as ISP to load code to Attiny 85.

Preparing Arduino as ISP to program Attiny
We need to get ready arduino as ISP so we have to upload ArduinoISP code to the arduino board

Simply connect your arduino board (in may case it is Arduino UNO) with laptop via data cable.

Go to the File > Examples > ArduinoISP > ArduinoISP

and upload this code to the arduino board I am using arduino UNO to load code to Attiny85 so you must have to select proper board before uploading the ISP code


![image](https://user-images.githubusercontent.com/19898602/155066530-349f4557-1cad-4c81-b06a-c9f87fca70b9.png)




# Downloading Attiny board in Arduino IDE

By default Arduino don’t have any board option for attiny 85 microcontroller so we need to first add the board for Attiny 85 board for this kindly follow below steps.

first add below line of code to the preference option in Arduino IDE

Go to File > Preferences and add the below line of code in board URL place

https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json


![image](https://user-images.githubusercontent.com/19898602/155066572-42477ddc-ef5e-4d91-84be-d85610641b9d.png)


After completing above step now go to

Tools > Board > Board manager

and search for Attiny

and install the board by clicking on install option

![image](https://user-images.githubusercontent.com/19898602/155066617-0eecfcc0-3235-4c6b-ab5c-9d404fef39af.png)
![image](https://user-images.githubusercontent.com/19898602/155066630-a60ddfea-7fd4-465e-9f1d-c6a440271ce7.png)




As of now attiny board is succesfully installed in our Arduino IDE, So now we need to wire Attiny with Arduino boras as per below diagram to upload game code.


Arduino attiny connection


![image](https://user-images.githubusercontent.com/19898602/155066663-1ac7252d-ceb6-42b5-af69-0f85aed285ea.png)
![image](https://user-images.githubusercontent.com/19898602/155066681-a72ca5f1-2bc8-4b2d-989b-01074e2826ef.png)


After doing wiring as per above Image connect arduino board with laptop and open the game code which we have downloaded earlier and select the board option as shown in images below and upload the code.


![image](https://user-images.githubusercontent.com/19898602/155066692-4e1607d6-42c5-4956-873f-7a510073eab6.png)
![image](https://user-images.githubusercontent.com/19898602/155066699-4438efad-a205-4eef-9998-442582ddeef9.png)



Till now we have succefully uploaded game code to Attiny 85 now its time to make our game console please refer the below image for circuit diagram attach all the components as shown below

UNCATEGORIZED

How to make Attiny based mini game console
Posted by sandeep on November 16, 2020


 
Hello friends in this post we’ll se how easily we can build a Attiny based mini game console.

In this mini game console you can play some retro games, which is obviously not very high tech but yes you get a good experience of making your own game console.

So in post I’ll tell you in detail how to can build you game console what components you need and how to program Attiny 85 microcontroller.

Components required for Attiny based mini game console
Here is the list of component you need to build your Attiny 85 based game console.

Attiny 85 microcontroller
10K Ohm x 2
6.8K Ohm resistor x 1
1K Ohm resistor x 1
LED 5MM x 1
6mm tactile PB X 3
0.96 Oled display( gnd,vcc,scl,sda) x 1
slide switch x 1
CR2032 battery x 1
CR2032 battery holder x 1
3V Buzzer x 1
For uploading code to Attiny 85
Any arduino board ( I am using Arduino UNO)
Data cable
Some jumper wires
Attiny based mini game console
Attiny based mini game console
components
PCB version of mini game console
I have made this project on zero PCB but prototype PCB really make your project professional and cool, For that I like to introduce PCBWAY.COM

You can download the gerber file and order it from PCBWAY.COM

DOWNLOAD GERBER FILE

PCBWAY.COM have very affordable rates for PCB like 5$ for 10 boards of 1 -2 layer PCB, they also have very fast production time of only 24 hours.
PCBWAY is expert in manufacturing 1 to 14 Layer PCB also they have option of 9 different colors of PCB to choose from.

You can get quote for PCB very easily just Upload your gerber file to there website and get instant quote for you PCB https://www.pcbway.com/orderonline.aspx

Not only PCB they also have SMD assembly service for there customers means you can now get pre-solder SMD components on you PCB https://www.pcbway.com/pcb-assembly.html



 
Brief intro about Attiny 85
Attiny 85 is a tiny 8 bit Microcontroller which is high performance and low power.

Attiny 85 is 8 PIN microcontroller, most of its I/O pins are multifunctional. if you are familiar with arduino borads like NANO, UNO or MEGA, you can easily relate Attiny 85 with them.

You can program attiny 85 same as you program Arduino board using Arduino IDE.

Due to its compact size Attiny 85 is best for compact projects where you not need many IO’s and need to keep size of project as small as possible.

Attiny based mini game console
Attiny 85 pin detail
Programming Attiny 85
So its time to program Attiny 85 means we need to load the code of game which we want to play on the game console.

For this we need code for game either you have to write your own game code or you can download it from anywhere from internet.

Writing code for game on your own is not piece of cake you need a pro level of coding skills, so we are going to use ready made game code for attiny 85 microcontroller.

Thanks to Andyhighnumber he already wrote many game codes and available for free to use, you can download Attiny Arduino game code from here.

As of now we have downloaded the code for games which we need to upload in attiny microcontroller, but this is not this easy because we cannot connect attiny 85 directly to PC/Laptop we need to us Arduino borad as ISP to load code to Attiny 85.

Preparing Arduino as ISP to program Attiny
We need to get ready arduino as ISP so we have to upload ArduinoISP code to the arduino board

Simply connect your arduino board (in may case it is Arduino UNO) with laptop via data cable.

Go to the File > Examples > ArduinoISP > ArduinoISP

and upload this code to the arduino board I am using arduino UNO to load code to Attiny85 so you must have to select proper board before uploading the ISP code

Attiny based mini game console
Downloading Attiny board in Arduino IDE
By default Arduino don’t have any board option for attiny 85 microcontroller so we need to first add the board for Attiny 85 board for this kindly follow below steps.

first add below line of code to the preference option in Arduino IDE

Go to File > Preferences and add the below line of code in board URL place

https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json

Attiny based mini game console
attiny board manager
After completing above step now go to

Tools > Board > Board manager

and search for Attiny

and install the board by clicking on install option


Attiny based mini game console
As of now attiny board is succesfully installed in our Arduino IDE, So now we need to wire Attiny with Arduino boras as per below diagram to upload game code.


Arduino attiny connection
Attiny based mini game console
Attiny based mini game console
After doing wiring as per above Image connect arduino board with laptop and open the game code which we have downloaded earlier and select the board option as shown in images below and upload the code.





Till now we have succefully uploaded game code to Attiny 85 now its time to make our game console please refer the below image for circuit diagram attach all the components as shown below

# Circuit diagram for Attiny based mini game console


![image](https://user-images.githubusercontent.com/19898602/155066749-29b280bf-afe5-4b6c-a324-bcafbc0fa760.png)

![image](https://user-images.githubusercontent.com/19898602/155066767-583e802e-ef27-4844-aa74-b41adb622cfe.png)


![MVI_0008_1](https://user-images.githubusercontent.com/19898602/155067346-cc2228fb-106e-4524-bd1e-c91f14db6164.gif)

