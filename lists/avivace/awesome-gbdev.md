<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="avivace/awesome-gbdev">avivace/awesome-gbdev</a> with ranks
</p>
---
# Awesome Game Boy Development [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](#awesome-gbdev)

#### [![GameboyIcon](http://i.imgur.com/ROUq7NT.gif) Join us on Discord](https://discord.gg/gpBxq85)

A curated list of awesome Game Boy Development resources, tools, docs, related projects and open-source ROMs. Inspired by the [awesome ★59088](https://github.com/sindresorhus/awesome) list thing.

Here you can find everything to get started and master the development of unofficial software for the original 1989 Game Boy.

## Contents

- [Intro](#intro)
- [Community](#community)
- [Documentation](#documentation)
  - [Peripherals](#peripherals)
  - [Cartridges](#cartridges)
- [Emulator Development](#emulator-development)
  - [Open-Source emulators](#open-source-emulators)
- [Software Development](#software-development)
  - [Assemblers](#assemblers)
  - [Compilers](#compilers)
  - [Emulators](#emulators)
  - [Tools](#tools)
- [Programming Tutorials](#programming-tutorials)
  - [ASM](#asm)
    + [Glitches and exploits](#glitches-and-exploits)
    + [Timings](#timings)
  - [C](#c)
- [Open-Source Games](#games)
  - [ASM](#asm-1)
  - [C](#c-1)
- [ROMs Disassembly](#roms-disassembly)
- [Related sites, posts and projects](#related-sites-posts-and-projects)
- [About this project](#about)
  - [Contribute](#contribute)
  - [License](#license)
  - [Special Thanks](#special-thanks)

## Intro
- [The Game Boy, a hardware autopsy](https://www.youtube.com/playlist?list=PLu3xpmdUP-GRDp8tknpXC_Y4RUQtMMqEu).
- [The Ultimate Boy Talk](https://media.ccc.de/v/33c3-8029-the_ultimate_game_boy_talk).
- [Emulation of Nintendo Game Boy](https://github.com/Baekalfen/PyBoy/blob/master/PyBoy.pdf) - Overview of the Game Boy hardware with the perspective of building an emulator.

## Community
- [gbdev Discord Server](https://discord.gg/gpBxq85)
- [#gbdev on EFnet](http://chat.efnet.org/?channels=gbdev) - IRC channel.
- [gbdev.gg8.se](http://gbdev.gg8.se) - This is basically the home of the gbdev scene. The [wiki](http://gbdev.gg8.se/wiki/articles/Main_Page) has a lot of articles from previous sites, tutorials and other documents about a lot of topics.
- [devrs.com/gb](http://devrs.com/gb) - Jeff Frohwein’s page, this the main reference for everything. Almost everything is archived here: code examples and working programs(ASM and C), complete documentation and various tools.


## Documentation
- [Game Boy Programming Manual](http://www.chrisantonellis.com/files/gameboy/gb-programming-manual.pdf) - **Official Game Boy** programming & hardware manual by Nintendo. Pretty much everything in the console is covered and explained in this manual. This should be your first and main resource to start understanding what game boy is.
- [The Cycle-Accurate Game Boy Docs](https://github.com/AntonioND/giibiiadvance/blob/master/docs/TCAGBD.pdf) - A precise documentation by AntonioND to make a cicle-accurate Game Boy emulator.
- [Pan Docs](http://bgb.bircd.org/pandocs.htm) - The single most comprehensive technical reference to Game Boy that is available to the public.
- [Everything You Always Wanted To Know About GAME BOY](http://www.emulatronia.com/doctec/consolas/gameboy/gameboy.txt) - but were afraid to ask
- [GBSOUND.txt](https://github.com/bwhitman/pushpin/blob/master/src/gbsound.txt) - A document detailing the Game Boy sound engine.
- [DMG Schematics](http://gbdev.gg8.se/wiki/articles/DMG_Schematics) - Hardware schematics.
- [GB Instructions](http://www.chrisantonellis.com/files/gameboy/gb-instructions.txt) Game Boy Assembly commands.
- [GB ASM Tips](http://www.chrisantonellis.com/files/gameboy/gb-asm-tips.txt) - Some tips for coding in Assembly by Jeff Frohwein.
- [ASMotor Manual](http://www.chrisantonellis.com/files/gameboy/asmotor-v0.1.0-manual.pdf) - A reference for rgbds.
- [ASMotor v1.10 documentation](http://otakunozoku.com/RGBDSdocs/)
- [wla-dx documentation](http://www.villehelin.com/wla.txt) - WLA DX Macro Assembler Package manual.
- [GBDK libraries documentation](http://gbdk.sourceforge.net/doc/gbdk-doc.pdf)
- [gbdev FAQs](http://www.devrs.com/gb/files/faqs.html) - Must read by Jeff Frohwein.
- [Game Boy CPU InstructionSet Sheet (GCISheet)](http://www.devrs.com/gb/files/GBCPU_Instr.html) - Cheatsheet for the available Instruction Set.
- [Opcode table](http://goldencrystal.free.fr/GBZ80Opcodes.pdf)
- [Opcode table with timings and flags](http://www.devrs.com/gb/files/opcodes.html)
- [Game Boy CPU Manual](http://marc.rawer.de/Gameboy/Docs/GBCPUman.pdf) - Assembly language commands, timings and opcodes.
- [Assembly Language Programming Course](http://cratel.wichita.edu/cratel/ECE238Spr08) - Machine and assembly language programming concepts that illustrate basic principles and techniques. Application through study of the Z80 chip and Game Boy programming assignments (Center for Research in Arts, Technology, Education, and Learning CRATEL at Withicha State University).
- [Game Boy Bootrom](http://www.neviksti.com/DMG/DMG_ROM.asm) - Commented dump of the DMG bootrom.
- [GB Technical Information](http://fms.komkon.org/GameBoy/Tech/) - Some old code resources.
- [Differences between the Z80 and the gameboy's processor](http://www.z80.info/z80gboy.txt)
- [Archive of related files](http://gbdev.gg8.se/files/)
- [fruttenboel](http://verhoeven272.nl/fruttenboel/Gameboy/index.html) - Page with loads of information on the actual hardware, custom boards to interface with the console and other related projects.

### Peripherals
- [Game Boy Camera RE ★14 ⏳2Y](https://github.com/AntonioND/gbcam-rev-engineer) - Documentation about GB Camera and tools used to reverse engineer it by using Arduino UNO.
- [Creating photorealistic images with neural networks and a Gameboy Camera](http://www.pinchofintelligence.com/photorealistic-neural-network-gameboy/)
- [The Game Boy Printer](https://shonumi.github.io/articles/art2.html) - An in-depth technical document about the printer hardware, the communication protocol and the usual routine that games used for implementing the print feature.
- [Ben Heck Reverse Engineers Game Boy Printer](https://www.youtube.com/watch?v=43FfJvd-YP4)

### Cartridges
- [AntonioND's docs](https://github.com/AntonioND/giibiiadvance/tree/master/docs) - Corrected schematics and infos on cartridge header data
- [Gekkio's Game Boy cartridge types](http://gekkio.fi/blog/2015-02-14-mooneye-gb-gameboy-cartridge-types.html) - An overview on existing cartridge types.
- [Gekkio](http://gekkio.fi/blog/)'s cartridge analysis - [DMG-BEAN-02](http://gekkio.fi/blog/2015-05-18-mooneye-gb-cartridge-analysis-dmg-bean-02.html), [MBC1](http://gekkio.fi/blog/2015-05-17-mooneye-gb-cartridge-analysis-fortress-of-fear.html), [no MBC](http://gekkio.fi/blog/2015-02-28-mooneye-gb-cartridge-analysis-tetris.html)
- [Game Boy Cartridges Schematics](http://www.devrs.com/gb/files/gb.html) - Schematics for MBC2 and MBC3 types.
- [Cartridges PCB photos](https://imgur.com/a/D5bpC)
- [Reiner Ziegler's Game Boy page](http://www.reinerziegler.de/readplus.htm) - Commercial and homemades programmable cartridges and programming systems. Tutorials, wiring and schematics provided.
- [MBC1+Ram+Battery cartridge Schematic](http://www.devrs.com/gb/files/mbc1.gif) - First schematics by Jeff Frohwein.
- [MBC1 and MBC2 cartridges circuits](http://fms.komkon.org/GameBoy/Tech/Carts.html) and explaination on how these MBC actually bank switch and control RAM.
- [GB Rom List](https://docs.google.com/spreadsheets/d/1cOS__xEj8bBT7cqEDgJcYStKuFAS8mMA4uErx9kA40M/edit?usp=sharing) - Navigable table of every GB game released with details on their cartridges.
- [Game Boy cartridge PCB photos](http://gekkio.fi/blog/2016-03-19-game-boy-cartridge-pcb-photos.html)
- [Emulating a GameBoy Cartridge](https://dhole.github.io/post/gameboy_cartridge_emu_1/) - Emulating the functionality of a GameBoy cartridge with the development board STM32F4.
- [Wolf](http://www.happydaze.se/wolf/) - Gameboy cartridge with co-processor.

## Emulator Development

- [Blargg's test roms](http://gbdev.gg8.se/files/roms/blargg-gb-tests/)
- [Gekkio's test roms](https://gekkio.fi/files/mooneye-gb/latest/)
- [Building a Game Boy emulator in JavaScript](http://imrannazar.com/gameboy-Emulation-in-JavaScript) - Step by step tutorial.
- [Writing a Game Boy emulator, Cinoop](https://cturt.github.io/cinoop.html)
- [RealBoy Emulator](https://realboyemulator.wordpress.com/posts/) - A series of posts about the design and implementation of the RealBoy Emulator
- [Codeslinger](http://www.codeslinger.co.uk/pages/projects/gameboy.html) - Another series of posts documenting the building of an emulator.


### Open-source emulators
- [Mooneye-gb ★154](https://github.com/Gekkio/mooneye-gb) -  A Game Boy research project and emulator written in Rust.
- [php-terminal-Game Boy-emulator ★1167](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) - PHP Terminal
- [gameboy-Online ★165 ⏳1Y](https://github.com/taisel/gameboy-Online) - Javascript, HTML5 canvas and JavaScript audio APIs.
- [cboy ★14](https://github.com/jkbenaim/cboy) - C. Mac OS X and Linux.
- [weplay ★488](https://github.com/rauchg/weplay) - Collaborative Game Boy emulation powered by JavaScript.
- [giibiiadvance ★47 ⏳1Y](https://github.com/AntonioND/giibiiadvance) -  A GB, GBC emulator with GB Camera support. Written in C.
- [GBE+ ★58](https://github.com/shonumi/gbe-plus) - Built in C++ and SDL. Focused on enhancements.
- [Sameboy ★24](https://github.com/LIJI32/SameBoy) - Portable C.
- [GameYob ★115](https://github.com/Drenn1/GameYob) - Emulator for Nintendo (3)DS.
- [oneup-gb ★0](https://github.com/oneup40/oneup-gb) - C++ DMG. Currently provides SDL frontend and Retroarch integration.
- [rustboy ★5](https://github.com/VelocityRa/rustboy) - A basic DMG emulator written in Rust, using the Piston engine for window creation and graphics.
- [Gearboy ★245](https://github.com/drhelius/Gearboy) - C++. iOS, Raspberry Pi, Mac, Windows and Linux.
- [AndroidGameBoyEmulator ★179](https://github.com/pedrovgs/AndroidGameBoyEmulator)
- [GameLad ★251](https://github.com/Dooskington/GameLad) - C++/SDL almost fully featured emulator.
- [Wadatsumi ★8](https://github.com/arrow-lang/wadatsumi) - Arrow.
- [Binjgb ★28](https://github.com/binji/binjgb) - 5kloc emulator in C that passes most of the tests.
- [jgilchrist ★16](https://github.com/jgilchrist/emulator) - Modern C++.
- [gameboyGO ★9](https://github.com/gonccalo/gameboyGO) - Go.
- [GameBoyEmulator-GBS ★22 ⏳1Y](https://github.com/Salgat/GameBoyEmulator-GBS) - C++ 14 with a single library dependency of SFML.
- [PyBoy ★27](https://github.com/Baekalfen/PyBoy) - Python. Mac, Linux and Windows.
- [scimitar ★0](https://github.com/tompko/scimitar) - Rust.
- [FunGBC ★7](https://github.com/andreasjhkarlsson/fungbc) - F#.


## Software Development

### Assemblers
- [rgbds](https://github.com/bentley/rgbds) - Assembler and linker package (a fork currently updated).
- [wla-dx ★147](https://github.com/vhelin/wla-dx) - Yet Another GB-Z80/Z80/.. Multi Platform Cross Assembler Package.
- [gbasm ★94](https://github.com/BonsaiDen/gbasm) - A JavaScript based compiler for Gameboy z80 assembly code.
- [tniASM](http://www.tni.nl/products/tniasm.html) - Macro Assembler.
- [Assembler ★88](https://github.com/ulrikdamm/Assembler) - Assembler written in Swift.

### Compilers
- [The Game Boy Developer's Kit (GBDK)](http://gbdk.sourceforge.net/) - A set of tools that enable to develop programs for the Nintendo Game Boy system in **C**. Includes a set of libraries for the most common requirements and generates image files for use with a real Game Boy.
- [gbdk-osx ★8 ⏳2Y](https://github.com/x43x61x69/gbdk-osx) - Patched GBDK 2.96a for the latest compilers on OS X.

### Emulators
- [BGB](http://bgb.bircd.org/) - Powerful Game Boy emulator and debugger. Provides an accurate hardware emulation.
- [Gambatte](http://sourceforge.net/projects/gambatte/) - Open-source, cross-platform and accurate emulator for Game Boy and Game Boy Color.

### Tools
- [ZGB ★49](https://github.com/Zal0/ZGB) - A little engine for creating games for the original Game Boy (expands gbdk, more info [here](http://zalods.blogspot.com/2017/01/zgb-little-engine-for-game-boy.html)).
- [DevSound ★0](https://github.com/DevEd2/DevSound) - Sound driver embeddable in homebrews which supports pulse width manipulation, arpeggios, and multiple waveforms.
- [Game Boy Tile Data Generator](http://www.chrisantonellis.com/gameboy/gbtdg/) - HTML5 / JS web application that will convert bitmap images to hexidecimal data appropriate for use in tile based graphical applications, specifically GB.
- [rgbds_textmate ★12 ⏳5Y](https://github.com/Bananattack/rgbds_textmate) - Some syntax highlighting rules for coding in Z80 assembly as a Textmate language plugin. Works in Sublime Text 2 and 3\. The syntax is particularly designed for rgbds and Game Boy-specific Z80 instructions.
- [Harry Mulder's GB Development](http://www.devrs.com/gb/hmgd/intro.html) - Some sources and home of Game Boy Tile Designer and Game Boy Map Builder tools.
- [GBT PLAYER ★35](https://github.com/AntonioND/gbt-player) - A music player library and converter kit for Game Boy that can be used with RGBDS.
- [ROM Header Utility](http://catskull.net/GB-Logo-Generator/) - An online tool to inspect and modify a ROM's header data, including the logo.
- [gbcamextract ★8](https://github.com/jkbenaim/gbcamextract) - Extracts photos from Game Boy Camera saves.
- [GBExtended](http://www.tensi.eu/thomas/programming/gameboy/gbextended.html) - C library extending gbdk.
- [GBZ80 to items](http://issotm.github.io/gbz80toitems3/) - 
An online converter, translates gameboy assembly into Pokémon R/B/Y items ([Source ★6](https://github.com/ISSOtm/gbz80-to-items))
- [bmp2cgb ★2](https://github.com/gitendo/bmp2cgb) - 8bpp bitmap converter for Gameboy Color development.

## Programming Tutorials
### ASM
- [ASMSchool](http://gameboy.mongenel.com/asmschool.html) - A set of lessons by Duo about coding in Assembly for GB/GBC and disassembling.
- [dev'rs ASM section](http://www.devrs.com/gb/asmcode.php) - A lot of working demos and sources.
- [Assembly tutorial by David Pello](http://wiki.ladecadence.net/doku.php?do=show&id=tutorial_de_ensamblador) - Good document to actually learn to produce working asm code for gb. Brief explainations of many important topics. Many examples with commented source code (spanish only).
- [Assembly tutorial by David Pello](https://avivace.ovh/apps/gbdev/salvage/tutorial_de_ensamblador%20%5bLa%20decadence%5d.html) - The english version of the resource above.
- [Beginner's Guide to Reverse Engineering GB](http://web.archive.org/web/20150511145100/http://www.bennvenn.com/Beginners_Guide_To_Reverse_Engineering.htm) - Some starting tips on disassembling and reverse engineering.
- [gb-template ★2 ⏳1Y](https://github.com/exezin/gb-template) - A template with basic functions pre-made such as joypad input, DMA transfers, and map/tile data loading.
- [assemblydigest ★35 ⏳3Y](https://github.com/assemblydigest/gameboy) - Exploring Game Boy programming techniques.
- [Reverse Engineering for Beginners](https://beginners.re/) - Free ebook (1060 pages) by Dennis Yurichev.
- [FlappyBoy: Making a simple Game Boy Game](http://voidptr.io/blog/2017/01/21/GameBoy.html)

#### Glitches and exploits
- [DMA hijacking](https://github.com/avivace/awesome-gbdev/blob/master/articles/dma_hijacking.md) - A simple technique that allows you to run custom code in most GB/SGB/CGB games, provided you have an ACE exploit. [Demo video](http://gbdev.gg8.se/forums/viewtopic.php?id=430).
- [Pokèmon Yellow ASM hack](http://pastebin.com/raw.php?i=WaFyrr21) - Debug menu. [Demo video](https://www.youtube.com/watch?v=BkIDPwkeGWs).

#### Timings
- [Game Boy DMA transfer routines](http://exez.in/gameboy-dma) - Understanding and using DMA routines.
- [Nitty Gritty Gameboy Cycle Timing](http://blog.kevtris.org/blogfiles/Nitty%20Gritty%20Gameboy%20VRAM%20Timing.txt)
- [Mode3 Sprite Timing](https://www.reddit.com/r/EmuDev/comments/59pawp/gb_mode3_sprite_timing/)
- [GameBoy Color DMA-Transfers v0.0.1](http://gameboy.mongenel.com/dmg/gbc_dma_transfers.txt)
- [STAT interrupt timings](http://gameboy.mongenel.com/dmg/istat98.txt)

### C
- [8-Bit Wonderland](http://belial.blarzwurst.de/gbpaper/paper.pdf) - Well-written introductory document about how the Game Boy works and how to start developing working code for it.
- [Grooves Game Boy Programming ★26 ⏳2Y](https://github.com/gbdk-salvage/grooves-game-boy-programming) - A complete set of lessons about implementing various game mechanics in a Game Boy game.
- [How to Write a Simple Side Scrolling Game](http://pastebin.com/F3tHLj68) - Old (but still relevant) tutorial.
- [Just another simple tutorial](http://pastebin.com/gzT47MPJ)
- [GBDK Tutorial](https://refreshgames.co.uk/2016/04/18/gameboy-tutorial-rom/) - Fairly minimal game demo for getting started with GBDK.
- [GBDK Sprite](http://gbdev.gg8.se/wiki/articles/GBDK_Sprite_Tutorial) - Presents a workflow for getting multiple sprites to display and animate.
- [GBDK Color](http://gbdev.gg8.se/wiki/articles/GBDK_Color_Tutorial) - Extends your knowledge of basic spriting on the Game Boy by adding colors to sprites, backgrounds and the window layer.
- [GBDK Joypad](http://gbdev.gg8.se/wiki/articles/GBDK_Joypad_Tutorial) - Details the use of the joypad with GBDK.
- [Game Boy home of Flavor](http://www.personal.triticom.com/~erm/GameBoy/) - Some full games and sources.
- [GBDK Configuring and Programming Tutorial](https://videlais.com/2016/07/03/programming-game-boy-games-using-gbdk-part-1-configuring-programming-and-compiling/) - Configuring GBDK, Using Tiles, Colliding Sprites, GBTD, GBMB, Memory Management and ROM Banking.

## Games
- [Infinity ★381](https://github.com/infinity-gbc/infinity)

### ASM
- [RedPlusPlus ★60](https://github.com/TheFakeMateo/RedPlusPlus) - An upgrade to Pokémon Red. Fixes several bugs and adds a lot of new features.
- [Tuff ★264](https://github.com/BonsaiDen/Tuff.gb)
- [2048-gb ★58 ⏳2Y](https://github.com/Sanqui/2048-gb)
- [Snake](https://bitbucket.org/Sanqui/snake/src/?at=master)
- [PlantBoy](https://github.com/siObyte/PlantBoy)
- [Lazerpong ★7 ⏳2Y](https://github.com/huderlem/lazerpong)
- [Back to Color ★14 ⏳2Y](https://github.com/AntonioND/back-to-color)
- [Geometrix ★10 ⏳1Y](https://github.com/AntonioND/geometrix)
- [µCity ★32](https://github.com/AntonioND/ucity)
- [Carazu ★5](https://github.com/mholtkamp/carazu)
- [Snake-gb ★5](https://github.com/DonaldHays/snake-gb)
- [GB303 ★19](https://github.com/furrtek/GB303) - GB303 wavetable-based TB-303 style synthesizer for the Nintendo Gameboy.
- [Pokémon Christmas](https://github.com/TheFakeMateo/xmas)
- [Sushi ★2](https://github.com/JustSid/Sushi)
- [Flappy-boy-asm ★1](https://github.com/bitnenfer/flappy-boy-asm)

### C
- [flappybird-gb ★17 ⏳1Y](https://github.com/LuckyLights/flappybird-gb)
- [FlappyBoy ★9 ⏳2Y](https://github.com/bitnenfer/FlappyBoy)
- [flappybird-gameboy ★1](https://github.com/pashutk/flappybird-gameboy) - Yet another gbdk powered Flappybird clone
- [Novascape](http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=6823)
- [Squishy the Turtle ★4 ⏳1Y](https://github.com/cppchriscpp/SquishyTheTurtle)
- [Quadratino ★7](https://github.com/avivace/quadratino)
- [Doctor How ★14 ⏳1Y](https://github.com/elfgames/doctorhow)
- [Super Princess' 2092 Exodus ★7](https://github.com/Zal0/gbjam2016)
- [GBsnake ★12](https://github.com/brovador/GBsnake)
- [gb-mines ★14](https://github.com/andreasjhkarlsson/gb-mines)
- [oranges](http://www.atari2600land.com/gameboy/oranges.html)
- [red hot princess carnage ★1](https://github.com/Imanolea/bitbitjam3_red_hot_princess_carnage)
- [loderunner](http://www.tensi.eu/thomas/programming/gameboy/loderunner.html)
- [Hives](https://refreshgames.co.uk/2017/04/24/ludum-dare-38-entry-hives/)

## ROMs Disassembly
- [Sonic 1 ★11 ⏳3Y](https://github.com/Kroc/Sonic1-Z80-ASM)
- [Pokémon Red/Blue ★1163](https://github.com/pret/pokered)
- [Pokémon Crystal ★850](https://github.com/pret/pokecrystal)
- [Reverse engineering Kirby's Dreamland 2](http://ecc-comp.blogspot.it/2016/03/reverse-engineering-kirbys-dreamland-2.html)

## Related sites, posts and projects
- [papiGB ★0](https://github.com/diegovalverde/papiGB) - 
Game Boy Classic fully functional FPGA implementation from scratch
- [fpgaboy ★41](https://github.com/trun/fpgaboy) - Implementation Nintendo's Game Boy console on an FPGA.
- [Piglet ★30 ⏳2Y](https://github.com/danShumway/Piglet) - A LUA-driven AI that plays classic Game Boy color games using experimentation. In active development.
- [The Game Boy Project](http://marc.rawer.de/Gameboy/Docs/GBProject.pdf) - Provides a study on the hardware and detailed constructional information for the realisation of three 8-bit bidirectional parallel ports.
- [gbdk-n](https://github.com/rotmoset/gbdk-n) - Aims to update the gbdk libraries to be compatible with new versions of SDCC and provide helpers for building roms.
- [Wiz ★5 ⏳1Y](https://github.com/Bananattack/wiz) - A high-level assembly language for writing homebrew on retro console platforms (Game Boy, NES, Atari 2600, and more).
- [Gatesboy](https://web.archive.org/web/*/http://www.gatesboy.com/) - Non-gaming purposes applications development.
- [pdroms.de](http://pdroms.de/news/gameboy/) Game Boy releases.
- [Game Boy Demospotting](http://gameboy.modermodemet.se/en) - A collection of demos.
- [Nintendo's fake logos](http://fuji.drillspirits.net/?post=87) - Every cartridge has to show the authentic logo to be considered valid and be runned, but obviously some companies managed to exploit the check system.
- [Booting the Game Boy with a custom logo](https://dhole.github.io/post/gameboy_custom_logo/) - Bypassing the Nintendo logo check.
- [GBDK Developers](http://gbdk-developers.com/) - Active blog about everything related to the scene. Including features, insights and interviews.
- [Ostrich ★3](https://github.com/PumpMagic/ostrich) - A Game Boy Sound System player written in Swift.
- [mGB ★39 ⏳1Y](https://github.com/trash80/mGB) - A Gameboy cartridge program that enables the Gameboy to act as a full MIDI supported sound module.
- [GBVisualizer ★10](https://github.com/LIJI32/GBVisualizer) - Demonstrating the use of two undocumented Gameboy Color registers, nicknamed PCM12 (FF76) and PCM34 (FF77), which can be used to read the current PCM amplitude of the 4 APU channels.
- [GBVideoPlayer ★31 ⏳1Y](https://github.com/LIJI32/GBVideoPlayer) - A technical demo demonstrating how the Gameboy LCD controller can be hacked to make a Gameboy Color play a full motion video in color, together with music.
- [rgbgfx ★7](https://github.com/stag019/rgbgfx) - A program which converts PNG images into the Game Boy's planar tile format, for eventual integration into RGBDS.
- [ArduinoGameBoy ★40 ⏳1Y](https://github.com/drhelius/arduinogameboy) - Arduino based Game Boy cartridge reader and writer.
- [gameboy-brainfuck ★2](https://github.com/bitnenfer/gameboy-brainfuck) - 
Implementation of a brainfuck interpreter.


## About

### Contribute
Take a look at [Contribution Guidelines](https://github.com/avivace/awesome-gbdev/blob/master/CONTRIBUTING.md).

### License
Licensed under **GPLv3**.
See [LICENSE](LICENSE) for more information.

### Special Thanks
[Every](https://github.com/avivace/awesome-gbdev/graphs/contributors) contributor of this project, Jeff Frohwein, Pascal Felber, KOOPa, Pan of Anthrox, GABY, Marat Fayzullin, Paul Robson, Martin Korth, BOWSER, neviksti, Martin “nocash" Korth, Nitro2k01, Duo, Chris Antonellis, Michael Hope, Beware, Jonathan “Lord Nightmare” Gevaryahu, Marat Fayzullin, Paul Robson, Carsten Sorense, Sindre Aamås, Otaku No Zoku, GeeBee.
---
<p align="center">
	This list is a copy of <a href="avivace/awesome-gbdev">avivace/awesome-gbdev</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
