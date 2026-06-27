## Spot Welder Pro [🇺🇦|UA](https://github.com/MYMDO/Arduino_Spot_Welder_Pro/blob/main/README_UA.md)
This is the latest Alpha version of the Arduino Spot Welder Pro. The is forked from [KaeptnBalu/Arduino_Spot_Welder_V4](https://github.com/KaeptnBalu/Arduino_Spot_Welder_V4)

An Arduino based Spot Welder Pro for battery welding

___

Improvements in V4:

- Buzzer: With the buzzer alarms will not only be displayed on the screen but also be audible for the user. This makes it much easier to notice an alarm while working with the welder.    
- Temperature Sensor: The temperature sensor will trigger an alarm and disable welding when temperature reaches 65°C to protect the welder from overheating.
- additional 470µF Capacitor: With now two 470µF capacitors it is possible to use weld times up to 100 – 150ms without the risk of the Arduino Nano rebooting. The reboot could happen in V3 at very long weld times because the voltage at the Arduino Nano dropped to low dring the weld.  
- SMD Mosfet Driver: the mosfet driver chip has been changed from the through hole version that was plugged in a socket to a SMD version that is directly soldered to the pcb. The SMD version eliminates eventual contact problems that could happen with the through hole version when it was not plugged in the socket correctly.
- SMD Mosfets: The mosfets have been changed from through hole version to SMD. That will eliminate the problem of failing mosfet legs in V3 on very high currents.
- new aluminum parts: there are still two aluminum parts used on the mosfet board but the parts are just straight and both the same size. This makes producing or modding them for DIY users much easier.    
- Stronger Protection Diodes: The protection diodes on the bottom of the mosfet board have been changed to a much stronger version. They are rated for the same current as the ones in V3 but can take much higher short peak amps and have better heat dissipation because they are phisically bigger.
    


This Spot Welder can be used to weld 18650 batteries. It uses a 12V car battery as welding current supply. Typically one 60Ah 600A battery delivers enough current to get good welds with 0.15mm - 0.2mm nickel strips. For thicker nickel strips maybe you will need bigger battery or two in paralell. (Maximum 800A total)

The Welder generates a double pulse, where the first one is 12% of the time of the second one by default. Pulse time of the main pulse is adjustable by the rotary encoder and displayed on the screen in ms so you can exactly adjust the time. Its adjustable from 1 … 100 mS by default. (adjustable up to 500ms in the system menu)

If you want to download the project click on "clone or download" on this page. Downloading single files sometimes seems to cause some files to be corrupted while downloading.

## Task Lists
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

You can get parts to build your own Spot Welder or prebuilt kits at [fx.in.ua/spot-welder-pro/](https://www.fx.in.ua/spot-welder-pro/)

> ___

<a href="https://coindrop.to/mymdo" target="_blank"><img src="https://coindrop.to/embed-button.png" style="border-radius: 10px; height: 57px !important;width: 229px !important;" alt="Coindrop.to me"></img></a>
