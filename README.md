# ZX Multiface 3 Enhanced

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

* If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* You may not use the material for commercial purposes.
* You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

This interface is based on the Multiface 3 clone by Hard Micro and the recreation made by José Leandro Novellón.

# ATTENTION

   - This project was made for retro community, individuals or forums, and NOT FOR COMMERCIAL PURPOSES.
   - Its commercial sale on eBay, auction sites or shops (online or not) is PROHIBITED.
   - So only retro hardware forums and individual people with non profit intentions can build this project.

**I take no responsibiltiy for any damage to any equipment that results from the use of this board.**

USE IT AT YOUR OWN RISK!

# Version 2.0s Final - August 6, 2024

Version 2.0s has been tested an working 100%

# Added version 2.0s (small) - July 04, 2024 - RC2 version, needs to be tested.

   - Redefined Kempston Joystick side (no more GAL22V10D)
   - Stay only three TH components 27E257 (ROMs), 6264/62256 (RAM) and GAL16V8B (MF3 operative) all other componentes now are SMD/SMT.
   - PCB size: 73.1 x 86.3 mm

# Versions 1.5D & 1.5DE - August 12, 2021

A better routing of the boards has been carried out and a power LED has been added.

Version 1.5DE has a rear expansion port.

# Version 1.4D - December 1, 2020

Started in April 2020, I finally got the expected results and created a fully operational and enhanced clone
of the Romantic Robot Multiface 3 for ZX Spectrum +3 computers.

The following project is a modified and improved version of the Multiface 3 interface originally designed by Romantic Robot UK LTD.
The Spanish company Hard Micro made, back in 1988, a clone of the Multiface 3. Since then there have been no more recreations that I know of.

The Multiface 3 is a multipurpose interface designed for ZX Spectrum +3 computers that, among many other functionalities,
allows us to make backup copies of programs or games on tape or disk. If used on the + 2A / + 2B models, such copies can only be made on tape.

The main changes compared to the original model are:

- Dual ROM based on a W27E257
- PAL16L8 replaced by GAL16V8B
- RAM 6264 or 62256 (best to use HM62256ALP-10).
- Tested RAM IC's:
  - HM62256ALP-10
  - HM6264LP-12
  - HY62256A LP-70
  - UT6264CPCL-70LL 
- RESET button.
- Decoupling capacitors for all IC's.
- Horizontal EDGE connector.
- PCB designed to put inside a printed 3D case.
- Kempston Joystick interface (can be enabled or disabled)

# Notes for Gotek (FlashFloppy) users:

- To format a real 3.5" disk to 720k that the ZX +3 can read (+3DOS), the best is to do it with the CPCDiskXP utility.
- These DSK files can be used as real diks to save or load MF3 snapshots.
- You must update the Gotek firmware to the latest FlashFloppy version (at the moment the v3.42).

# General Notes

- All versions, **1.4D, 1.5D & 1.5DE** have been tested on my ZX +3 computers and are working perfectly even with the +3e ROMs by Garry Lancaster (https://worldofspectrum.org/zxplus3e/)

# Links:

- https://www.winuaespanol.com/phpbb3/viewtopic.php?p=5981#p5981
- https://hardware.speccy.org/old.html
- https://k1.spdns.de/Vintage/Sinclair/82/Peripherals/Multiface%20I%2C%20128%2C%20and%20%2B3%20(Romantic%20Robot)/MF3/Technical%20Information/
- https://speccy4ever.speccy.org/_RR.htm

Special thanks to José Leandro, Bone and Cacharreo for their help.

# Original introduction

MULTIFACE 3 is a multi-purpose interface designed exclusively for the
SPECTRUM+3. It provides fully automatic and universal back-up/transfer of
48/128K programs from tape to disk, disk to tape, tape to tape and disk to
disk. It also incorporates a comprehensive toolkit enabling you to
study/modify/develop software. MULTIFACE 3 can copy screens to printer in
hi-res modes and it extends the use of DOS in 48 SPECTRUM mode. MULTIFACE
is menu-driven, fully error-trapped with on-screen prompts and it largely
uses a system of one-touch commands. It is very easy to use and does not
really need a separate written manual. Nonetheless, the following few pages
should help you to understand every aspect of MULTIFACE 3 operations so that
you can use it to its fullest possible potential.
