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

![alt assignment-2]()
[tinker-cad]()
