# Broca

A Simple 4 Channels HiFi Eurorack Mixer.

This module is inspired by the [Doepfer A-138n](https://doepfer.de/a138n.htm) and uses some parts of the schematics of the [Befaco STMix](https://www.befaco.org/stmix/).

While inspired by those modules, it is better at handling audio signals because of it's high quality components specifically designed for high quality audio applications.  

## Features

- 4 mono channels with independent volume control
- 1 output
- 1 inverted output
- High quality audio capacitors (Nichicon MUSE ES Bipolar)
- High quality audio amplifiers (Texas Instruments OPA4134)
- 4 HP
- 0.005 mA +12V
- 0.005 mA -12V

This module is designed to mix audio signals with very low noise and distorsion.

Mixing CV signals is also possible but low frequency signals can get distorted in unexpected ways, try it and see if it works for you :)

While using high quality audio components, this module still end up being quite cheap to build if you order parts in bulk.  
However, if you want to make it for even cheaper or use more widely available components, feel free to replace the MUSE ES capacitors (C9, C10, C11, C12) by any regular 10µF unipolar electrolytic capacitor (make sure to respect polarity) and the OPA4134 amplifiers by some TL074.

## Where to buy

The module will soon be available on [my Tindie store](https://www.tindie.com/stores/mentalnoise/) as a kit or fully assembled but feel free to build it yourself from scratch using the resources in this repository.

## Schematics

All schematics can be found in the [schematics folder](./schematics).

To import the schematics:
- Install EasyEDA at https://easyeda.com/ and download the standard edition
- Import [schematics.json](./schematics/schematics.json) in EasyEDA editor by clicking the document icon on the topbar, "Document" > "Open" > "EasyEDA Source", and select the json file

![Broca - Mental Noise - Schematics](./schematics/broca.png)