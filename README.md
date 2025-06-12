# 🌌 cOSine

> _A gentle ripple on the surface of system design..._

**cOSine** is a lightweight, experimental operating system crafted for curiosity, creativity, and code. Built as a **hobby project**, it’s not made to power machines—but to inspire minds.

**Not intended for real hardware. Best enjoyed in the comfort of emulators like [QEMU](https://www.qemu.org/) or [Bochs](http://bochs.sourceforge.net/).**

---

## ❓ What *is* cOSine?

**cOSine** (yes, like the math function) is a small-scale operating system for the x86 architecture. It exists to demystify how computers come alive—from the first instruction to the first pixel.

Whether you're into bootloaders, bare-metal coding, or the magic behind multitasking, cOSine is your invitation to peek under the digital curtain.

### 🧪 Core goals:
- Low-level system programming
- Bootloader and kernel design
- Simple multitasking & rudimentary graphics
- A deeper understanding of "how computers boot"

This is **not** a complete OS. It’s an evolving thought experiment—an exploration, not a destination.

---

## ⚠️ Disclaimer

**This is a hobby project** — raw, imperfect, and always in flux.

- ❌ Not stable  
- ❌ Not secure  
- ❌ Not meant for real hardware  
- ✅ Designed for learning and fun  

Use it as a playground, not a platform.

---

## ✨ Features (WIP)

Here’s what you’ll find (or eventually will) inside the world of cOSine:

- 🧼 Minimal bootloader
- 🛡 32-bit protected mode
- 🧠 Basic kernel with system utilities
- 💾 File system support
- 🪟 *(Planned)* Window-like graphical interface

---

## 🚀 Getting Started

### 📦 Requirements

To explore cOSine, you’ll need:

- [`QEMU`](https://www.qemu.org/) (recommended) or `Bochs`
- [`nasm`](https://www.nasm.us/) – Netwide Assembler
- `make`
- Unix-like environment (Linux/macOS/WSL)

---

### 🧰 Build and Run

Clone and launch:

```bash
git clone https://github.com/scovings/cOSine-kernel.git
cd cOSine-kernel
./run.sh
