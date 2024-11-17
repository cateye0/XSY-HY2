# XSY-HY2
Water Pump Inverter

![image](https://github.com/user-attachments/assets/44aec20c-3bdd-4197-a293-1bf303de3cb3)


If you have this type of inverter and would like to control it with an ESP, you can do so using the attached circuit and configuration. <br/>
There are two important settings: <br/>

P43 Relay output, change it from 0 to 1 <br/>
P11 Start stop control source, change it from 0 to 2 !!! Warning !!! From this point on, the start/stop buttons on the device controller will be inactive. <br/>



With this setup, you can achieve the following functions: <br/>

1. Remotely enable/disable inverter (Pump VFD Control)
2. Remotely monitor when your pump is activated (Pump VFD Active)
3. Physically turn the pump On or Off using the push button (Pump VFD Button)"



HY2 Terminal Blocks:

TA, TB, TC
This is a dry relay output. TA is the common terminal, TB is normally closed (NC), and TC is normally open (NO).

X1 and COM <br/>
When X1 is connected to the COM terminal, the pump receives a start signal. <br/>
When disconnected, the pump receives a stop signal. <br/>


My Inverter settings:
| Prog  | Value |
| ------------- | ------------- |
| P07  | 33  |
| P11  | 2  |
| P25  | 2  |
| P30  | 43500  |
| P39  | 3000  |
| P43  | 1  |
| P54  | 2  |
| P97  | 46800  |
| P98  | 13250  |
| P99  | 3.2  |
| P105  | 3.2  |
| P110  | 0.3  |
| P112  | 5  |
