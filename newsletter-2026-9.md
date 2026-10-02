## Agon Newsletter, September 2026

## avalonbits development tools:

* [acc](https://github.com/avalonbits/acc), a C compiler for Agon that runs on MOS.

* [aed](https://github.com/avalonbits/aed), a text editor, has been updated with syntax highlighting:

* [hub](https://github.com/avalonbits/hub), a "resident shell" that automates the process of one program 
running another and returning afterwards.
* [zap](https://github.com/avalonbits/zap), a fast eZ80 assembler compatible with ez80asm:

* The work on zap also motivated improvements in the [original ez80asm](https://github.com/AgonPlatform/agon-ez80asm).

## CP/M Plus

> "This is a port of CP/M Plus (also known as CP/M 3) for the Agon Light open source modern retro computer.
> 
> It is styled after Amstrad CP/M Plus for the CPC and PCW range of computers."
* [AgonCPM3](https://github.com/SanPollo/agoncpm3)

## Agon Jukebox

* [v0.11.0-beta with directory-wide playlist progression](https://github.com/bgates747/AgonJukebox)

## Games

* [Foggy's Quest](https://github.com/xianpinder/Agon/tree/main/Foggy), a platforming game made with MPAGD, is now complete.

* [Fuchs und Katzen](https://github.com/avysk/fuk), a computerized version of the Fox and Hound board game, written in Agon Forth.

* [Space Patrol](https://github.com/absayuti/SpacePatrol), a port of the July 1984 COMPUTE Gazette type-in game.

* [Untitled 2D Platformer](https://discord.com/channels/1158535358624039014/1548769972732428399/1551256571298713762) from lovejoy777. Work-in-progress.

## MOS, Emulation and Hardware

* The next release of MOS, [Eirene MOS 3.1.0](https://github.com/AgonPlatform/eirene-mos/releases/tag/3.1.0_beta_1), is in beta.

* [A new emulation of the ESP32 Xtensa architecture, flexe.](https://github.com/levkropp/flexe) Not yet integrated
with any Agon projects.

* [Agon Extender](https://discord.com/channels/1158535358624039014/1548625992652693606/1548625992652693606), a project to add a second, updated VDP with the RISC V ESP32-P4,
and various targeted improvements to speed and capability of I/O.

## Cartooning the Screen and a-nib

* Work has started on a new comic episode, the "Ship of Theseus", based on the talk I gave at California Extreme.

* a-nib is undergoing architectural revisions to use a message-queue focused system, based on the principles of J. Paul Morrison's "Flow-Based Programming"(FBP).
  * This is the fourth major revision, based on needs identified with each application a-nib supports(palette editor, bitmap editor, launcher).
  * This change lightens the pressure to use the Forth stack, and will aid in writing decoupled and reusable code, e.g. supporting different input devices for gaming, or string processing for menus.
  * Emphasis is expected to move more strongly towards supporting demonstration games after this.
