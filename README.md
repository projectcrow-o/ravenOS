
<div align="center">

<br/>

```
██████╗  █████╗ ██╗   ██╗███████╗███╗   ██╗     ██████╗ ███████╗
██╔══██╗██╔══██╗██║   ██║██╔════╝████╗  ██║    ██╔═══██╗██╔════╝
██████╔╝███████║██║   ██║█████╗  ██╔██╗ ██║    ██║   ██║███████╗
██╔══██╗██╔══██║╚██╗ ██╔╝██╔══╝  ██║╚██╗██║    ██║   ██║╚════██║
██║  ██║██║  ██║ ╚████╔╝ ███████╗██║ ╚████║    ╚██████╔╝███████║
╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝╚═╝  ╚═══╝     ╚═════╝ ╚══════╝
```

**Your hardware. Your data. Your OS.**

[![License: GPL-2.0](https://img.shields.io/badge/License-GPL%202.0-white?style=flat-square&labelColor=000)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Pre--Alpha-white?style=flat-square&labelColor=000)](ROADMAP.md)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-white?style=flat-square&labelColor=000)](CONTRIBUTING.md)
[![Built by Project Crow](https://img.shields.io/badge/Built%20by-Project%20Crow-white?style=flat-square&labelColor=000)](https://github.com/projectcrow)

<br/>

</div>

---

## What is Raven OS?

Raven OS is an independent operating system built from the ground up for people who are tired of their OS working against them.

Not a Linux distro. Not a Windows skin. Something new.

Windows ships with ads, telemetry, and background processes you never asked for. macOS is polished but you're locked into Apple's hardware and Apple's rules. Linux gives you freedom but asks you to earn it first. Raven OS sits in the space none of them occupy — an OS that feels immediately familiar, runs lean, respects your privacy by default, and gives you real control over your own machine.

It's being built alongside the **Rook** — a laptop by Project Crow — so the software and hardware are designed together from day one. That's the only way to get the kind of performance and efficiency that makes a real difference.

---

## Why does this exist?

Most people don't know how much their OS costs them — not in money, but in performance, battery life, privacy, and control.

The average Windows install runs dozens of background processes the user never sees and never consented to. Updates interrupt work. Telemetry ships your usage data. Bloat accumulates until a fresh machine feels slow within a year.

We think that's wrong. And we think enough people agree that it's worth building something better.

---

## Core principles

**Resource-first.** Every process on Raven OS has to earn its place. Nothing runs in the background without a reason. The OS is built to be lean from the kernel up, not lean after the fact.

**Privacy by default.** No telemetry. No usage reporting. No data collection. The camera and microphone have hardware-level kill switches on the Rook. What happens on your machine stays on your machine.

**Familiarity without compromise.** You shouldn't need to relearn how to use a computer. Raven OS borrows the best interaction patterns from Windows and macOS — a taskbar, a file manager, right-click menus that behave the way you expect — without inheriting their baggage.

**Open kernel, open future.** The core of Raven OS is open source and always will be. If you can build something better, build it. The community owns this as much as we do.

---

## Key features

### Flight Controller
A system-level process manager built into the OS, not bolted on as an afterthought. See exactly what every core is doing in real time. Lock your main application to the performance cores. Push background tasks to the efficiency cores. Set profiles for different workflows — coding, gaming, battery saving. No third-party software needed.

### System-wide accent engine
Change the accent colour and it propagates through every element of the UI — window borders, the taskbar, highlighted text, status indicators. White on obsidian black by default. One setting, total consistency.

### Hardware privacy controls
The camera physically cuts power when the kill switch is toggled. Not a software block — actual hardware-level power cut. The microphone follows the same principle. These aren't features we added. They're decisions we made at the design stage.

### MDM-ready architecture
Raven OS ships clean for personal users. For organisations — schools, businesses, institutions — it exposes a full device management API compatible with standard MDM tools. No built-in surveillance layer. Just clean hooks that let IT do their job without compromising everyone else's experience.

### Floating taskbar
A centred, floating dock at the bottom of the screen that expands and contracts fluidly as applications open and close. Clean. Minimal. Yours.

---

## The Rook

Raven OS ships on the **Rook** — a laptop built by Project Crow specifically around this OS.

- ARM-based SoC with dedicated performance and efficiency cores
- Dark matte chassis — polycarbonate gen 1, magnesium alloy gen 2
- 14-inch anti-glare IPS display, 1080p, 400 nits
- UFS 3.1 storage — fast, not the eMMC bottleneck most budget laptops ship with
- Hardware camera kill switch with dedicated toggle
- Customisable function button — assign it to wifi kill, mic mute, do not disturb, whatever you need
- Fingerprint reader built into the power button, logo embossed on the cap
- 2x USB-C, 1x USB-A
- Ships with Raven OS, Windows ARM, or Linux — your choice at order

The Rook is coming. Raven OS is being built now.

---

## Project status

Raven OS is in **pre-alpha**. We're building the foundation.

| Component | Status |
|---|---|
| Project vision and architecture | ✅ Defined |
| Repository structure | ✅ Live |
| Kernel research and selection | 🔄 In progress |
| Compositor / display server | 🔄 In progress |
| Flight Controller prototype | 🔲 Planned |
| UI shell and taskbar | 🔲 Planned |
| Accent engine | 🔲 Planned |
| MDM API layer | 🔲 Planned |
| Alpha release | 🔲 Target: TBD |

---

## How to get involved

This is open source. We need people.

Whether you're a kernel developer, a UI designer, a writer, or just someone who wants to test builds and file bugs — there's a place for you here.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before you open a pull request. It explains how we work, what we need most right now, and how decisions get made.

If you have questions, open a Discussion. If you find a bug, open an Issue. If you want to build something, fork the repo and show us what you've got.

---

## Repository structure

```
ravenOS/
├── kernel/          # Kernel research, patches, and configuration
├── compositor/      # Display server and window management
├── flight-controller/  # Core scheduler and process manager
├── shell/           # Desktop environment, taskbar, launcher
├── accent-engine/   # System-wide theming layer
├── mdm-api/         # Device management API and documentation
├── docs/            # Architecture docs, design decisions, roadmap
└── assets/          # Brand assets, UI mockups, screenshots
```

---

## Community

We're just getting started. Join the conversation:

- **GitHub Discussions** — ideas, questions, architecture debates
- **Issues** — bugs, feature requests, tasks
- Kickstarter and GoFundMe coming soon — follow the repo to get notified

---

## License

Raven OS is licensed under the [GNU General Public License v2.0](LICENSE).

You can use it, modify it, and distribute it. You can't make it proprietary. That's the deal.

---

<div align="center">

**Project Crow** · Raven OS · The Rook

*Built in the open. Owned by everyone.*

</div>
