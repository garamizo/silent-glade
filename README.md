# silent-glade
Hacking of a automatic aroma spray to reduce night-time noise

## Problem

1. The spray wakes me up at night.
2. It wastes energy and scent when it sprays at an empty room.
3. Manually turning off at night or when I leave is bothersome.
4. Does not spray when I need it the most: when I just arrived at the room.

## Solution

Add a IOT microcontroller, such as ESP32, to manage when to spray. The ESP32 is connected to the home network to know when the owner arrived at/left home.

## Components

- ESP32 ()
- MOSFET ()
- Rechargeable LiFePO4 3.2v battery
- Battery clip