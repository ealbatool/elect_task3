# Latching Power Switch with Auto-Off

[![Tinkercad Simulation](https://img.shields.io/badge/Simulate-Tinkercad-blue)](https://www.tinkercad.com/things/feSQjaLeTLC-latching-power-switch)

A smart power switch circuit that:
- Latches ON with a single button press
- Automatically turns OFF after 10 seconds
- Uses minimal components for energy efficiency

## Circuit Diagram
shown in PNG file.

## Components
| Component       | Quantity | Notes                          |
|-----------------|----------|--------------------------------|
| Arduino Uno     | 1        | Control logic                 |
| IRF540N MOSFET  | 1        | Power switching               |
| 100µF Capacitor | 1        | Latching mechanism            |
| Pushbutton      | 1        | Momentary switch              |
| LED             | 1        | Example load                  |
| 220Ω Resistor   | 1        | LED current limiting          |
| 10kΩ Resistor   | 1        | Button pull-down              |
| 1kΩ Resistor    | 1        | MOSFET gate protection        |

## How It Works
1. **Latching ON**  
   - Press button → Capacitor charges → MOSFET stays ON
2. **Auto-OFF**  
   - Arduino cuts power after 10 seconds
3. **Manual Override**  
   - Press button again to turn OFF early

## Arduino Code
you can find it in arduino code file. 


# adding sensor to the task 

i tried to add PIR sensor but i stucked in the coding i didn't understand the logic and how both the sensor and the button should work toghther.

Provided a PNG for the circuit including the sensor and a brd file for the circuit all named ( with sensor ).
