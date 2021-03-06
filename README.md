# door-status-monitoring-system
> Project Title: Door-Status-Monitoring System

> Description
- Moniters the status of lockers, cupboards, refrigrators using an ESP32 board and a magnetic reed switch.
- The electrical circuit is closed when a magnet is near the switch—door; the circuit is closed.
- When the magnet is far away from the switch—door; the circuit is open.
- Connected the reed switch to an ESP32 GPIO to detect changes in its state.
- Notifies user/ owner about the status of the door through email.
- The email notifications is sent using IFTTT, and the ESP32 board is programmed using Arduino IDE.
- IFTTT is a free service which stands for “If This Then That” which is used to send email notification.
- Created an Applet in IFTTT.
- Applets are composed of triggers and actions. Triggers tell an Applet to start. The ESP32 will send a request (webhooks) that will trigger the Applet. Actions are the end result of an Applet run. In my case, sending an email.
- SMTP server can also be used instead of IFTTT
- User/ owner can also check the status of the door at any time through web server.
- Monitors status of all kinds of doors (sliding or rotating).

> HARDWARE COMPONENTS USED:
- ESP32 
- 1× Magnetic Reed Switch 
- 1× breadboard
- Jumper wires
- Buzzer/ Alarm
- MicroUSB wire

> Applications:
- Safety of lockers
- Saftey of cupboards
- Saftey of drawers
- Safety of refrigrator
- Can check windows and doors of a house in check.
