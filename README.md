# AOSP Kernel with KernelSU + SuSFS for Exynos 9611

This is a temporary workaround, since Something New kernel is still under development and is really unstable, I have ported KernelSU to AOSP kernel.

## Features

- KernelSU support (up until [v0.9.5](https://github.com/tiann/KernelSU/releases/download/v0.9.5/KernelSU_v0.9.5_11872-release.apk), since KernelSU has droped non-GKI support)
- KernelSU Next support (strongly recommend using [v1.0.7](https://github.com/KernelSU-Next/KernelSU-Next/releases/download/v1.0.7/KernelSU_Next_v1.0.7_12602-release.apk) or [backslashxx magic mount port](https://github.com/backslashxx/KernelSU/releases))
- SuSFS v1.5.5

I haven't tested other KernelSU versions / variants other than that (e.g. SukiSU Ultra)

### Flashing Instructions

Flash the kernel using custom recovery or via adb sideload.

### Acknowledgements

- [cat658011](https://github.com/cat658011)
- [Tim Zammerman](https://github.com/linux4)
- [Royna2544](https://github.com/Royna2544)
- [Samsung Open Source](https://opensource.samsung.com/)
- [Android Open Source Project](https://source.android.com/)
- [The Linux Kernel](https://www.kernel.org/)
- [backslashxx](https://github.com/backslashxx)
- [simonpunk](https://github.com/simonpunk)
