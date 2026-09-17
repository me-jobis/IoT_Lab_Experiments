# Experiment 1 — ESP32 LED Blink

## Aim

To write an Arduino program to blink an LED connected to ESP32 GPIO2 at 1 Hz frequency.

## Components Required

| Component | Quantity |
|---|---:|
| ESP32 Development Board | 1 |
| LED (Red / Green) | 1 |
| Resistor 220Ω | 1 |
| Breadboard | 1 |
| Jumper Wires | 3 |
| USB Cable | 1 |

## Circuit Connections

| ESP32 Pin | Component / Connection |
|---|---|
| GPIO2 | LED Anode (+) via 220Ω resistor |
| GND | LED Cathode (−) |

### Circuit Diagram

```text
ESP32 GPIO2 ──── 220Ω ──── LED(+) ──── LED(−) ──── GND
