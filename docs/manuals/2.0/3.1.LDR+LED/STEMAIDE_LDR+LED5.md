# Project 1: SMART STREET LIGHT (5 LEDs) 

| **Description** | You will learn how use the detection of the presence or absence of light to turn on or turn off LEDs. |
|------------------|----------------------------------------------------------------|
| **Use case**     | Controlling visibility of light in streetlights at different times of the day.  |

## Components (Things You will need)

| ![LEDs](../../assets/components/LED.png) | ![Arduino Uno](../../assets/components/arduino.png) | ![Arduino USB Cable](../../assets/components/USB_Cable.png) | ![Breadboard](../../assets/components/breadboard.png) |![Jumper Wires](../../assets/components/jump_wire.png)| ![LDR Sensor](../../assets/components/ldr.png)|
|-------------------------|-------------------------|-------------------------|-------------------------|-------------------------|-------------------------|

## Building the circuit

Things Needed:

-	1 Arduino Uno 
-	1 Arduino USB cable 
-	1 Light dependent resistor   
-	1 Green LED 
-	1 Red LED 
-   1 Blue LED
-   1 White LED
-   1 Yellow LED
-	1 Breadboard 
-	1 Red jumper wire 
-	1 Black jumper wire 
-	1 Green jumper wire 
-	2 Brown jumper wire 
-	1 White jumper wire 
-	2 Violet jumper wire 
-	1 Yellow jumper wire 
-	2 Orange jumper wire 


## Mounting the component on the breadboard

### Things needed:

-	1 Light dependent resistor  
-	1 Green LED 
-	1 Red LED 
-	1 Blue LED 
-	1 White LED
-   1 Yellow LED
-	1 Breadboard 

**Step 1:** Take the light dependent resistor and the breadboard, insert the light dependent resistor into the horizontal connectors on the breadboard.

![LDR sensor fixed on breadboard](../../assets/2.0/3.2.LDR+Buzzer/circuit_1.jpg).

**Step 2:** Insert the red LED into the horizontal connectors on the breadboard beside the LDR and take note of where the positive pin (long pin) is and where the negative pin (short pin) is as shown in the picture below.

![Red LED fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/circuit_2.jpg).

**Step 3:** Insert the LED green into the horizontal connectors on the breadboard on the other side of the LDR and take note of where the positive pin (long pin) is and where the negative pin (short pin) is as shown in the picture below.

![Green LED fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/circuit_3.jpg).

**Step 4:** Insert the blue LED into the horizontal connectors on the breadboard on the other side of the LDR and take note of where the positive pin (long pin) is and where the negative pin (short pin) is as shown in the picture below. 

![Blue LED fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/circuit_4.jpg).

**Step 5:** Insert the white LED into the horizontal connectors on the breadboard on the other side of the LDR and take note of where the positive pin (long pin) is and where the negative pin (short pin) is as shown in the picture below. 

![White LED fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/circuit_5.jpg).

**Step 6:** Insert the Yellow LED into the horizontal connectors on the breadboard on the other side of the LDR and take note of where the positive pin (long pin) is and where the negative pin (short pin) is as shown in the picture below. 

![Yellow LED fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_2.jpg).

## WIRING THE CIRCUIT

### Things Needed:

-	1 Red male-to-male jumper wire 
-	1 Black male-to-male jumper wire 
-	1 White male-to-male jumper wire 
-	1 Yellow male-to-male jumper wire 
-	1 Brown male-to-male jumper wire 
-	3 Green male-to-male Jumper Wire 
-	2 Violet male-to-male Jumper Wire 
-	2 Orange male-to-male Jumper Wire 
-	1 Grey male-to-male Jumper Wire 
-	1 Blue male-to-male Jumper Wire 

**Step 1:** Take the green jumper wire. Connect one end of the wire to the “VCC” port on the LDR module and the other end to the “5V” port on the Arduino UNO board. As shown in the picture below.

![Green wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_3.jpg).

**Step 2:** Take the black jumper wire, connect one end of the wire to the “GND” port on the Arduino UNO board and the other end to the “GND” port on the LDR module. As shown in the picture below

![Black wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_4.jpg).

**Step 3:** Take the violet jumper wire, connect one end of the wire to the “DO” pin of the LDR module and the other end to the digital pin 8 on the Arduino UNO board. As shown in the picture below.

![Violet wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_5.jpg).

**Step 4:** Take the brown jumper wire, connect one end of the wire to the “AO” port on the Arduino UNO board and the other end of the pin to the “AO” pin of the LDR module.

![Brown wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_5.jpg).

**Step 5:** Take the orange jumper wire.  Connect one end of the wire to the negative pin of the red LED and connect the other end to GND pin on the Arduino UNO board. As shown in the picture below.

![Orange wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_6.jpg).

**Step 6:** Take the red jumper wire, connect one end of the wire to the positive pin of the red LED and connect the other end to digital pin 5 on the Arduino UNO board. As shown in the picture below.

![Red wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_7.jpg).

**Step 7:** The Breadboard has sections labelled negative and positive. In these sections current runs through horizontally. Since we are working with 5 LEDs where we will need more than 3 GNDs we would transfer one GND to negative section of the Breadboard.

![Red wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/circuit_12.jpg).

**Step 8:** Connect one end of the green male-to-male jumper wire to the GND of the Arduino Uno board and the other end to the negative section of the Breadboard to power the whole negative section as shown in the picture below.

![Green wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_8.jpg).

**Step 9:** Take the white jumper wire, connect one end of the wire to the negative pin of the green LED and connect the other end to negative section of the Breadboard. As shown in the picture below.

![White wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_9.jpg).

**Step 10:** Take the yellow jumper wire, connect one end of the wire to the positive pin of the green LED and connect the other end to the digital pin 7 on the Arduino UNO board. As shown in the picture below.

![Yellow wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_10.jpg).

**Step 11:** Take the blue jumper wire, connect one end of the wire to the negative pin of the green LED and connect the other end to negative section of the Breadboard. As shown in the picture below.

![Blue wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_11.jpg).

**Step 12:** Take the grey jumper wire, connect one end of the wire to the positive pin of the green LED and connect the other end to the digital pin 6 on the Arduino UNO board. As shown in the picture below.

![Grey wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_12.jpg).

**Step 13:** Take the violet jumper wire, connect one end of the wire to the positive pin of the green LED and connect the other end to the negative section of the Breadboard. As shown in the picture below.

![Violet wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_13.jpg).

**Step 14:** Take the orange jumper wire, connect one end of the wire to the positive pin of the green LED and connect the other end to the digital pin 13 on the Arduino UNO board. As shown in the picture below.

![Orange wire fixed on breadboard](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/circuit_14.jpg).

## PROGRAMMING

**Step 1:** Open your Arduino IDE. See how to set up here: [Getting Started](../../../../README.md#getting-started).

**Step 2:** Type ```const int LDR_PIN = A0.```   as shown below in the image 

_**NB:** Make sure you avoid errors when typing. Do not omit any character or symbol especially the bracket { }  and semicolons ;  and place them as you see in the image . The code that comes after the two ash backslashes “//” are called comments. They are not part of the code that will be run, they only explain the lines of code. You can avoid typing them._

![Code 1](../../assets/2.0/3.2.LDR+Buzzer/code_1.jpg).

**Step 3:** Type ```const int DO_PIN = 8;``` as shown below in the image

![Code 2](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/code_1.png).

**Step 4:** Type ```const int Red = 5;``` as shown below in the image

![Code 3](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/code_2.png).

**Step 5:** Type ```const int Green = 7;``` as shown below in the image

![Code 4](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/code_3.png).

**Step 6:** Type ```const int Blue = 6;``` as shown below in the image

![Code 4](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/code_4.png).

**Step 7:** Type ```const int White = 13; ``` as shown below in the image

![Code 5](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/code_5.png).

**Step 8:** Type ```const int Yellow = 3;  ``` as shown below in the image

![Code 6](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_6.png).

**Step 9:** Type ```int ldrValue;``` as shown below in the image

![Code 7](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_7.png).

**Step 10:** Type ```int digitalValue;``` as shown below in the image

![Code 8](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_8.png).

**Step 11:** Type ```pinMode (DO_PIN, INPUT);``` as shown below in the image

![Code 9](../../assets/2.0/3.1.LDR+LED/LDR_and_LED4/code_9.png).

**Step 12:** Type ```int redValue,greenValue,blueValue;``` as shown below in the image

![Code 10](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_10.png).

**Step 13:** Type 
    ```pinMode (DO_PIN, INPUT);   ``` 
    as shown below in the image

![Code 11](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_11.png).

**Step 14:** Type ```Serial.begin(9600);``` as shown below in the image

![Code 12](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_12.png).

**Step 15:** Type ```pinMode(Red,OUTPUT); pinMode (Green,OUTPUT); pinMode(Blue, OUTPUT);pinMode(White, OUTPUT);pinMode(Yellow, OUTPUT); ``` as shown below in the image

![Code 13](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_13.png).

**Step 16:** Type ```int ldrValue = analogRead (LDR_PIN);``` as shown below in the image

![Code 14](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_14.png).


**Step 17:** Type ```int lightState= digitalRead (DO_PIN);``` as shown below in the image

![Code 15](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_15.png).

**Step 18:** Type ``` Serial.printIn (ldrValue);  ``` as shown below in the image

![Code 16](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_16.png).

**Step 19:** Type 
    ```if (lightState == HIGH) { ```

![Code 17](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_17.png).

**Step 20:** Type 
    ```Serial.println ("Light is not present"); ```

![Code 18](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_18.png).

**Step 21:** Type 
    ``` digitalWrite (Red, HIGH);
digitalWrite (Green, HIGH);
digitalWrite (Blue, HIGH);
digitalWrite (White, HIGH);
digitalWrite (Yellow, HIGH);
     ```

![Code 19](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_19.png).

**Step 22:** Type 
    ```else {
Serial.println ("Light is present");
 digitalWrite (Red, LOW);
digitalWrite (Green, LOW);
digitalWrite (Blue, LOW);
digitalWrite (White, LOW);
digitalWrite (Yellow, LOW);
    }
     ```

![Code 20](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_20.png).

![Code 21](../../assets/2.0/3.1.LDR+LED/LDR_and_LED5/code_21.png).

## Conclusion

If you encounter any problems when trying to upload your code to the board, run through your code again to check for any errors or missing lines of code. If you did not encounter any problems and the program ran as expected Congratulations on a job well done. 