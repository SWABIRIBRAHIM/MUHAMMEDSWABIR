# 10 days internship
### day-1
>github

1. open github.
2. create github acc.
3. create new file.
4. change repository name
   of ("ilogic.c")

>use symbols on repository file
 
 1.[christin-chris](https://www.github.com/christin-chris)
 2.[jomon123-123](https://www.github.com/jomon123-123)
 3.[kpr22102210](https://www.github.com/kpr22102210)
 
 >uplode img
 
 1.your picture
 ![alt project-1](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/IMG_20230208_202237_285.jpg)
 
 
### day-2
>tinkercad:

1.open tinkercad software

2.open new simulation folder

3.creat an a led  simulation circuit with switch and without switch

>project-1

![alt project-1](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-09%20at%2012-25-34%20Circuit%20design%20Grand%20Blorr-Inari%20Tinkercad.png)
>project-2

![alt project-2](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-09%20at%2012-56-43%20Circuit%20design%20Grand%20Blorr-Inari%20Tinkercad.png)
  [tinker-cad](https://www.tinkercad.com/things/5d9RetLUXcA-grand-blorr-inari/editel)
### day-3
>tinkercad:

1.open tinkercad software

2.open new simulation folder

3.creat an a AND gate circuit for op-amp using AND gate ic 7408

>project-3

![alt project-3](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-11%20at%2010-22-21%20Circuit%20design%20Amazing%20Elzing-Blorr%20Tinkercad.png)
>project-4

**LED BLINKING PROGRAM**
![alt project-4](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-11%20at%2011-20-50%20Circuit%20design%20Fantabulous%20Gaaris-Jaban%20Tinkercad.png)
  [tinker-cad](https://www.tinkercad.com/things/fFQTSRrff8g-fantabulous-gaaris-jaban/editel)
   ## program code :
   
```   // C++ code
//
void setup()
{
  pinMode(8, OUTPUT);
}

void loop()

{

  digitalWrite(8, HIGH);
  
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(8, LOW);
  
  delay(1000); // Wait for 1000 millisecond(s)
  
}
```
>project-5

**DENCING LED PROGRAM**
![alt project-5](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-11%20at%2013-41-13%20Circuit%20design%20Fantabulous%20Gaaris-Jaban%20Tinkercad.png)
  [tinker-cad](https://www.tinkercad.com/things/fFQTSRrff8g-fantabulous-gaaris-jaban/editel) 
   ## program code :
   
```   // C++ code
//
void setup()

{

  pinMode(8, OUTPUT);

  pinMode(13, OUTPUT);
  
}

void loop()

{
  digitalWrite(8, HIGH);
  
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(8, LOW);
  
  digitalWrite(13, HIGH);
  
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(13, LOW);
  
  delay(1000);
  
}
```
>project-6

**LED CHEISER PROGRAM**

![alt project-6](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-11%20at%2015-44-56%20Circuit%20design%20Fabulous%20Krunk-Migelo%20Tinkercad.png)
 [tinker-cad](https://www.tinkercad.com/things/ac5tYu984PZ-fabulous-krunk-migelo/editel)
  ## program code :
  
```
// C++ code
//
void setup()
{

  pinMode(13, OUTPUT);
  
  pinMode(8, OUTPUT);
  
  pinMode(7, OUTPUT);
  
  pinMode(2, OUTPUT);
  
}

void loop()

{

  digitalWrite(13, HIGH);
  
  delay(180); // Wait for 1000 millisecond(s)
  
  digitalWrite(13, LOW);
  
   // Wait for 1000 millisecond(s)
   
  digitalWrite(8, HIGH);
  
  delay(180);// Wait for 1000 millisecond(s)
  
  digitalWrite(8, LOW);
  
  // Wait for 1000 millisecond(s)
  
  digitalWrite(7, HIGH);
  
  delay(180); // Wait for 1000 millisecond(s)
  
  digitalWrite(7, LOW);
  
   // Wait for 1000 millisecond(s)
   
  digitalWrite(2, HIGH);
  
  delay(180); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, LOW);
  
   // Wait for 1000 millisecond(s)
   
}`
```
>project-7

**(0-9)7 SEGMENT COUNTER PROGRAM**

![alt project-7](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-15%20at%2015-42-43%20Circuit%20design%20Epic%20Bigery-Sango%20Tinkercad.png)
[tinker-cad](https://www.tinkercad.com/things/39gr94bs2TJ-epic-bigery-sango/editel)
 ## program code :
 
```// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT); 
  pinMode(6,OUTPUT);
}

void loop()
{
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(10,HIGH);
  delay(500); // Wait for 1000 millisecond(s
  digitalWrite(13,LOW);
  digitalWrite(7,LOW);
  digitalWrite(6,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(11,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(12,HIGH);
  delay(500);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(8,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,HIGH);
  digitalWrite(11,HIGH);
  delay(500);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(8,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(6,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(11,HIGH);
  delay(500);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(13,LOW);
  digitalWrite(11,LOW);
  digitalWrite(6,LOW);
  digitalWrite(12,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(500);
  digitalWrite(12,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(6,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(13,HIGH);
  delay(500);
  digitalWrite(12,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(6,LOW);
  digitalWrite(13,HIGH);
  delay(500);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(6,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(500);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(6,LOW);
  delay(500); 
  digitalWrite(6,LOW);
  digitalWrite(9,HIGH);
  delay(500); 
}
```

 
 
 
 ### DAY-4

> introduction to AI & ML
1. Introduced a programming platform named as (Blockly) ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2010-34-11.png)
2. The platform like Blockly are mostly used by  fresher's in programming
3. It's like a game 
4. The blockly helps to know about the programming easly
5. To create a multifunction program like a calculator ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2012-21-17.png)
**AI & ML** 
> STM 32 NUCLEO DEVELOPMENT BOARD
 
![IMAGE](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/stm32.jpg)
1. the board is programmeble
2. Can program th board by nucleo software
3. it can build a sound detecting device by using microphone sensor 

### DAY-5

> Introducing drones by NAVANEETH 3rd year student of robotics

1. Introducing Drones
2. explained about drones parts
3. also speaked about the technical specifications like (Thrust,altitude,propeler diamention,weight management)
>project-8

** Analog reader potentiometer**

![alt project-8](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-15%20at%2014-30-32%20Circuit%20design%20Ingenious%20Curcan-Fyyran%20Tinkercad.png)
[tinker-cad](https://www.tinkercad.com/things/kAk4GmEpMZt-ingenious-curcan-fyyran/editel)

 ## program code :
 
 ```
 const int potpin=A0;
void setup() 
{
  Serial.begin(9600);
}

void loop() 
{
  int potValue = analogRead(potpin); 
  Serial.println(potValue);
  delay(100);
}
```
### DAY-6

> Basics of 3D printing conducted by 3rd year student robotics

1. first introduced of the 3d printing
2. creating  models by the tinkercad 3D modeling
3. start with basic shapes
4. also cover the previous design's
5. created a 3D CAR

![IMAGE](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-19%20at%2013-46-31%203D%20design%20Dazzling%20Snicket%20Tinkercad.png)
[tinker-cad](https://www.tinkercad.com/things/3qsw81D0mDj-dazzling-snicket/edit)

7. then introduced the 3D printer 
8. also printed a design (duration 19 min)

### DAY-7

> Introduced the yaskawa arm robot
1. The introduction of yaskawa AR1440 
![image](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/MOTOMAN-AR1440_max.png)

> Then introduced about the EV (electric vehicle)

### DAY-8

> PROJECT-9 

1. Programming the arduino for the 7 segment display with pot 
2. adjusting the speed of the display by varing the pot [thinker the circuit](https://www.tinkercad.com/things/7hNg1XcCvKV-copy-of-fantastic-gaaris-jaiks/editel)  ![PROJECT-9](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-18%2010-51-29.png)

## PROGRAM CODE:

```
// C++ code
//
const int potpin=A0;


void setup()
  
{
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(potValue); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(potValue);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(potValue);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(potValue);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(potValue);
  
  delay(potValue); // Wait for 1000 millisecond(s)
}
```

### DAY-9

>PROJECT-10

**MANUAL TRAFFIC LIGHT**

![alt project-10](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Capture.JPG)
[tinker-cad](https://www.tinkercad.com/things/7KrXrwLNVTQ-super-fyyran/editel)

 ## program code :
 
 ```const int buttonPin0 = 2;     // the number of the pushbutton pin
const int ledPin0 =  13;
const int buttonPin1 = 4;     // the number of the pushbutton pin
const int ledPin1 =  12;
const int buttonPin2 = 7;     // the number of the pushbutton pin
const int ledPin2 =  8; // the number of the LED pin

// variables will change:
int buttonState0 = 0;         // variable for reading the pushbutton status
int buttonState1 = 0; 
int buttonState2 = 0; 

void setup()
{
  // initialize the LED pin as an output:
  pinMode(ledPin0, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin0, INPUT);
  // initialize the LED pin as an output:
  pinMode(ledPin1, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin1, INPUT);
  // initialize the LED pin as an output:
  pinMode(ledPin2, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin2, INPUT);
}

void loop()
{
  // read the state of the pushbutton value:
  buttonState0 = digitalRead(buttonPin0);
   buttonState1 = digitalRead(buttonPin1);
   buttonState2 = digitalRead(buttonPin2);

  // check if the pushbutton is pressed. If it is, the buttonState is HIGH:
  if (buttonState0 == HIGH)
  {
    // turn LED on:
    digitalWrite(ledPin0, HIGH);
  }
  else if (buttonState1 == HIGH)
  { 
   digitalWrite(ledPin1, HIGH); 
  }
  else if (buttonState2 == HIGH)
  { 
   digitalWrite(ledPin2, HIGH); 
  } 
  else
  {
    // turn LED off:
    digitalWrite(ledPin0, LOW);
     digitalWrite(ledPin1, LOW);
     digitalWrite(ledPin2, LOW);
  }
}
```

>PROJECT-11

**LCD interfacing with arduino**

![alt project-11](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-19%20at%2015-07-08%20Circuit%20design%20Cool%20Snaget-Densor%20Tinkercad.png)
[tinker-cad](https://www.tinkercad.com/things/hyjbVJBnyE4-cool-snaget-densor/editel)

 ## program code :
 
 ```
 #include <LiquidCrystal.h>

// initialize the library by associating any needed LCD interface pin
// with the arduino pin number it is connected to
const int rs = 12, en = 11, d4 = 5, d5 = 4, d6 = 3, d7 = 2;
LiquidCrystal lcd(rs, en, d4, d5, d6, d7);

void setup() {
  // set up the LCD's number of columns and rows:
  lcd.begin(16, 2);
  // Print a message to the LCD.
  lcd.print("instagram ");
}

void loop() {
  // set the cursor to column 0, line 1
  // (note: line 1 is the second row, since counting begins with 0):
  lcd.setCursor(0, 1);
  // print the number of seconds since reset:
  lcd.print("@swabir_ibrahim");
}
```
### DAY-10

>ASSIGNMENT-1:

***VOLT METER USING ARDUINO***

![alt assignment-1](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-20%20at%2012-42-04%20Circuit%20design%20volt%20meter%20using%20arduno%20Tinkercad.png)
[tinker-cad](https://www.tinkercad.com/things/hCURlXQkQ1L-volt-meter-using-arduno/editel)

 ## program code :
 
 ```
 // C++ code
//
#include "Adafruit_LEDBackpack.h"
#include <LiquidCrystal.h> 
Adafruit_7segment led_display1 = Adafruit_7segment();
const int rs = 8, en = 9, d4 = 4, d5 = 5, d6 = 6, d7 = 7;
LiquidCrystal lcd(rs, en, d4, d5, d6, d7);

 float input_volt = 0.0;

 float temp=0.0;

 float r1=15000.0;    

 float r2=3000.0; 

void setup()
{
   led_display1.begin(112);
   pinMode(A1, INPUT);
   Serial.begin(9600);     
   lcd.begin(16, 2);      

   lcd.print("DC DIGI VOLTMETER");
}

void loop()
{
  // Convert from 0-1023 range to 0-30V range
  // (.0293255  = 30.0 / 1023)
  led_display1.println((analogRead(A1) *0.0293255));
  led_display1.writeDisplay();
  delay(100); // Wait for 100 millisecond(s)
 int analogvalue = analogRead(A1);
  temp = (analogvalue * 5.0) / 1024.0;       // FORMULA USED TO CONVERT THE VOLTAGE
  input_volt = temp / (r2/(r1+r2));
 if (input_volt < 0.1) 
   {
     input_volt=0.0;
   } 
    Serial.print("v= ");                 // prints the voltage value in the serial monitor

    Serial.println(input_volt);

    lcd.setCursor(0, 1);

    lcd.print("Voltage= ");               // prints the voltage value in the LCD display  

    lcd.print(input_volt);

    delay(300);
}
```

>ASSIGNMENT-2:

1.creat a key chain

![alt assignment-2](https://github.com/SWABIRIBRAHIM/MUHAMMEDSWABIR/blob/main/Screenshot%202023-05-20%20at%2013-26-04%203D%20design%20Sizzling%20Duup%20Tinkercad.png)
[tinker-cad](https://www.tinkercad.com/things/0FLMgQeMdC5-sizzling-duup/edit)
