<div align="center">

<img src="assets/silas.jpg" width="128" alt="Silas Godoy" />

### Silas Godoy

<code>sigods</code>

**Linux · Open Source · Automation · Reverse Engineering**

🇧🇷 Brazil

</div>

> Currently: booting a 2002 Xbox game on a machine that has never seen an Xbox.

---

## whoami

I take systems apart to understand how they work, then put them back together somewhere they were never meant to run. Mostly Linux, mostly C, usually while something recompiles in the background.

The interesting part has never been getting it to boot — it's the three days of disassembly it takes to figure out why it booted.

## focus

| | |
| :-- | :-- |
| **Static recompilation** | Translating console binaries into native C. No emulator, no interpreter, no hand-written stand-in for the original logic. |
| **Linux systems** | Low-level plumbing, kernel-adjacent work, build systems, things that run headless and stay running. |
| **Automation** | Scripts written once to delete a manual step permanently. |
| **Reverse engineering** | Disassembly, ABI recovery, tracing a bug down to the single instruction that caused it. |

## selected work

| Project | What it is | Stack |
| :-- | :-- | :-- |
| **[otogi1](https://github.com/sigods/otogi1)** | Static recompilation of *Otogi: Myth of Demons* (FromSoftware / Sega, 2002) into native Linux and Windows executables. Boots the retail XBE, runs the title's own main loop, streams the attract video and BGM. 3D rendering and input are still open. GPL-3.0. | `C11` `CMake` `SDL2` `D3D11` `Capstone` |
| **[xboxrecomp](https://github.com/sigods/xboxrecomp)** | Toolkit that turns an Xbox binary into a native executable — no emulation, no interpreter, just recompiled C. Fork carries the local changes otogi1 depends on. | `C` `Python` `x86` |

## toolchain

![Linux](https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=E6EDF3)
![C](https://img.shields.io/badge/C-161B22?style=flat-square&logo=c&logoColor=E6EDF3)
![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=E6EDF3)
![Bash](https://img.shields.io/badge/Bash-161B22?style=flat-square&logo=gnubash&logoColor=E6EDF3)
![Git](https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=E6EDF3)
![CMake](https://img.shields.io/badge/CMake-161B22?style=flat-square&logo=cmake&logoColor=E6EDF3)

## now

- Drawing the 3D scene in `otogi1` — the pushbuffer decodes, the quads rasterise, the world doesn't render yet.
- Chasing a self-linked queue in the USB path that keeps the pad from ever being polled.
- Reading more disassembly than documentation.

---

<div align="center">

**[github.com/sigods](https://github.com/sigods)** · **[email](mailto:you@example.com)** · **[website](https://example.com)**

<sub>Everything here is built from public documentation, a lot of patience, and code I wrote myself.</sub>

</div>
