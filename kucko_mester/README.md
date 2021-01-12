Parts List
==========

- [SX-10](https://www.yli.ro/yala-electromagnetica-aplicabila-cu-motor-si-senzor-magnetic.html) cheap electric lock
- [Sonoff 4CH Pro r2](https://sonoff.tech/product/wifi-diy-smart-switches/4ch-r2-pro-r2)
- [DHT22](https://ardushop.ro/ro/electronica/230-senzor-de-temperatura-si-umiditate-dht22.html) temp and humidity sensor kit
- Normal Open [Button](https://www.a2t.ro/butoane-de-acces/buton-de-iesire-incastrabil-din-inox-pbk-811a.html)


Idea
====

The relays in the Sonoff are configured to send an impulse that open the gate ( full or partial ) or close it. 
The electric lock auto closes. The button is on the outside of the door, connected in series to the normal close 
Sonoff relay 4, when the relay opens, it disables the button, so there's no way to open the door from the outside,
effectively closing it. The lock has a key as a backup for electronics failure. 


Wiring diagram
==============

Button
------
- red: +12v
- yellow: Sonoff relay 4 COM

Sonoff
------
- purple: gate COM 
- green: Gate open (Relay 1)
- blue: Gate open partial (Relay 2)
- yellow: Gate Close (Relay 3)
- Black: N  |
- Red:   L  |_> 220VAC 

Lock
----

- blue: GND 
- red: +12V
- green: connect to GND
- yellow: Open (Sonoff relay 4) NC
