
# Dumpx - Hexdump

This repository contains a simplified version of the hexdump command implemented in PowerShell. The script allows users to display the contents of a file in hexadecimal format, similar to the hexdump utility in Linux.

## Features
* Hexdump Operation: Reads a specified file and outputs its contents in hexadecimal format.

* User-Friendly Interface: Prompts the user for commands and provides clear instructions and error messages.

* Command Validation: Validates user input to ensure correct command usage.




## Table of contents

* [Prerequisites](##Prerequisites)
* [Installation](##Installation)
* [Usage](##Usage)
* [Examples](##Examples)
* [Contributing](##Conributing)


## Prerequisites
PowerShell Version: Ensure you have PowerShell installed on your system. The script is compatible with PowerShell 5.1 or later versions.

* Windows: PowerShell is included by default in Windows operating systems. For the best experience, ensure you have the latest version available for your Windows version
* ```Microsoft.PowerShell.Utility``` Module: This script utilizes the ```Format-Hex``` cmdlet, which is included in the Microsoft.PowerShell.Utility module. However, this module is usually included by default in both Windows PowerShell and PowerShell Core installations.

## Installation
To install and set up the Dumpx, follow these steps:

* Clone the repository
    ```sh
    https://github.com/snadeem03/Dumpx---Hexdump
     ```
* Add the executable path to environment variables
* Run the executable. 



## Usage
To use the Dumpx, follow these steps:

* Open the terminal
* Run the executable with appropriate arguments
    ```sh
    dumpx <filename>

    ```

* The script will output the hexadecimal format of the contents of the file



## Examples
Here are some examples of how to use the dumpx:

#### Decoding 

```sh
dumpx simple.txt 

```

*output*
```mathematica
 Path: C:\Users\shaik\playgrounds\tools\encoders\sample.txt

           00 01 02 03 04 05 06 07 08 09 0A 0B 0C 0D 0E 0F

00000000   FF FE 48 00 65 00 6C 00 6C 00 6F 00 20 00 74 00  ._H.e.l.l.o. .t.
00000010   68 00 69 00 73 00 20 00 69 00 73 00 20 00 73 00  h.i.s. .i.s. .s.
00000020   61 00 6D 00 70 00 6C 00 65 00 0D 00 0A 00        a.m.p.l.e.....

```




## Contributing 
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

* Fork this project
* Create your Feature Branch (git checkout -b feature/AmazingFeature)
* Commit your Changes (git commit -m 'Add some AmazingFeature')
* Push to the Branch (git push origin feature/AmazingFeature)
* Open a Pull Request





## Acknowledgements

 - [Hexdump](https://man7.org/linux/man-pages/man1/hexdump.1.html)


