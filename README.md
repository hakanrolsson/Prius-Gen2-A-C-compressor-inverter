# Prius Gen2 A/C Compressor Inverter

This repository contains information and code for interfacing with the A/C compressor inverter from a Toyota Prius Gen2. The goal is to control the A/C compressor for various applications, such as electric vehicle conversions or other custom projects.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Toyota Prius Gen2 A/C compressor inverter is a high-voltage device used to drive the electric A/C compressor in the Prius. This project aims to provide the necessary information and code to control this inverter using an Arduino or other microcontroller. Logs captured with Sigrok from a Prius and when running with the Arduino is attached.

## Features

- Control the A/C compressor inverter using an Arduino
- Example code for interfacing with the inverter
- Documentation on the inverter's communication protocol

## Hardware Requirements

- Toyota Prius Gen2 A/C compressor inverter
- Arduino or compatible microcontroller
- High-voltage power supply (e.g., from a Prius battery pack)
- Necessary wiring and connectors

## Software Requirements

- Arduino IDE

## Installation

1. Clone this repository to your local machine:

    ```sh
    git clone https://github.com/hakanrolsson/Prius-Gen2-A-C-compressor-inverter.git
    ```

2. Open the Arduino IDE and install the necessary libraries.

3. Open the example code provided.

4. Upload the code to your Arduino.

## Usage

1. Connect the Arduino to the A/C compressor inverter according to the wiring diagram provided in the documentation.

2. Power up the inverter with a suitable high-voltage power supply.

3. Use the Arduino to send control signals to the inverter and monitor its operation.

4. Refer to the example code and documentation for details on the communication protocol and control commands.

## Contributing

Contributions are welcome! If you have any improvements or new features to add, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
