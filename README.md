# OpenEVSE Divert toggler

Button for manual toggle divert mode in OpenEVSE via MQTT with ESPHome

As the physical button on an OpenEVSE charger is primarily used for manual charging override, I also wanted to have a physical button to togle divert mode ECO <-> Fast while keeping original hardware and firmware. So I added a push button connected to a ESP32 super-mini loaded with ESPHome communicating via MQTT directly to the OpenEVSE do do the job - a plus using a toggle button with a LED.

![Image](https://github.com/francescros/openevse-divert/openevse-divert.jpeg)
