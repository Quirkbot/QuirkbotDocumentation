###Pin names and functions for the Quirkbot: 


Name            | Quirkbot Library   | Arduino     | Function          | 32U4 Port
:---------------|:-------------------|:------------|:------------------|:----
*Pads:* |
Horn Front [^1] | `HF`               | `13`        | PWM (10BIT)       | PC7
Horn Back [^2]  | `HB`               | `A2`        | ADC5              | PF5
Left Arm Front  | `LAF`              | `10`        | ADC13/PWM (16BIT) | PB6
Left Arm Back   | `LAB`              | `A1`        | ADC6              | PF6
Left Leg Front  | `LLF`              | `9`         | ADC12/PWM (16BIT) | PB5
Left Leg Back   | `LLB`              | `A0`        | ADC7              | PF7
Right Arm Front | `RAF`              | `5`         | PWM (HS)          | PC6
Right Arm Back  | `RAB`              | `A3`        | ADC4              | PF4
Right Leg Front | `RLF`              | `11`        | PWM (8/16BIT)     | PB7
Right Leg Back  | `RLB`              | `A4`        | ADC1              | PF1
*LEDs:* | 
Left Eye        | `LE`               | `8`         | ADC11             | PB4
Right Eye       | `RE`               | `A5`        | ADC0              | PF0
Left Mouth      | `LM`               | -           | -                 | PD5
Right Mouth     | `RM`               | -           | -                 | PB0
*Left Backpack:* |
Backpack 1      | `BP1`              | `A7`        | ADC10/PWM (HS)    | PD7
Backpack 2      | `BP2`              | `A11`       | ADC9              | PD6
Backpack 3      | `BP3`/`SERVO_BP2`  | `0`         | RXD1              | PD2
Backpack 4      | `BP4`              | `2`         | SDA               | PD1
Backpack 5      | `BP5`              | `3`         | SCL               | PD0
Backpack 6      | `BP6`/`SERVO_BP1`  | `1`         | TXD1              | PD3
*Right Backpack:* ||| *ICSP:*
VCC             | -                  | -           | VCC               | -
GND             | -                  | -           | GND               | -
SCK             | -                  | -           | SCK               | PB1
MOSI            | -                  | -           | MOSI              | PB3
MISO            | -                  | -           | MISO              | PB2
RESET           | -                  | -           | RESET             | -
*Other:* |
Pull-up pin     | `PULL_UP_PIN`      | `4`         | ADC8              | PD4


***note:*** When the Quirkbot Library or CODE is using the names `H`, `LA`, `LL`, `RL` and `RA` that means the node is using both the front and the back pad, so for instance `H` is using `HF` and `HB`.

[^1]: All the back pads: `HB`, `LAB`, `LLB`, `RAB` and `RLB` are pulled down to ground with a 10k resistor to facilitate the Analog Input functionality.

[^2]: All the front pads: `HF`, `LAF`, `LLF`, `RAF` and `RLF` are connected to the Pull-up pin via a 10M resistor for the Cicuit Touch functionality.
