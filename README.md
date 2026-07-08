# Air-Quality-Monitoring-System
Monitors air quality using MQ-135 sensor and stores data to SD card
# Air-Quality-Monitoring-System

## Description
This project monitors air quality using MQ-135 gas sensor. 
It displays AQI on LCD and stores data to SD card for analysis.

## Components Required
- Arduino Uno
- MQ-135 Gas Sensor
- 16x2 LCD Display
- SD Card Module
- Jumper Wires

## Circuit Connections
| Component | Arduino Pin |
| --- | --- |
| MQ-135 AO | A0 |
| LCD RS | D12 |
| LCD E | D11 |
| LCD D4-D7 | D5,D4,D3,D2 |
| SD CS | D4 |

## Working
1. MQ-135 reads air quality every 3 seconds
2. Value displayed on LCD with Good/Moderate/Poor status
3. All data saved to airdata.csv on SD card

## Real-World Application
Smart City Health Monitoring, Indoor Air Quality Check
