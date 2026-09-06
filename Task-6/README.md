# Task 6 – Executive Battery Dashboard

## Objective
Develop an executive-level dashboard for monitoring and diagnosing the Smart BMS.

## Features
- Four-cell voltage monitoring
- Pack voltage monitoring
- Average cell voltage
- Cell imbalance monitoring
- System mode monitoring
- Active fault monitoring
- WiFi signal monitoring
- Battery risk indication
- Fault history
- Operator recommendation
- Historical voltage trends

## Cloud Platform
- Blynk IoT
- ESP32
- Wokwi simulation

## Dashboard Datastreams

| Virtual Pin | Parameter |
|---|---|
| V0 | Cell 1 Voltage |
| V1 | Cell 2 Voltage |
| V2 | Cell 3 Voltage |
| V3 | Cell 4 Voltage |
| V4 | Pack Voltage |
| V5 | Average Voltage |
| V6 | Cell Imbalance |
| V7 | System Mode |
| V8 | Active Fault |
| V9 | WiFi RSSI |
| V10 | Battery Risk |
| V11 | Fault History |
| V12 | Operator Recommendation |

## System Modes
- NORMAL
- DEGRADED
- FAILSAFE
- SHUTDOWN

## Output
The dashboard provides real-time battery measurements, system status, fault information, risk indication, and operator recommendations.
