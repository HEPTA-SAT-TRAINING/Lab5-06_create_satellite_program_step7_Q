# Lab5-06: Create Satellite Program (Step 7 — Question)

Firmware template for building a satellite application: HK downlink, battery-aware 3.3 V switching, and uplink command handling. Commands `c`, `d`, and `e` are left for you to implement.

## Web Serial Monitor

Open in **Chrome or Edge**, then **Add Port** → **Connect** (38400 baud):

**https://hepta-sat-training.github.io/hepta-serial-viewer/**

- HK lines appear every second in the output pane.
- `a` — prints `Hello HEPTA-SAT` ten times (1 s apart).
- `b` — saves battery voltages to `test.txt` on the SD card, then reads the file back over COM.
- `c`, `d`, `e` — implement in `Lab5-06_create_satellite_program_step7_Q.ino`.

## Firmware

Open `Lab5-06_create_satellite_program_step7_Q.ino` in the Arduino IDE and upload to your board. For library and submodule setup, see [src/README.md](src/README.md).
