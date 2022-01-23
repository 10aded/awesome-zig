# Awesome Zig

> 📜Zig Learning & Usage Guide.

[<img src="https://ziglang.org/zig-logo-light.svg" align="right" width="100">](https://ziglang.org)

[Zig](https://ziglang.org/) is a general-purpose programming language and toolchain for maintaining robust, optimal, and reusable software.

**Thanks to all the project authors and others who made this project possible.**

**Note🗒️An project may also be a development tool, application, library or other category, but it will only appear once in this guide.**

## Table Of Contents

- [Related Web Sites](#related-web-sites)
- [Development Tools](#development-tools)
  - [Editor Plugins](#editor-plugins)
  - [Package Managers](#package-managers)
  - [Other Tools](#other-tools)
- [Applications](#applications)
  - [Command Line](#command-line)
  - [Compiler / Parser / Interpreter](#compiler--parser--interpreter)
  - [Database](#database)
  - [Embedded](#embedded)
  - [Game and Desktop Applications](#game-and-desktop-applications)
  - [Operating Systems / Kernels](#operating-systems--kernels)
  - [Simulator](#simulator)
  - [Web](#web)
  - [Other Applications](#other-applications)
- [Libraries](#libraries)
  - [Audio](#audio)
  - [Database Operation](#database-operation)
  - [Encryption / Encoding / Decoding](#encryption--encoding--decoding)
  - [Game Dev and GUI Dev](#game-dev-and-gui-dev)
  - [Terminal / Low-Level Libraries / System API](#terminal--low-level-libraries--system-api)
  - [Universal](#universal)
    - [Algorithms and Data Structures](#algorithms-and-data-structures)
    - [Memory Management](#memory-management)
    - [Other Universal Libraries](#other-universal-libraries)
  - [Web](#web)
- [Resources](#resources)
  - [Community](https://github.com/ziglang/zig/wiki/Community)
  - [Introduction Or News](#introduction-or-News)
  - [Learning](#learning)
- [Contributing](https://github.com/C-BJ/awesome-zig/blob/main/CONTRIBUTING.md)

## Related Web Sites

- [Zig Official Website](https://ziglang.org/)
- [Zig Github Page](https://github.com/ziglang)
- [Zig News](https://zig.news/)
- [Zig Community List](https://github.com/ziglang/zig/wiki/Community)
- [Learning Zig](https://ziglearn.org/)
- [Zig Monthly](https://zigmonthly.org/)
- [Zig Showtime](https://zig.show/)
- [Zig.Run](https://zig.run/)
- [Zig Playground](https://zig-play.dev/)
- [Andrew Kelley's  (founder of zig) Personal Blog](https://andrewkelley.me/)
- [Loris Cro's Personal Blog](https://kristoff.it/)

## Development Tools

- ### Editor Plugins

  - [intellij-zig🗒️The IntelliJ IDEA plugin for the Zig programming language](https://github.com/ice1000/intellij-zig)
  - [kde-syntax-highlighting🗒️kde xml file for zig syntax highlighting ](https://github.com/ziglang/kde-syntax-highlighting)
  - [sublime-zig-language🗒️Zig language support for Sublime Text ](https://github.com/ziglang/sublime-zig-language)
  - [vscode-zig🗒️Zig language support for VSCode ](https://github.com/ziglang/vscode-zig)
  - [zig-mode🗒️Zig mode for Emacs ](https://github.com/ziglang/zig-mode)
  - [zig.vim🗒️Vim configuration for Zig ](https://github.com/ziglang/zig.vim)

- ### Package Managers

  - [asdf-zig🗒️zig plugin for asdf version manager https://github.com/asdf-vm/asdf](https://github.com/cheetah/asdf-zig)
  - [gyro🗒️A Zig package manager with an index, build runner, and build dependencies. ](https://github.com/mattnite/gyro)
  - [zpm🗒️Package dependency generator; WIP ](https://github.com/zigtools/zpm)
  - [zigmod🗒️📦 A package manager for the Zig programming language. ](https://github.com/nektro/zigmod)

- ### Other Tools

  - [jaz🗒️A JVM implementation in Zig! ](https://github.com/zig-java/jaz)
  - [repository🗒️A community-maintained repository of zig packages ](https://github.com/ziglibs/repository)
  - [setup-zig🗒️use a @ziglang compiler in your github actions workflows](https://github.com/goto-bus-stop/setup-zig)
  - [svd2zig🗒️Convert System View Description (svd) files to Zig headers for baremetal development ](https://github.com/justinbalexander/svd2zig)
  - [xmake🗒️🔥 A cross-platform build utility based on Lua ](https://github.com/xmake-io/xmake)
  - [zig-doctest🗒️A tool for testing snippets of code, useful for websites and books that talk about Zig. ](https://github.com/kristoff-it/zig-doctest)
  - [zigfmt-web🗒️zig fmt on the web ](https://github.com/shritesh/zigfmt-web)
  - [zig-header-gen🗒️Automatically generate headers/bindings for other languages from Zig code ](https://github.com/suirad/zig-header-gen)
  - [zig-pypi🗒️The Zig programming language, packaged for PyPI ](https://github.com/ziglang/zig-pypi)
  - [zigup🗒️Download and manage zig compilers. ](https://github.com/marler8997/zigup)
  - [zls🗒️Zig LSP implementation + Zig Language Server ](https://github.com/zigtools/zls)

## Applications

- ### Command Line

  - [crisp🗒️A Minimal Lispy Calculator ](https://github.com/rvcas/crisp)
  - [outfieldr🗒️A TLDR client in Zig.](https://gitlab.com/ve-nt/outfieldr)
  - [pbui-main🗒️The main repository for the PBUI project ](https://github.com/pbui-project/pbui-main)
  - [sudokuinzig🗒️Sudoku solver in zig ](https://github.com/user00e00/sudokuinzig)

- ### Compiler / Parser / Interpreter

  - [arocc🗒️A C compiler written in Zig. ](https://github.com/Vexu/arocc)
  - [base32🗒️base32 encoding/decoding for ziglang ](https://github.com/gernest/base32)
  - [bog🗒️Small, strongly typed, embeddable language. ](https://github.com/Vexu/bog)
  - [brainfuck-zig🗒️Brainfuck interpreter written in zig ](https://github.com/dantecatalfamo/brainfuck-zig)
  - [cmdlinezig🗒️A simple command line parser ](https://github.com/travisstaloch/cmdlinezig)
  - [hzzp 🗒️A I/O agnostic HTTP/1.1 parser and encoder for Zig.](https://github.com/truemedian/hzzp)
  - [koino🗒️CommonMark + GFM compatible Markdown parser and renderer ](https://github.com/kivikakk/koino)
  - [libpcre.zig🗒️Zig bindings to libpcre ](https://github.com/kivikakk/libpcre.zig)
  - [liz🗒️Lisp-flavored general-purpose programming language (based on Zig) ](https://github.com/dundalek/liz)
  - [LoLa🗒️LoLa is a small programming language meant to be embedded into games. ](https://github.com/MasterQ32/LoLa)
  - [luf🗒️Statically typed, embeddable, scripting language written in Zig. ](https://github.com/Luukdegram/luf)
  - [rem🗒️An HTML parsing library, written in Zig. ](https://github.com/chwayne/rem)
  - [rotate-zig🗒️a programming language written in zig ](https://github.com/Airbus5717/rotate-zig)
  - [zig-clap🗒️Simple command line argument parsing library ](https://github.com/Hejsil/zig-clap)
  - [zigmkv🗒️wip Matroska/webm (mkv) parser in Zig ](https://github.com/vi/zigmkv)
  - [zig-parse-args🗒️Parse command line arguments. ](https://github.com/winksaville/zig-parse-args)
  - [zig-parse-number🗒️Implement ParseNumber which can parse any TypeId.Int or TypeId.Float. ](https://github.com/winksaville/zig-parse-number)
  - [zig-regex🗒️A regex implementation for the zig programming language ](https://github.com/tiehuis/zig-regex)
  - [zig-ryu🗒️Zig port of https://github.com/ulfjack/ryu](https://github.com/tiehuis/zig-ryu)
  - [zig-toml🗒️A TOML parser written in Zig ](https://github.com/aeronavery/zig-toml)
  - [ziguid🗒️GUID parsing/stringifying with zig ](https://github.com/goto-bus-stop/ziguid)
  - [zig-yaml🗒️YAML parser for Zig ](https://github.com/kubkon/zig-yaml)
  - [zuri🗒️URI parser for Zig ](https://github.com/Vexu/zuri)

- ### Database
  
  - [redis-cuckoofilter🗒️Hashing-function agnostic Cuckoo filters for Redis ](https://github.com/kristoff-it/redis-cuckoofilter)
  - [sqlite-zig SQLite bindings ](https://github.com/leroycep/sqlite-zig)
  - [tigerbeetle🗒️A distributed financial accounting database designed for mission critical safety and performance to power the future of financial services. ](https://github.com/coilhq/tigerbeetle)
  - [zig-cassandra🗒️Cassandra CQL client ](https://github.com/vrischmann/zig-cassandra)
  - [zig-okredis🗒️Zero-allocation Client for Redis 6+ ](https://github.com/kristoff-it/zig-okredis)
  - [zig-sqlite🗒️zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig. ](https://github.com/vrischmann/zig-sqlite)

- ### Embedded
  
  - [embedded_zig🗒️minimal Zig embedded ARM example (STM32F103 blue pill) ](https://github.com/tralamazza/embedded_zig)
  - [uefi-paint🗒️UEFI-bootable touch paint app ](https://github.com/nrdmn/uefi-paint)
  - [zig-armv8m-test🗒️Minimal Zig-based app for Armv8-M + TrustZone ](https://github.com/yvt/zig-armv8m-test)
  - [zig-bare-metal-microbit🗒️Bare metal microbit program written in zig ](https://github.com/markfirmware/zig-bare-metal-microbit)
  - [Ziguana-Game-System🗒️A retro-style gaming console running on bare x86 metal written in Zig ](https://github.com/MasterQ32/Ziguana-Game-System)
  
- ### Game and Desktop Applications

  - [blink🗒️A game about building logic with lasers ](https://github.com/Stenodyon/blink)
  - [clashos🗒️multiplayer arcade game for bare metal Raspberry Pi 3 B+ ](https://github.com/andrewrk/clashos)
  - [curses-minesweeper🗒️Minesweeper game written in curses with zig ](https://github.com/Akuli/curses-minesweeper)
  - [fundude🗒️Gameboy emulator:Zig -> wasm ](https://github.com/fengb/fundude)
  - [legend-of-swarkland🗒️Hack-n-slash roguelike inspired by NetHack ](https://github.com/thejoshwolfe/legend-of-swarkland)
  - [kisa🗒️Text editor of the new world ](https://github.com/greenfork/kisa)
  - [minesweeper-zig🗒️Simple Minesweeper clone written in Zig, using SDL for graphics. ](https://github.com/Ryp/minesweeper-zig)
  - [MiniPixel🗒️Tiny pixel art editor ](https://github.com/fabioarnold/MiniPixel)
  - [mogwai🗒️Graphic utility used to manipulate objects in 3D for scene editing (commonly called Gizmo). ](https://github.com/kooparse/mogwai)
  - [pacman.zig🗒️Simple Pacman clone written in Zig. ](https://github.com/floooh/pacman.zig)
  - [rayray🗒️A tiny GPU raytracer, using Zig and WebGPU ](https://github.com/mkeeter/rayray)
  - [river🗒️A dynamic tiling Wayland compositor ](https://github.com/riverwm/river)
  - [snake-zig 🗒️A simple snake game written in the Zig programming language using OpenGL 2. ](https://github.com/fabioarnold/snake-zig)
  - [SoftRenderLib🗒️A collection of software rendering routines ](https://github.com/MasterQ32/SoftRenderLib)
  - [tetris🗒️A simple tetris clone written in zig programming language. ](https://github.com/andrewrk/tetris)
  - [weekend-raytracer-zig🗒️A Zig implementation of the "Ray Tracing in One Weekend" book ](https://github.com/Nelarius/weekend-raytracer-zig)
  - [zalgebra🗒️Linear algebra library for games and real-time graphics. ](https://github.com/kooparse/zalgebra)
  - [zig-gorillas🗒️A clone of the classic QBasic Gorillas written in the Zig programming language ](https://github.com/fabioarnold/zig-gorillas)
  - [Zig-Oculus-Quest🗒️An example application for the Oculus Quest, written in Zig ](https://github.com/SpexGuy/Zig-Oculus-Quest)
  - [ZigPaint🗒️A simple paint application written in Zig. Used to create an OpenGL loader/wrapper and a minimal UI system. ](https://github.com/MasterQ32/ZigPaint)
  - [zig-raylib-experiments🗒️Some classic game implementations in Zig using raylib ](https://github.com/BitPuffin/zig-raylib-experiments)
  - [zig-raytrace🗒️simple raytracer in zig ](https://github.com/tiehuis/zig-raytrace)
  - [zig-vulkan-triangle🗒️simple triangle displayed using vulkan, glfw, and zig ](https://github.com/andrewrk/zig-vulkan-triangle)
  - [zig-wasm-snake🗒️Classic snake game written in Zig, compiled to WASM. ](https://github.com/holobeat/zig-wasm-snake)
  - [zootdeck🗒️Fediverse GTK Desktop Reader ](https://github.com/donpdonp/zootdeck)
  - [zstack🗒️Line-race tetris mode in Zig ](https://github.com/tiehuis/zstack)

- ### Operating Systems / Kernels

  - [daintree🗒️ARMv8-A/RISC-V kernel (with UEFI bootloader) ](https://github.com/kivikakk/daintree)
  - [georgios🗒️Hobby Operating System ](https://github.com/iguessthislldo/georgios)
  - [HellOS🗒️"hello world" x86 kernel example ](https://github.com/andrewrk/HellOS)
  - [Hidamari🗒️Modern operating system aimed at running WebAssembly code. ](https://github.com/HidamariProject/Hidamari)
  - [kernel-zig🗒️hobby x86 kernel zig ](https://github.com/jzck/kernel-zig)
  - [Lukarnel🗒️A microkernel in zig with rust microservices ](https://github.com/DorianXGH/Lukarnel)
  - [microzig🗒️Unified abstraction layer and HAL for several microcontrollers ](https://github.com/ZigEmbeddedGroup/microzig)
  - [pluto🗒️An x86 kernel written in Zig ](https://github.com/ZystemOS/pluto)
  - [trOS🗒️tiny aarch64 baremetal OS thingy ](https://github.com/sjdh02/trOS)
  - [uefi-examples🗒️UEFI examples in Zig ](https://github.com/nrdmn/uefi-examples)
  - [ZBZZ.OS🗒️An operating system built with RISCV and Zig ](https://github.com/ZeeBoppityZagZiggity/ZBZZ.OS)
  - [zen🗒️Experimental operating system written in Zig ](https://github.com/AndreaOrru/zen)
  - [zig-bare-metal-microbit🗒️Bare metal microbit program written in zig ](https://github.com/markfirmware/zig-bare-metal-microbit)
  - [zig-bare-metal-raspberry-pi🗒️Bare metal raspberry pi program written in zig ](https://github.com/markfirmware/zig-bare-metal-raspberry-pi)
  - [zigish🗒️A toy Unix shell written in Zig ](https://github.com/ratfactor/zigish)
  - [zig-x86_64🗒️Support for x86_64 specific instructions (e.g. TLB flush), registers (e.g. control registers), and structures (e.g. page tables) ](https://github.com/leecannon/zig-x86_64)

- ### Simulator

  - [chip8-zig🗒️A CHIP-8 emulator written in Zig ](https://github.com/GrooveStomp/chip8-zig)
  - [ichigo🗒️WIP🍓 Virtual Boy emulator ](https://github.com/sourgrasses/ichigo)
  - [fundude🗒️Gameboy emulator:Zig -> wasm](https://github.com/fengb/fundude)
  - [kc85.zig🗒️A KC85 emulator written in Zig ](https://github.com/floooh/kc85.zig)
  
- ### Web

  -  [cosmic🗒️A simple and productive Javascript/WASM runtime. ](https://github.com/fubark/cosmic)
  -  [hello🗒️Multi-threaded cross-platform HTTP/1.1 web server example in Zig. ](https://github.com/lithdew/hello)
  -  [lua-in-the-browser🗒️using zig to build lua for webassembly ](https://github.com/andrewrk/lua-in-the-browser)
  -  [zig-v8🗒️Simple V8 builds with C and Zig bindings. ](https://github.com/fubark/zig-v8)
  -  [zig-wasm-dom🗒️Zig + WebAssembly + JS + DOM ](https://github.com/shritesh/zig-wasm-dom)
  -  [zig-wasm-test🗒️A minimal Web Assembly example using Zig's build system. ](https://github.com/meheleventyone/zig-wasm-test)
  -  [zss🗒️zss is a CSS layout engine and renderer. ](https://github.com/chwayne/zss)
  -  [zwld🗒️Experimental wasm linker ](https://github.com/Luukdegram/zwld)

- ### Other Applications

  - [geteltorito-zig🗒️ geteltorito re-write in Zig ](https://github.com/hspak/geteltorito-zig)
  - [hexdump-zip🗒️produce an annotated hexdump of a zipfile ](https://github.com/thejoshwolfe/hexdump-zip)
  - [iotmonitor🗒️Monitor and State server for iot mqtt devices, and software agents. This daemon permit to maintain the execution of constellations of mqtt devices and associated agents ](https://github.com/mqttiotstuff/iotmonitor)
  - [wayfarer🗒️Experiments involving a Zig Wayland compositor. ](https://github.com/dominikh/wayfarer)
  - [zig-ios-example🗒️Minimal build.zig for targeting iOS ](https://github.com/kubkon/zig-ios-example)
  - [zig-minisign🗒️Minisign reimplemented in Zig. ](https://github.com/jedisct1/zig-minisign)
  - [zig-protobuf🗒️a protobuf 3 implementation for zig. ](https://github.com/Arwalk/zig-protobuf)
  - [zig-snappy🗒️Snappy compression for Zig ](https://github.com/gsquire/zig-snappy)

## Libraries

- ### Audio

  - [zig-midi 🗒️](https://github.com/Hejsil/zig-midi)
  
- ### Database Operation

  - [zig-sqlite🗒️zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig. ](https://github.com/vrischmann/zig-sqlite)

- ### Encryption / Encoding / Decoding

  - [zig-args🗒️Simple-to-use argument parser with struct-based config ](https://github.com/MasterQ32/zig-args)
  - [zig-charm🗒️A Zig version of the Charm crypto library. ](https://github.com/jedisct1/zig-charm)
  - [zig-clap🗒️Simple command line argument parsing library ](https://github.com/Hejsil/zig-clap)
  - [zigimg🗒️Zig library for reading and writing different image formats ](https://github.com/zigimg/zigimg)
  - [zig-qoi🗒️Quite OK Image format encoder/decoder written in Zig ](https://github.com/MasterQ32/zig-qoi)
  - [zig-wayland🗒️Zig wayland scanner and libwayland bindings ](https://github.com/ifreund/zig-wayland)
  - [zjson🗒️Minimal json library with zero allocations ](https://github.com/xyaman/zjson)

- ### Game Dev and GUI Dev

  - [Alka🗒️Simple, fast, easy to get started mid-level game engine written in Zig ](https://github.com/Kiakra/Alka)
  - [cupcake🗒️an app framework for making small and delicious games! (very wip) ](https://github.com/bootradev/cupcake)
  - [didot🗒️Zig 3D game engine. ](https://github.com/zenith391/didot)
  - [IUPforZig🗒️Zig idiomatic and type-checked bindings for IUP Portable User Interface Toolkit ](https://github.com/batiati/IUPforZig)
  - [mach🗒️Mach is a game engine & graphics toolkit for the future. ](https://github.com/hexops/mach)
  - [mach-glfw🗒️Ziggified GLFW bindings with 100% API coverage, zero-fuss installation, cross compilation, and more. ](https://github.com/hexops/mach-glfw)
  - [metronome🗒️A set of tools for modifying and randomizing Pokémon games ](https://github.com/TM35-Metronome/metronome)
  - [notcurses-zig-example🗒️Demo showing how to use Notcurses library for building terminal UIs with Zig ](https://github.com/dundalek/notcurses-zig-example)
  - [qml_zig🗒️QML bindings for the Zig programming language ](https://github.com/kassane/qml_zig)
  - [raylib-zig🗒️Manually tweaked, auto generated raylib bindings for zig. https://github.com/raysan5/raylib](https://github.com/Not-Nik/raylib-zig)
  - [SDL.zig🗒️A shallow wrapper around SDL that provides object API and error handling ](https://github.com/MasterQ32/SDL.zig)
  - [seizer🗒️Cross platform Zig library for obtaining a rendering context and loading assets ](https://github.com/leroycep/seizer)
  - [slingworks🗒️Small to Medium scale 2d Game Engine for Zig ](https://github.com/JonSnowbd/slingworks)
  - [tm35-nds🗒️A library for working with Nintendo DS roms ](https://github.com/TM35-Metronome/tm35-nds)
  - [vulkan-zig🗒️Vulkan binding generator for Zig ](https://github.com/Snektron/vulkan-zig)
  - [wasm4🗒️Build retro games using WebAssembly for a fantasy console. ](https://github.com/aduros/wasm4)
  - [zalgebra🗒️Linear algebra library for games and real-time graphics. ](https://github.com/kooparse/zalgebra)
  - [zero-graphics🗒️Application framework based on OpenGL ES 2.0. Runs on desktop machines, Android phones and the web ](https://github.com/MasterQ32/zero-graphics)
  - [zgt🗒️Zig GUI Toolkit:Portable library for making native GUIs in Zig ](https://github.com/zenith391/zgt)
  - [zglfw🗒️A thin, idiomatic wrapper for GLFW. Written in Zig, for Zig! ](https://github.com/Iridescence-Technologies/zglfw)
  - [zig-gamedev-lib🗒️xq's Zig Game Development Library ](https://github.com/MasterQ32/zig-gamedev-lib)
  - [zig-gamedev🗒️Building game development ecosystem for @ziglang! ](https://github.com/michal-z/zig-gamedev)
  - [Zig-Game-Engine ](https://github.com/danielabbott/Zig-Game-Engine)
  - [zig-gamekit🗒️Companion repo for zig-renderkit for making 2D games ](https://github.com/prime31/zig-gamekit)
  - [ZigGBA🗒️Work in progress SDK for creating Game Boy Advance games using Zig programming language. ](https://github.com/wendigojaeger/ZigGBA)
  - [Zig-Gltf-Display🗒️A program that displays glTF files using Vulkan, written in Zig. ](https://github.com/SpexGuy/Zig-Gltf-Display)
  - [Zig-PSP🗒️A project to bring the Zig Programming Language to the Sony PlayStation Portable! ](https://github.com/zPSP-Dev/Zig-PSP)
  - [zig-renderkit🗒️ Cross platform Zig graphics backends with a 2D focus ](https://github.com/prime31/zig-renderkit)
  - [zig-sdl🗒️self-contained SDL2 package for Zig ](https://github.com/andrewrk/zig-sdl)
  - [zig-sfml-wrapper🗒️A zig wrapper for csfml ](https://github.com/Guigui220D/zig-sfml-wrapper)
  - [zig-window🗒️window client library ](https://github.com/andrewrk/zig-window)
  - [zig-wlroots🗒️Zig bindings for wlroots ](https://github.com/swaywm/zig-wlroots)
  - [zlm🗒️Zig linear mathemathics ](https://github.com/ziglibs/zlm)
  - [zplay🗒️A simple framework intended for game/tool creation. ](https://github.com/jack-ji/zplay)
  - [ZT🗒️A zig based Imgui Application framework ](https://github.com/JonSnowbd/ZT)

- ### Terminal / Low-Level Libraries / System API

  - [ansi-term🗒️Zig library for dealing with ANSI terminals ](https://github.com/ziglibs/ansi-term)
  - [dos.zig🗒️Create DOS programs with Zig ](https://github.com/jayschwa/dos.zig)
  - [known-folders🗒️Provides access to well-known folders across several operating systems ](https://github.com/ziglibs/known-folders)
  - [mibu🗒️Pure Zig library for low-level terminal manipulation. ](https://github.com/xyaman/mibu)
  - [zig-serial🗒️Serial port configuration library for Zig ](https://github.com/MasterQ32/zig-serial)
  - [x86-zig🗒️library for assembling x86 in zig (WIP) ](https://github.com/momumi/x86-zig)
  - [zig-win32🗒️Bindings for win32, with and without WIN32_LEAN_AND_MEAN ](https://github.com/GoNZooo/zig-win32)

- ### Universal

  - #### Algorithms and Data Structures

    - [ArrayVec🗒️An array with a vector feeling in Zig ](https://github.com/DutchGhost/ArrayVec)
    - [deque.zig🗒️a lock free chase-lev deque for zig ](https://github.com/emekoi/deque.zig)
    - [fastfilter🗒️fastfilter:Binary fuse & xor filters for Zig (faster and smaller than bloom filters) ](https://github.com/hexops/fastfilter)
    - [it/redis-cuckoofilter🗒️Hashing-function agnostic Cuckoo filters for Redis ](https://github.com/kristoff-it/redis-cuckoofilter)
    - [Lazy-Zig🗒️Linq in Zig ](https://github.com/BraedonWooding/Lazy-Zig)
    - [LZig4🗒️Implementing lz4 in zig.](https://github.com/BarabasGitHub/LZig4)
    - [zig-containers🗒️A container library for Zig. ](https://github.com/Sahnvour/zig-containers)
    - [zig-cuckoofilter🗒️Production-ready Cuckoo Filters for any C ABI compatible target. ](https://github.com/kristoff-it/zig-cuckoofilter)
    - [zig-prometheus🗒️Prometheus/VictoriaMetrics client library for Zig ](https://github.com/vrischmann/zig-prometheus)
    - [zig-sparse-set🗒️Sparse sets for zig, supporting both SOA and AOS style ](https://github.com/Srekel/zig-sparse-set)
    - [zigstr🗒️Zigstr is a UTF-8 string type for Zig programs. ](https://github.com/jecolon/zigstr)
    - [zig-string🗒️A String Library made in Zig ](https://github.com/JakubSzark/zig-string)
    - [zigtimsort🗒️TimSort implementation for Zig ](https://github.com/marijnfs/zigtimsort)

  - #### Memory Management

    - [adma🗒️A general purpose, multithreaded capable slab allocator for Zig ](https://github.com/suirad/adma)
    - [Seal🗒️An allocator that wraps another allocator and detects if memory is leaked after usage ](https://github.com/suirad/Seal)
    - [zee_alloc🗒️tiny Zig allocator primarily targeting WebAssembly ](https://github.com/fengb/zee_alloc)
    - [ziegfried🗒️A general-purpose memory allocator for Zig ](https://github.com/mdsteele/ziegfried)
    - [zig-gc🗒️A super simple mark-and-sweep garbage collector written in Zig. ](https://github.com/Hejsil/zig-gc)
    - [zig-rcsp🗒️Reference-counted Shared Pointer for Zig ](https://github.com/yrashk/zig-rcsp)
    
  - #### Other Universal Libraries

    - [getty🗒️Serialization framework for Zig ](https://github.com/getty-zig/getty)
    - [interface.zig🗒️Dynamic dispatch for zig made easy ](https://github.com/alexnask/interface.zig)
    - [log.zig🗒️a thread-safe logging library for zig. ](https://github.com/emekoi/log.zig)
    - [sokol🗒️minimal cross-platform standalone C headers ](https://github.com/floooh/sokol)
    - [sokol-zig🗒️Zig bindings for the sokol headers (https://github.com/floooh/sokol)](https://github.com/floooh/sokol-zig)
    - [zap🗒️An asynchronous runtime with a focus on performance and resource efficiency. ](https://github.com/kprotty/zap)
    - [zig-datetime🗒️A date and time module for Zig ](https://github.com/frmdstryr/zig-datetime)
    - [ziglyph🗒️Unicode text processing for the Zig programming language. ](https://github.com/jecolon/ziglyph)
    - [zig-regex🗒️A regex implementation for the zig programming language ](https://github.com/tiehuis/zig-regex)
    - [zoltan🗒️A Sol-inspired minimalist Lua binding for Zig. ](https://github.com/ranciere/zoltan)

- ### Web

  - [foxwren🗒️A WebAssembly runtime in zig ](https://github.com/malcolmstill/foxwren)
  - [h11🗒️I/O agnostic HTTP/1.1 implementation for Zig  ](https://github.com/ducdetronquito/h11)
  - [htmlentities.zig🗒️HTML entity data for Zig ](https://github.com/kivikakk/htmlentities.zig)
  - [http🗒️HTTP core types for Zig 🦴 ](https://github.com/ducdetronquito/http)
  - [ip.zig🗒️A Zig library for working with IP Addresses ](https://github.com/euantorano/ip.zig)
  - [rem🗒️An HTML parsing library, written in Zig. ](https://github.com/chwayne/rem)
  - [routez🗒️Http server for Zig ](https://github.com/Vexu/routez)
  - [snow🗒️A small, fast, cross-platform, async Zig networking framework built on top of lithdew/pike. ](https://github.com/lithdew/snow)
  - [wasmer-zig🗒️Zig bindings for the Wasmer WebAssembly runtime ](https://github.com/zigwasm/wasmer-zig)
  - [wasmtime-zig🗒️Zig embedding of Wasmtime ](https://github.com/zigwasm/wasmtime-zig)
  - [wasm-zig🗒️Common Wasm runtime binding to C API ](https://github.com/zigwasm/wasm-zig)
  - [wazm🗒️Web Assembly Zig Machine ](https://github.com/fengb/wazm)
  - [wz 🗒️An I/O agnostic WebSocket 1.3 library for Zig.](https://github.com/truemedian/wz)
  - [zhp🗒️A Http server written in Zig ](https://github.com/frmdstryr/zhp)
  - [zigdig🗒️naive dns client library in zig ](https://github.com/lun-4/zigdig)
  - [zigly🗒️The easiest way to write services for Fastly's Compute@Edge in Zig. ](https://github.com/jedisct1/zigly)
  - [zig-network🗒️A smallest-common-subset of socket functions for crossplatform networking, TCP & UDP ](https://github.com/MasterQ32/zig-network)

## Resources

**Content that has appeared in [Related Web Sites](#related-web-sites) will not appear here again** 

- ### [Community](https://github.com/ziglang/zig/wiki/Community)

- ### Introduction Or News
  
  - [Interview with Zig language creator Andrew Kelley - YouTube](https://www.youtube.com/watch?v=ZvskDoP09Ao&t=253s)
  - [The Road to Zig 1.0 - Andrew Kelley - YouTube](https://www.youtube.com/watch?v=Gv2I7qTux7g)
  - [Zig language:a WAY better C! - YouTube](https://www.youtube.com/watch?v=J6ZxxnSp_fY&t=2s)
  - [Zig Programming Language - YouTube](https://www.youtube.com/watch?v=ygfGO5n1Oe4)
  - [Zig SHOWTIME - YouTube](https://www.youtube.com/channel/UC2EQzAewrC10KCDFSS4j-zA)
  - [Zig Star History](https://star-history.com/#ziglang/zig&Date)

- ### Learning

  - [Learning the Zig programming language with help from its creator and core team - YouTube](https://www.youtube.com/watch?v=O4UYT-brgrc)
  - [learnopengl🗒️https://learnopengl.com tutorials ported to zig ](https://github.com/cshenton/learnopengl)
  - [zig-by-example.github.io🗒️learn Zig, by example](https://github.com/zig-by-example/zig-by-example.github.io)
  - [ziglearn🗒️Repo for https://ziglearn.org content. Get up to speed with Zig quickly. ](https://github.com/Sobeston/ziglearn)
  - [ziglings🗒️Learn the Zig programming language by fixing tiny broken programs. ](https://github.com/ratfactor/ziglings)
  
# The End
