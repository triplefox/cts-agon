# Agon Newsletter, June 2026

Hello! I was busy in May so I skipped a month, but I plan to continue with this newsletter. Without further ado:

## Firmware and emulator dev
* Fab Agon Emulator 1.2.2
  * https://github.com/tomm/fab-agon-emulator/releases/tag/1.2.2 <br>
  The 1.2 series has added configurable main memory size, various emulation fixes, and support for audio over EZ80 GPIO.
* VDP 2.16.0 "Bistromathics"
  * https://github.com/AgonPlatform/agon-vdp/releases/tag/v2.16.0 <br>
  This version includes more support for the Acorn graphics system's PLOT commands, Y-Modem support, and some bugfixes.
* MOS 3.0.2 "Arthur"
  * https://github.com/AgonPlatform/agon-mos/releases/tag/v3.0.2 <br>
  Bugfixes and improvements for "copy", "rename", "mem", tab-completion, and memory management.

## Software Development
* envenomater - BBC Basic V, v0.8, various fixes and large array support
  * https://github.com/envenomator/agon-bbc-basic/releases/tag/v0.8
* Ellie's Treat Hunt - game for BBC Basic V
  * https://discord.com/channels/1158535358624039014/1158536774008721449/1514009369757352036
* romba1 - I2C routines for Forth24
  * https://discord.com/channels/1158535358624039014/1158753764224802877/1513164485559582770
* Radiotux - "BAT", a modern text viewer
  * https://github.com/Radiotux/Agon-Software/tree/main/bat
* Radiotux - "get", A PC/Agon wireless file transfer system
  * https://discord.com/channels/1158535358624039014/1203663539709935687/1507256069250879578
* Pac-Man - An accurate Agon port of the original Pac-Man game <br>
  * https://github.com/andymccall/pac-man/releases
* Tomm - EZ80 GPIO sound and video
  * https://www.youtube.com/watch?v=S31Ax5gSNiM
  * https://github.com/tomm/vga-ez80
* Inufuto - 23 arcade games for Agon
  * https://www.youtube.com/watch?v=BNsR1mF7htc&list=PLgV8aJVUzcOMPebGdSQtv8p-OkxjWsZSu
  * http://inufuto.web.fc2.com/8bit/
  * All 23 as one zip https://discord.com/channels/1158535358624039014/1158753764224802877/1503119881439019190
* Triplefox - A-Nib - see below
        
## Agon at SoCal Game Expo in Pasadena, CA
* https://socalgamingexpo.com/
    
I visited and showcased the Agon hardware and software with the Bay Area Development (BAD) Collective. 
* https://www.badcollective.games/

This convention invites a lot of vintage collectors, retro enthusiasts, etc. For most of the expo I ran the Pac-Man demo and connected with people who were interested in homebrew arcades and computer education. While I brought units for sale, the interest was towards building awareness and considering a purchase to be shipped later.
    
While building this showcase I put together a page of links, both for the business and for Agon and related information: 
* https://triplefox.github.io/cts-agon/

## A-Nib
    
A-Nib is my Forth-based games framework project for Agon.

The A-Nib codebase has had its first release! This is a software distribution made for the showcase, and contains a custom kiosk launcher. 
* https://triplefox.github.io/cts-agon/a-nib-2026-06-04.zip
    
I am now working towards polishing up the bitmap editor with file management code, using learnings from the launcher. My port of Stephen Stout's "Adventure Creation Kit" from Antic March 1988 may be undertaken this month and represents the culmination of a lot of background work on self-hosted editing tools.

A-Nib Mastodon thread: 
* https://pounced-on.me/@Triplefox/116716465185295173
    
## Other Agon Events in CA This Summer

* https://vcfed.org/events/vintage-computer-festival-west/ August 1-2 - I am signed up for an exhibit, and will also have units in the consignment store
* https://magwest.org/ August 14th-16th - attending, no booth. Will bring a demo unit
* https://caextreme.org/ August 8th-9th - attending, no booth. Will bring a demo unit
    
## Not Agon: Coco-Net

In April, I was asked to participate in Fighting Game Jam 2026. The original team I was invited to started to dissolve within the first week, but I got an idea for a solo project. The result is "Coconut's Coco-Net", a 1v1 "fighting sport with a grappling gun" game where you throw balls at the other player and block them by placing nets.
* https://triplefox.itch.io/coco-net
    
    I'll probably continue to work on the game off and on, and showcase it at BAD events.

