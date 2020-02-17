# fv-1 experiments

Experiments to learn SpinASM - used to program FV-1 DSP chip

The experiments are listed below, the check box indicates if the particular experiment is complete or to be tackled

- [ ] incomplete
- [x] complete

## Assumption

I'll assume that you have an FV-1 development board - it allows you program the EEPROM that is in-place on the board directly from SpinASM IDE. It is possible to program the external EEProm in other ways, the Spin Semiconductor forums are helpful. You could try google `PICkit` - a common tool to help program EEPROM chips - in conjunction with `spin fv-1`.

## Preparation

- [x] Running SpinASM IDE on a Mac
  - [x] Guest Additions
  - [x] Point your SpinASM IDE at your shared folders

[Preparation steps writeups](./preparation/readme.md)

## Fundamentals

- [ ] Save your projects to Github
- [x] Connecting your FV-1 to your windows machine
- [ ] loading program onto EEprom using development board SPIN1001
- [ ] setting up a project with multiple programs in SpanASM IDE

[Fundamentals writeups](./fundamentals/readme.md)

## Simple

- [ ] pass-through
- [ ] Volume control
- [ ] High pass filter

[Simple experiments writeups](simple/readme.md)