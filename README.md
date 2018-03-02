# Home Assistant Blink

A (hopefully) simple exmple of how to read and write to a Raspberry Pi gpio pins using [Home Assistant](https://home-assistant.io/). 

Home Assistant utilizes [binary_sensor](https://home-assistant.io/components/binary_sensor/) to READ gpio ports and [switch] (https://home-assistant.io/components/switch/) to SET the state of gpio ports. This does not make intuitive sense when looking at the schematic.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

* Hardware

    * Wire Breadboard per diagram
    
        ![](https://github.com/jkobie/hass_io_blink/blob/master/fritzing/ha_led_schem.png?raw=true)
    
* Upload code
    
        Upload yamal files to /config directory
     
* Restart Home Assistant   

    
## Usage

Open http://hassio.local:8123/states/group.foo .  You should have port_21 sensor and led_1 switch. Toggle led_1 to turn on/off the physical LED.

The physical switch should also toggle the physical LED.

Feel free to remove any sections that aren't applicable to your project.

## Support

Please [open an issue](https://github.com/jkobie/hass_io_blink/issues) for support.

## Contributing

Please contribute using [Github Flow](https://github.com/jkobie/hass_io_blink/). Create a branch, add commits, and [open a pull request](https://github.com/fraction/readme-boilerplate/compare/)
