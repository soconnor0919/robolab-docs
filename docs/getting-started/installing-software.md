# Installing Software

To start using your NAO, you first need to set up a development environment. 

There are five pieces of software you might need.

1. Choregraphe IDE
    - A block-based development environment, which allows for simulation of programs.
2. NAOqi Python SDK
    - Python-based Software Development Kit, with access to the full NAOqi API.
3. NAOqi C++ SDK
    - C++-based Software Development Kit, with access to the full NAOqi API.
4. NAO Flasher
    - Allows the user to create a bootable USB drive in order to flash the NAO's firmware.
5. Robot Settings
    - Allows the user to connect to and manage the robot's settings.


## Recommended Hardware

The majority of development during the semester was done on the following hardware:

![Dell 5520](../assets/dell-5520.png "Dell Precision 5520"){ align="left", width="30%" }

Dell Precision 5520

- CPU: Intel i7-7820HQ
- Memory: 8GB DDR4 2400MHz
- Storage: 512GB NVMe SSD
- Graphics: NVIDIA Quadro M1200 (4GB GDDR5)  

<br>
  
!!! note

    The processor above is of the x86_64 architecture. Minimal testing was done on an Apple Silicon-based MacBook Pro natively, through Rosetta 2, and through Parallels Desktop, all requiring many patches for minimal progress. The rest of this guide assumes you are utilizing similar hardware to that mentioned above.

## Operating System

Development was done using the x86_64 edition of Ubuntu 22.10, which can be downloaded from Canonical [here](https://ubuntu.com/download/desktop/thank-you?version=22.10&architecture=amd64).

Software installation may work on future versions of Ubuntu, however installation was only tested on the version listed above.

## Installation Methods

Installation can be done one of two ways:

- Automatically, using the [robolab-installer](robolab-installer.md)
- Manually, by downloading the software packages from Aldebaran
    - Official installation guides can be found [here](http://doc.aldebaran.com/2-8/index_dev_guide.html).
    - Alternatively, guides can be found on this site [here](manual-installation.md).

