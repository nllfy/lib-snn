# lib-ssn

lib-ssn is a library that makes networking and security easier in c

---

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

---

## Introduction

Provide an overview of the project, its purpose, and its features.  
For example:
> `lib-ssn` is a library designed to code networks and cyber security in c it is the libraries designed for the csh-framework in c

### Features
- it makes nettworking in udp and tcp easier in c
- it is Open-Source so anybody can contribute to make it better
- it makes it much easier for people who use c to make cyber security tools

---

## Installation

### Installation Steps

    cd /path/to/your/project/
    git clone https://github.com/nllfy/lib-ssn.git

## Usage

    #include <stdio.h>
    #include "lib-ssn/network.h"

    int main(void)
    {
        tcp_server(8080, "welcome");// first variable is the port second variable is the message variable
    }

## Contributing

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear messages.
4. Push your branch to your forked repository.
5. Open a pull request on the main repository.

### Reporting Issues
If you encounter bugs or have feature requests, please open an issue on GitHub.

---

## License

This project is licensed under the MIT License.  
See the [LICENSE](./LICENSE) file for details.

