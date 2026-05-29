<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Tiny Tapeout is a project that lets people design and manufacture their own tiny integrated circuits (ASICs) without paying the enormous costs normally associated with chip fabrication.

You write a small digital hardware design, submit it online, and your design gets combined with hundreds of others onto one shared silicon chip. After fabrication, you can test your own real hardware.

Here’s the workflow.

Instead of writing software, you write hardware logic using a hardware description language like:

Verilog
SystemVerilog

Example projects:

LED blinker
Calculator
CPU
Game logic
Audio synthesizer

## How to test
Tiny Tapeout provides templates and CI automation.

Main repo:

Tiny Tapeout Template Repository

The flow automatically:

runs simulations
checks pin usage
validates synthesis
estimates area
runs linting



## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
Hardware	Purpose
Breadboard	Prototyping connections
LEDs	Output indication
7-segment display	Numeric display
PMOD module	Expansion interface
Push buttons	User input
DIP switches	Manual input selection
VGA monitor	Video output
OLED display	Graphics/text output
UART-to-USB adapter	Serial communication
Logic analyzer	Signal debugging
Oscilloscope	Timing verification
