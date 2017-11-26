# Node RED: actuate LEDs (interval)

> This repository is a [Node RED](https://nodered.org/) Flow that actuates two LEDs on a set interval and makes the payload (a binary output on the status of a _Pin_) available.

## Table of Contents

- [Hardware](#hardware)
- [Wiring](#wiring)
- [Usage](#usage)
- [Author Information](#author-information)
- [License](#license)

## Hardware

* 1 Raspberry Pi 3
* 1 breadboard
* 2 resistors (270-550 Ohms)
* 3 jumper cables (female to male)
* 2 LEDs

## Wiring

This flow actuates two LEDs; one on _Pin 11_, the other on _Pin 13_.

A wiring diagram is included in the `fritzing.png` file.

## Usage

Import this flow into _Node RED_ by clicking on the hamburger menu, followed by _"Import"_ and _"Clipboard"_.

The import dialogue can also be triggered by pressing `CTRL` and `I` on your keyboard.

Then, paste the contents of `flow.json` into the text area and click _"Import"_.

## Author Information

This flow is currently maintained by the individuals listed below.

- [Kerim Satirli](https://github.com/ksatirli)

Development of this module was sponsored by [Method](https://github.com/withmethod).

## License

Copyright 2017 [Kerim Satirli](https://github.com/ksatirli)

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an _"AS IS"_ basis, without WARRANTIES or conditions of any kind, either express or implied.

See the License for the specific language governing permissions and limitations under the License.
