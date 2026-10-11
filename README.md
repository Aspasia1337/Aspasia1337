<div align="center">

# Aspasia1337

**Reverse engineering - Windows internals, Android, game security.**

Focus: VAC / anti-cheat internals · Windows kernel drivers · IAT and module-streaming research

![C++](https://img.shields.io/badge/C%2B%2B-0d0a12?style=flat-square&logo=cplusplus&logoColor=ff7518)
![x86-64](https://img.shields.io/badge/x86--64-0d0a12?style=flat-square&logoColor=ff7518)
![Windows Kernel](https://img.shields.io/badge/Windows_Kernel-0d0a12?style=flat-square&logo=windows&logoColor=9b30ff)
![Android](https://img.shields.io/badge/Android-0d0a12?style=flat-square&logo=android&logoColor=9dff00)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-0d0a12?style=flat-square&logoColor=ff7518)
![Anti-Cheat](https://img.shields.io/badge/Anti--Cheat-0d0a12?style=flat-square&logoColor=9b30ff)

</div>

---

### VAC / Anti-Cheat
*Reverse engineering Valve Anti-Cheat and the internals around it.*

**[Aspasia](https://github.com/Aspasia1337/Aspasia)** - CS2 reverse engineering and cheat prototyping framework

**[cs2-vac-internals](https://github.com/Aspasia1337/cs2-vac-internals)** - VAC scan pipeline: message protocol, VEH handler, server-directed diagnostics

**[VAC-ModuleDumper](https://github.com/Aspasia1337/VAC-ModuleDumper)** - VAC module dumper and loader architecture

**[IATResolution](https://github.com/Aspasia1337/IATResolution)** - IAT reconstruction in modules streamed from server: how VAC resolves imports at runtime to hide API usage from static analysis

**[handle-hijacker](https://github.com/Aspasia1337/handle-hijacker)** - Windows process injection via handle hijacking: leveraging existing process handles to evade detection

### Kernel
*Ring-0 drivers for memory protection, telemetry and injection control.*

**[ring0-bouncer](https://github.com/Aspasia1337/ring0-bouncer)** - Kernel driver: process memory protection, handle hijack prevention, injection filtering

**[hypercall](https://github.com/Aspasia1337/hypercall)** - Windows kernel telemetry and communication layer

### Tools
*Small utilities for the reverse-engineering workflow.*

**[yet-another-ida-rpc](https://github.com/Aspasia1337/yet-another-ida-rpc)** - Discord Rich Presence plugin for IDA Pro 9.x

**[WG10B-Helper](https://github.com/Aspasia1337/WG10B-Helper)** - Helper library for the WG10B smartcard

### Linux / Setup
*The machine and dotfiles behind the work.*

**[arch-niri](https://github.com/Aspasia1337/arch-niri)** - My Arch Linux rig: niri scrollable-tiling Wayland setup plus AMD GPU passthrough (VFIO) for Windows VMs

---

Everything here is free to **clone, fork, and improve** - no strings attached. I learned all of this from people who shared their work openly, so I try to do the same: if any of this helps you learn, build, or get unstuck, it has done its job. Contributions, fixes, and ideas are always welcome.

### Thanks

Built on the shoulders of the communities that taught me - this is my small way of giving back to them:

**[UnknownCheats](https://www.unknowncheats.me)** · **[Guided Hacking](https://guidedhacking.com)** · **[secret.club](https://secret.club)** · **[Vergilius Project](https://www.vergiliusproject.com)**
