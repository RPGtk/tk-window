![top_banner](./.github/banner.jpg)

---

### Hyacinth
![loc_badge](https://github.com/waterlily-team/hyacinth/blob/badges/loc.svg)
![latest_release_badge](https://img.shields.io/github/v/release/waterlily-team/hyacinth?include_prereleases&label=Latest%20Version&color=blue)

A tiny, very specialized windowing wrapper written in [C23](https://en.wikipedia.org/wiki/C23_(C_standard_revision)). It's built to be performant and simple, supporting as many [windowing backends](https://en.wikipedia.org/wiki/Windowing_system) as possible. 

---

#### Support
Hyacinth current supports the following [operating systems](https://en.wikipedia.org/wiki/Operating_system) and [processor architectures](https://en.wikipedia.org/wiki/Instruction_set_architecture).

- [Linux](https://en.wikipedia.org/wiki/Linux): Currently supported. Tested on [`arch`](https://en.wikipedia.org/wiki/Arch_Linux).
    - [x64](https://en.wikipedia.org/wiki/X86-64): Currently supported. Tested on an [`AMD Ryzen™ 5 5600H`](https://en.wikipedia.org/wiki/List_of_AMD_Ryzen_processors#Desktop_processors).
    - [ARM64](https://en.wikipedia.org/wiki/AArch64): **Not yet supported, but planned.**
- [MacOS](https://en.wikipedia.org/wiki/MacOS): **Not yet supported, but planned.**
    - [Apple Silicon](https://en.wikipedia.org/wiki/Apple_silicon): **Not yet supported, but planned.**
- [BSD](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution): **Not yet supported, but planned.**
    - [x64](https://en.wikipedia.org/wiki/X86-64): **Not yet supported, but planned.**
    - [ARM64](https://en.wikipedia.org/wiki/AArch64): **Not yet supported, but planned.**

Hyacinth does not plan to support [Microsoft Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), for it is truly development hell in regards to C.

---

#### Backends
Hyacinth requires, currently, one of the following windowing libraries, and nothing else.

- [Linux](https://kernel.org/):
    - [Wayland](https://wayland.freedesktop.org/): Wayland is a newer windowing library quickly being adopted over X11. This is by **far** preferred to X11 in the context of Hyacinth. Its implementation here is better tested and smaller.
    - [X11](https://www.x.org/wiki/): X11 is a reliable, battle-hardened windowing library that's been around since desktop on Linux was really a thing.

---

![bottom_banner](./.github/banner.jpg)
