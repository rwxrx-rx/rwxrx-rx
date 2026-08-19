# Hi, I'm Akbar 👋 (`rwxrx-rx`)

I mess around with Android kernels, mostly on the MediaTek MT6833 chipset (POCO M3 Pro 5G / Redmi Note 10 5G, codename `camellia`). Linux 4.14 non-GKI trees, root frameworks, custom recoveries, and the occasional bootloop at 3am.

## What I'm doing

- Maintaining a custom kernel source tree for the `camellia` platform
- Running a CI/CD pipeline (GitHub Actions + Vercel) that builds the kernel, patches in KernelSU/SuSFS, builds the manager APK, and ships releases straight to Telegram — no local machine needed
- Building a custom TWRP recovery for the same device
- Occasionally touching Rust when the C isn't punishing me enough

## Stack

`C` · `C++` · `Bash` · `Python` · `Rust` · Proton Clang / AOSP LLVM · GitHub Actions

## Projects

| Repo | What it is |
|---|---|
| [kernel_xiaomi_mt6833](https://github.com/rwxrx-rx/kernel_xiaomi_mt6833) | Custom Linux 4.14 kernel source for `camellia` |
| [kernel-ci](https://github.com/rwxrx-rx/kernel-ci) | CI configs and scripts used to build the kernel |
| [KonToLKzuu](https://github.com/rwxrx-rx/KonToLKzuu) | Headless CI/CD pipeline that builds, patches, and ships kernel releases automatically |
| [twrp-android-device-xiaomi-camellia](https://github.com/rwxrx-rx/twrp-android-device-xiaomi-camellia) | TWRP device tree for `camellia` |
