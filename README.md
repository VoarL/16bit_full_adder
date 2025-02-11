# 16bit_full_adder
[![Build status](https://ci.appveyor.com/api/projects/status/yc3leb1t5t6ue01i?svg=true)]()

This is a a Repository containing the design of a 16-bit CMOS full adder in 45nm cadence library

[![License](https://img.shields.io/badge/License-GNU%20GPL-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Issues](https://img.shields.io/github/issues/VoarL/16bit_full_adder.svg)](https://github.com/VoarL/16bit_full_adder/issues)
[![GitHub Stars](https://img.shields.io/github/stars/VoarL/16bit_full_adder.svg)](https://github.com/VoarL/16bit_full_adder/stargazers)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project explores the design and analysis of a 16-bit CMOS full adder optimized for speed. A mirror adder-based ripple carry architecture was selected as the foundational design, which was then extended into a carry-select adder (CSLA) structure. The goal was to achieve a worst-case delay below 400 ps while analyzing power consumption and the power-delay product (PDP) under various operating conditions. Simulations were conducted to validate performance across different process corners and supply voltages, providing insights into the trade-offs between speed, power, and area.
## Features

- A customizable 16-bit carry-select adder using a mirror full adder topology.
- Achieves O(√n) delay for improved performance over traditional ripple carry adders.
- Simulated under multiple process corners (TT 27°C, FF -25°C, SS 85°C) to evaluate worst-case delay and power consumption.
- Analysis of power-delay product across different supply voltages to understand CMOS non-idealities.
- Suitable for high-speed applications where power and area constraints are secondary considerations.

## Installation

- Move files to your local directory and launch using virtuoso and ADE XL.

## Usage

- After running, customize accordingly.
  
## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

