# Hardware selection — 2026-11-25

## Selected reference board

Waveshare ESP32-S3-Touch-LCD-7, SKU 27078 (touch version). 800x480 IPS, 8 MB PSRAM, 192.96 x 110.76 mm, nominal 5 V / 450 mA. Integrated CS8501 battery management, single-cell 3.7 V PH2.0 connector, 580 mA charging current. Manufacturer recommends capacity <= 2000 mAh. Actual PCB revision and flash capacity to verify on receipt.

- https://www.waveshare.com/esp32-s3-touch-lcd-7.htm?sku=27078 ($36.99 before delivery/taxes)
- https://docs.waveshare.com/ESP32-S3-Touch-LCD-7/Instructions-For-Use
- https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-7

## Battery candidate

Tiendatec LP405085-CI-JST, protected 1S LiPo, 3.7 V 2000 mAh, 4.2 V charge, 2 A stated maximum discharge, PH2.0, 85 x 50 x 4 mm cell plus protection board. Listed EUR 14.95. https://www.tiendatec.es/electronica/baterias-pilas-y-accesorios/bateras-li-po/970-bateria-litio-lipo-405085-37v-2000mah-740wh-jst-ph20-8472496015066.html

Before connecting, confirm actual connector polarity against board markings and battery supplier; verify charging at 580 mA is supported. No soldering expected. Do not assume identical connector implies identical polarity.

## Mechanical and power validation

Four M4 40 mm suction cups are inexpensive test candidates, not a validated final mount. Prefer removable locking suction mount if testing supports it. Test with inert equivalent weight, away from heat and steam; secondary retention. Measure components before printing PETG enclosure. USB-A to USB-C data cable required for UART flashing. USB meter optional; battery-side measurement needed for true standby draw. Nominal active autonomy ~2.8 hours at assumed 85% conversion efficiency; sleep autonomy unknown. Target <=0.5 mA battery-side idle for multi-week use, not yet validated.
