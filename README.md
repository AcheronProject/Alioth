# Acheron Alioth PCB

<p align="center">
  <img align="middle" src="https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronLong.png"  width="400"> 
</p>

See [this page](https://gondolindrim.github.io/AcheronDocs/alioth/intro.html) for the Alioth documentation.

# Features

Alioth is an open-source replacement PCB for the Polaris keyboard. It is powered by an STM32F072 MCU and supports a big array of layout options, including:

- Full and split backspace
- Full and split right shift
- ANSI and ISO options
- Stepped caps lock

Alioth also features:

- Per-key single color LEDs
- Flex or relief cuts
- USBC connection
- QMK firmware compatibility

# Pictures

Yet not available as of june 25, 2020.

# Plate files

In the __polaris_plates__ folder there are the KiCad files for the ANSI and ISO versions of the half and full plates of the Polaris. These files can be submitted to a PCB manufacturer such as Elecrow to be manufactured in FR4 material. There are also SVG vectorized files which can be used to produce these plates in any other material.

# Licensing

Alioth is released under the Acheron Open-Hardware License AOHL version 1.3; see the __LICENSE.md__ file included in the root folder of this repository. However, the files in the ``polaris_resources`` folder were not authored by the Acheron Project but by the original Polaris PCB designer, ai03, and as such are subject to their own licensing. These files were obtained by Gondolindrim from [ai03's public repository](http://dl.ai03.me) in June 24, 2020. These files are licensed under the __README.txt__ file in the __polaris_resources__ folder. For commercial use of the files, please contact ai03 directly. Even with this license, permission to use these files to design the replacement Alioth PCB was given from ai03 to Gondolindrim expressly.

Commercial use of this PCB is licensed under the AOHL 1.3, but it would be a good idea to contact ai03 since the Polaris is a KBDFans product.
