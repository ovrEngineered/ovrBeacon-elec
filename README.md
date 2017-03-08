# ovrBeacon-elec

![ovrBeacon Profile](https://raw.githubusercontent.com/ovrEngineered/ovrBeacon-elec/master/resources/ovrBeaconProfile.jpg)

This project contains an open-source implementation of a Bluetooth Low Energy sensor beacon.
The beacon has the following features:
 - Integrated temperature sensor
 - Integrated light sensor
 - Integrated accelerometer
 - Remotely controlled LEDs
 - Wireless charging via Qi standard
 
Note: this repository contains the schematics and PCB design. The firmware repository is located [here](https://github.com/ovrEngineered/ovrBeacon-fw).


## Physical Description
![ovrBeacon Dimensions](https://raw.githubusercontent.com/ovrEngineered/ovrBeacon-elec/master/resources/ovrBeaconDimensions.png)

| Height       | Width        | Depth w/ programming header | Depth w/o programming header |
| ------------ | ------------ | --------------------------- | ---------------------------- |
| 1.85" (47mm) | 1.06" (27mm) | 0.57" (14.48mm)             | 0.41" (10.41mm)              |


## Parameters
| Parameter               | Min  | Typical | Max    | Units |
| ----------------------- | ---- | ------- | ------ | ----- |
| Temperature accuracy**  | -    | +/- 1   | -      | °C    |
| Acceleration range      | -16  | -       | +16    | g     |
| Acceleration resolution | -    | 4       | -      | mg    |
| Light sensitivity       | 0.01 | -       | 64,000 | lux   |
| Battery Capactity***    | -    | 500     | -      | mAh.  |
** accuracy can be increased with pin-compatible parts 
*** capacity can be increaded with replacement batteries


## Links
 * [Schematic PDF](output/ovrBeacon_schematic.pdf)
 * [PCB Layout PDF](output/ovrBeacon_layout.pdf)
 
 
## Built With
 * [KiCad](http://kicad-pcb.org/)
 
 
## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 


## License
This project is licensed under the MIT License:

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
