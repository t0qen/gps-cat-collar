<div align="center">
  
  ### GPS cat tracker
  A tiny private meshtastic node with a XIAO, to help me find my young cat when she go out.
</div>

------
### ✏️ how it works

The system can be describes with this simple diagram :

```mermaid
flowchart TB
    A[**Cat tracker:** XIAO nrf52840 + Lora + DFRobot GPS] -.->|Lora| B[**Transmitter:** XIAO esp32c3 + Lora]
    B -->|MQTT| C[**Home assistant**]
    B -->|Wifi| D[**Meshtastic app**]
```
### 📷️ screenshots
<img width="3264" height="2448" alt="IMG_20261026_103402" src="https://github.com/user-attachments/assets/9a03e862-6df2-40fb-9f7e-26bab95b1daa" />
<img width="2448" height="3264" alt="IMG_20261026_103349" src="https://github.com/user-attachments/assets/6bd59c2b-3cbb-4726-b2ca-f6441cde3ebd" />

<img width="2448" height="3264" alt="IMG_20261026_103340" src="https://github.com/user-attachments/assets/3aabe3d3-9fc9-48c0-af55-edf04a9fc7cd" />
