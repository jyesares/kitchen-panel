# MVP requirements

- Offline operation, no account or backend.
- Seven-inch color capacitive touchscreen.
- Recipe catalog, ingredients, sequential steps and appliance settings.
- Persistent recipe progress and safe recovery after power loss.
- Rechargeable battery, USB-C and no soldering in normal assembly.
- Removable suction mount for smooth glazed tile; validate retention under repeated touch and environmental changes. Avoid mounting over hot appliances.
- Record active, idle, sleep and off consumption before setting an autonomy target.
- User recipes stay local; distribute only original or appropriately licensed examples.

## Proposed architecture

ESP-IDF/C++, LVGL, JSON recipe schema, local storage, power manager, board abstraction. EEZ Studio for UI, OpenSCAD for mechanical design, TypeScript for optional desktop tooling. Pin versions after board bring-up.
