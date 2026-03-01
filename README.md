-=(Saturn_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound.

Important: Senhor does not support Dual SDRAM (at least for now).

Dev notes: Synthesize ST-V and Saturn in a separate folder or use the clean.bat after synthesizing each one. They share common files and that has side effects on the synthesized binaries.

For ST-V using a reworked STV.sdc as well as this line in files.qip "set_global_assignment -name SDC_FILE STV.sdc". To synthesize use Quartus 23.

___
# [Sega Saturn](https://en.wikipedia.org/wiki/Sega_Saturn) for MiSTer

## Hardware Requirements

- 128 MB SDRAM Module (Primary)
- SDRAM Module of any size (32MB-128MB) (Secondary)

> **Note:** Dual SDRAM modules is recommended for better compatibility.

## Status

Current status is WIP/Beta

Known issues:

