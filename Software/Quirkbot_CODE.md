# Nodes

## Table of contents

### Connect:

**[LED](#led)**

**[Dual Color LED](#dual-color-led)**

**[Light Sensor](#light-sensor)**

**[Squeeze Sensor](#squeeze-sensor)**

**[Circuit Touch](#circuit-touch)**

**[Analog Sensor](#analog-sensor)**

**[Voltage Output](#voltage-output)**

### Backpack:

**[Servo Motor](#servo-motor)**

**[Continuous Servo](#continuous-servo)**

**[Sonar](#sonar)**

**[IR Proximity](#ir-proximity)**

**[Buzzer](#buzzer)**

### Brains:

**[Wave](#wave)**

**[Randomizer](#randomizer)**

**[List](#list)**

**[Sequence](#sequence)**

**[Converter](#converter)**

**[Gate](#gate)**

### Usb:

**[Key Press](#key-press)**

**[Key Sequence](#key-sequence)**

---


## LED

![LED Node]

### General
Node to control Light Emitting Diodes (LEDs). It both controls LEDs permanently connected to the Quirkbot like the Eyes, or external LEDs you attach to the Arms, Legs, and Head. (Also works with the backpack pins if you are building your own backpack.)

### Connections
Inputs     | Range/Value     | Function
:----------|:----------------|:--------
light      | `0` - `1`       | Set brightness of the LED: `0`=Off,  `1`=Max, `0.5`=Half brightness
place      | *any place*     | Choose where the LED is placed. (See: [List of places](#list-of-places) for more info.)

**No outputs**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Blink Left Eye of the Quirkbot | [LED example](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
Single color LEDs

### Comment
You can use almost any 3mm or 5mm LED with the Quirkbot, just cut the leads to the right length. (See hardware documentation: LEDs (soon!))

### Learn more
The change in brightness of the LED is achieved by a method called PWM (Pulse Width Modulation). There are many Youtube videos and tutorials explaing this concept, like the beginnig of [this video](https://www.youtube.com/watch?v=YmPziPfaByw).

---
## Dual Color LED

![Dual Color LED Node]

### General
Node to control Light Emitting Diodes (LEDs) With 2 leds and 2 colors. Like the 3mm Red-Blue LEDs that comes with the Quirkbot kits. It controls LEDs connected to the Arms, Legs, and Head.

### Connections
Inputs     | Range/Value(s)          | Function
:----------|:------------------------|:--------
light      | `0` - `1`               | Set brightness of the LED: `0`=Off, `1`=Max,  `0.5`=Half brightness
color      | `0` - `1`               | Set color mix of the LED. So for R-B LEDs: `0`=Red, `1`=Blue, `0.5`=Equal mix
place      | `H`,`LA`,`LL`,`RA`,`RL` | Choose where the LED is placed.

**No outputs**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Funky Blinking Horn | [DualColorLED example](http://code.quirkbot.com/program/5655f68dd31f000100c5e758 "Go to Quirkbot CODE")

### Hardware
Dual color LEDs

### Comment
The 2 lead dual color LEDs (or bi-color) is actually 2 LEDs inside one package connected in parallel but reverse from each other. So the long lead is the positive anode of red *and* the negative cathode from blue. The short lead is anode from blue *and* cathode from red.

### Learn more
LEDs are everywhere! In a relativly short time the have become one of the most important techloigies in todays world. Learn more about the history of LEDs are and what makes them special from other lightsources: [Light-emitting diode on Wikipedia](https://en.wikipedia.org/wiki/Light-emitting_diode).

---
## Light Sensor

![Light Sensor Node]


### General
Node that gets the analog data from a Light Sensor connected to Arms, Legs, and Head of the Quirkbot. I gives the lightsesor power from the front pad and reads the back pad to deterimine the amount of hitting light the sensor. It also works with other sensors based on resistance.


### Connections
Inputs     | Range/Value             | Function
:----------|:------------------------|:--------
place      | `H`,`LA`,`LL`,`RA`,`RL` | Choose where the Lightsensor is placed.
min        | `0` - `1`               | Minimum value of the output range
max        | `0` - `1`               | Maximum value of the output range

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
Light sesors

### Comment
The sensor usually has a very wide sesetivity to different light conditions, from pitch black to direct sunlight. This means that in any given lightcondition you will not get the full output range of the node. You can solve this by amplifying the signal with the **Converter** node or using the **Squeeze Sensor** that is self calibrating.

### Learn more
Some link or activity

---
## Squeeze Sensor

![Squeeze Sensor Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/ "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Circuit Touch

![Circuit Touch Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Analog Sensor

![Analog Sensor Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Voltage Output

![Voltage Output Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Servo Motor

![Servo Motor Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Continuous Servo

![Continuous Servo Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Sonar

![Sonar Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## IR Proximity

![IR Proximity Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Buzzer

![Buzzer Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Wave

![Wave Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Randomizer

![Randomizer Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## List

![List Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Sequence

![Sequence Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Converter

![Converter Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Gate

![Gate Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Key Press

![Key Press Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---
## Key Sequence

![Key Sequence Node]

### General
Usage

### Connections
Inputs     | Range/Value       | Function
:----------|:------------------|:--------
in1        | -                 |  XXX
in2        | -                 | ddd

**Output**

### Example CODE
Program | Link to Quirkbot CODE
:---    |:---
Description | [Name](http://code.quirkbot.com/program/5655f35bd66de10100d133a9 "Go to Quirkbot CODE")

### Hardware
If any specific to the node

### Comment
Comment

### Learn more
Some link or activity

---

## List of places

### Names of places in Quirkbot CODE: 

Name            | Quirkbot CODE
:---------------|:-------------
*Pads:* |
Horn            | `H`
Horn Front      | `HF`
Horn Back       | `HB`
Left Arm        | `LA`
Left Arm Front  | `LAF`
Left Arm Back   | `LAB`
Left Leg        | `LL`
Left Leg Front  | `LLF`
Left Leg Back   | `LLB`
Right Arm       | `RA`
Right Arm Front | `RAF`
Right Arm Back  | `RAB`
Right Leg       | `RL`
Right Leg Front | `RLF`
Right Leg Back  | `RLB`
*LEDs:* | 
Left Eye        | `LE`
Right Eye       | `RE`
Left Mouth      | `LM`
Right Mouth     | `RM`
*Servo motors:* |
Servo Motor 1   | `SERVO_BP1`
Servo Motor 2   | `SERVO_BP2`
*Backpack:* |
Backpack 1      | `BP1`
Backpack 2      | `BP2`
Backpack 3      | `BP3` (same as:`SERVO_BP2`)
Backpack 4      | `BP4`
Backpack 5      | `BP5`
Backpack 6      | `BP6` (same as:`SERVO_BP1`)

***note:*** When Quirkbot CODE is using the places `H`, `LA`, `LL`, `RL` and `RA` that means the node is using both the front *and* the back pad, so for instance `H` is using both `HF` and `HB`.

---


### Explanations

Range = Explanation of how the min-max works for the outputrange (illustartion)


### Glossary



Backpack = 

Lead = The metal pins sticking out of a component

LED = Light Emitting Diode. A common electronic component that works as a power efficient light source. As the name indicates the LED is a type of Diode. In Diodes the current can only run in one direction.

Node = The blocks that make up the Quirkbot CODE

PCB = Printed Circuit Board, the plate made of mostly of fiberglass and copper that electronic components are mounted on. The body of the Quirkbot is made from a PCB

Servo Motor =

Continoius Servo Motor =

Pad = The metal surface on either the back or front of Arms, Legs, and Head. Each has independent back and a front pads.



[LED Node]: ./screenshots/1_connect/1_LED.png
[Dual Color LED Node]: ./screenshots/1_connect/2_DualColorLED.png
[Light Sensor Node]: ./screenshots/1_connect/3_LightSensor.png
[Squeeze Sensor Node]: ./screenshots/1_connect/4_SqueezeSensor.png
[Circuit Touch Node]: ./screenshots/1_connect/5_CircuitTouch.png
[Analog Sensor Node]: ./screenshots/1_connect/6_AnalogSensor.png
[Voltage Output Node]: ./screenshots/1_connect/7_VoltageOutput.png

[Servo Motor Node]: ./screenshots/2_backpack/1_ServoMotor.png
[Continuous Servo Node]: ./screenshots/2_backpack/2_ContinuousServo.png
[Sonar Node]: ./screenshots/2_backpack/3_Sonar.png
[IR Proximity Node]: ./screenshots/2_backpack/4_IRProximity.png
[Buzzer Node]: ./screenshots/2_backpack/5_Buzzer.png

[Wave Node]: ./screenshots/3_brains/1_Wave.png
[Randomizer Node]: ./screenshots/3_brains/2_Randomizer.png
[List Node]: ./screenshots/3_brains/3_List.png
[Sequence Node]: ./screenshots/3_brains/4_Sequence.png
[Converter Node]: ./screenshots/3_brains/5_Converter.png
[Gate Node]: ./screenshots/3_brains/6_Gate.png

[Key Press Node]: ./screenshots/4_usb/1_KeyPress.png
[Key Sequence Node]: ./screenshots/4_usb/2_KeySequence.png




