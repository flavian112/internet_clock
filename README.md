# Internet Clock

A digital clock that syncs it's time with the internet over WiFi.

## Repositories

- [Firmware](https://github.com/flavian112/internet_clock_firmware.git)
- [Hardware](https://github.com/flavian112/internet_clock_hardware.git)

## Resources

- [MM5451](./datasheets/MM5451.pdf) LED Display Driver
- [WL-T7DS](./datasheets/WL-T7DS.pdf) Common Anode 7-Segment Display
- [PTV09-4020S-B104](./datasheets/PTV09-4020S-B104.pdf) Potentiometer (100k)

## Files

### Schematic

![Schematic](./assets/internet_clock_hardware_schematic.svg)

### Board

![Board](./assets/internet_clock_hardware_board.svg)

## Clock Display

![Clock Display](./assets/clock_display.jpg)

![MM5451 Display Example](./assets/mm5451_communication_example.png)

## Usage

The clock is configured with Serial over USB at **9600 Baud**. The following
commands can be used:

- `pt` print the current datetime
- `pz` print the current timezone
- `ps` print the current ssid
- `pp` print the current password
- `sz <timezone>` sets the timezone, i.g. Europe/Zurich
- `ss <ssid>` sets the ssid
- `sp <password>` sets the password
