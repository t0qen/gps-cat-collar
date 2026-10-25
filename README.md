<div align="center">
  
  ### GPS cat tracker
  A tiny private meshtastic node with a XIAO, to help me find my young cat when she go out.
</div>

------
#### How it works
```mermaid
flowchart LR
    A[Capteur] --> B[ESP32]
    B --> C[MQTT]
    C --> D[Home Assistant]
```
```mermaid
flowchart TB
    User --> Nginx
    Nginx --> Docker[Conteneurs Docker]
    Docker --> Frigate
    Docker --> HomeAssistant[Home Assistant]
```
