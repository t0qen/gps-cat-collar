<div align="center">
  
  ### GPS cat tracker
  A tiny private meshtastic node with a XIAO, to help me find my young cat when she go out.
</div>

------
#### How it works

The system can be describes with this simple diagram :

```mermaid
flowchart TB
    A[**Cat tracker:** XIAO nrf52840 + Lora + DFRobot GPS] -.->|Lora| B[**Transmitter:** XIAO esp32c3 + Lora]
    B -->|MQTT| C[**Home assistant**]
    B -->|Wifi| D[**Meshtastic app**]
```
