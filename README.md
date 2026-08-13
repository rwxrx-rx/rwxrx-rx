<div align="center">

# Akbar Fatur Rochman

### Low-level developer — Linux kernel & Android internals

Building, breaking, and rebuilding kernels for the MediaTek MT6833 platform.
Currently automating what used to take a local machine into fully headless CI/CD.

[![X](https://img.shields.io/badge/X-dmesg__panic-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/dmesg_panic)
[![Instagram](https://img.shields.io/badge/Instagram-_rwxrxrx-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/_rwxrxrx)
[![Email](https://img.shields.io/badge/Email-akbarfatur.dev%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:akbarfatur.dev@gmail.com)

</div>

---

## About

I work on the parts of Android that most people never see — kernel trees, root frameworks, and the build systems behind them. Most of my time goes into a custom Linux 4.14 (non-GKI) kernel for the MediaTek MT6833 (Poco M3 Pro 5G / Redmi Note 10 5G, codename `camellia`), along with the CI/CD pipeline that builds it.

- 🔧 Maintaining a non-GKI kernel tree with scheduler tuning and LTO optimization
- 🛡️ Integrating KernelSU and its forks (Next, SukiSU Ultra, xxKSU, ReSukiSU) with SuSFS
- ☁️ Moving kernel + manager APK builds fully onto GitHub Actions — no local hardware required
- 📦 Occasional recovery builder work (TWRP / OrangeFox) between kernel builds

## Currently building

**[KonToLKzuu](https://github.com/rwxrx-rx/KonToLKzuu)**
A GitHub Actions pipeline that compiles and patches non-GKI kernels for `camellia` — toolchain setup, KernelSU/SuSFS patching, and manager APK builds, all headless.

**[kernel_xiaomi_mt6833](https://github.com/rwxrx-rx/kernel_xiaomi_mt6833)**
The kernel source tree itself: scheduler tuning and ThinLTO on top of the stock Linux 4.14 base.

## Tech stack

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

![Linux](https://img.shields.io/badge/Linux%20Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![LLVM](https://img.shields.io/badge/LLVM%2FClang-262D3A?style=for-the-badge&logo=llvm&logoColor=white)

## GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=rwxrx-rx&show_icons=true&hide_border=true&theme=tokyonight" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rwxrx-rx&layout=compact&hide_border=true&theme=tokyonight" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rwxrx-rx&hide_border=true&theme=tokyonight" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rwxrx-rx&theme=tokyo-night&hide_border=true" width="95%" />

<img src="https://github-profile-trophy.vercel.app/?username=rwxrx-rx&theme=tokyonight&no-frame=true&row=1&column=6" />

</div>

### Contribution snake

<div align="center">

<img src="https://raw.githubusercontent.com/rwxrx-rx/rwxrx-rx/output/github-contribution-grid-snake.svg" width="95%" />

</div>

---

<div align="center">
<sub>Building for <code>camellia</code>, one CI run at a time.</sub>
</div>
