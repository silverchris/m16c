# Ghidra Processor Module for Renesas M16C Architecture

## Install instructions

Clone this repo into `<ghidra_home>/Ghidra/Extensions/` folder
(don't confuse with `<ghidra_home>/Extensions/`).

That's it, just run Ghidra and select `m16c` language.

## Development Instructions

Install Eclipse, set up a development environment following [this guide](https://github.com/NationalSecurityAgency/ghidra/blob/master/DevGuide.md).

Add GhidraDev Plugin to Eclipse and create a new Ghidra Processor Module following [this other guide](https://spinsel.dev/2020/06/17/ghidra-brainfuck-processor-1.html).

Clone this repo into the newly created module path.

Build and run!
