About
-----

Use a 38 pin node-mcu ESP32 board with a yhdc sct013 50A/1V to monitor AC power production of an
on-grid solar panel setup. Use this information to control 2 30A relays (FC-65 Songle
SLA-05VDC-SL-C) to only enable power in an electrical socket if the solar panels are producing more
than a configurable threshold. We also connect 2 externals relays and one to show we are connected
to wifi. 

Data sheets
-----------

- [SCT013 datasheet](https://datasheetspdf.com/pdf/1328320/YHDC/SCT-013-050/1) 
- [FC-65 5V 30A](http://www.giga.co.za/ocart/index.php?route=product/product&product_id=105)

Resources
---------

- [NodeMCU-32S-38 pinoput](https://www.studiopieters.nl/esp32-pinout/)
- [Connect CT Clamp sensor](https://www.youtube.com/watch?v=Z3YSHhS39Bc)
- [NodeMCU and ct\_clamp forum](https://community.home-assistant.io/t/esphome-ct-calmp-sct-013-000-and-nodemcu/174608/3)

