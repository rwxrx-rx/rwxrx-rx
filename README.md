<div align="center">

<h1><code>&lt; ROOT@RWXRX-RX:~ &gt;</code></h1>
<p><i>"Converting caffeine & sleep deprivation into compiled zImage-dtb"</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Kernel-Linux_4.14.x-7aa2f7?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Platform-MediaTek_MT6833-ff9e64?style=for-the-badge&logo=android&logoColor=black" />
  <img src="https://img.shields.io/badge/Toolchain-LLVM%2FClang_17+-7dcfff?style=for-the-badge&logo=llvm&logoColor=black" />
  <img src="https://img.shields.io/badge/CI%2FCD-Vercel_%2B_GitHub_Actions-9ece6a?style=for-the-badge&logo=githubactions&logoColor=black" />
</p>

</div>

---

### 🖥️ `cat /proc/developer_info`

| Parameter | Value / Live Status |
| :--- | :--- |
| **Main Architecture** | ARM64 (aarch64) — Linux 4.14 Custom Kernel Tree |
| **Target Device** | MediaTek MT6833 (`camellia` / `camellian`) |
| **Security Hooks** | KernelSU (Official / Next / SUKISU / ReSUKISU) + SuSFS 4.14 + BBG |
| **Debugging Method** | `adb pull /sys/fs/pstore/` & screaming at `ramoops` |
| **Compiler Strategy** | `-Wno-everything` *(If the compiler doesn't report errors, it's a feature)* |
| **Mental Health** | `0x00000000` (NULL Pointer Dereference / Core Dumped) |

---

### 💀 SYSTEM DIAGNOSTICS & CRASH LOGS

```text
[   0.000000] Linux version 4.14.x-KonToLKzuu (rwxrx-rx@github-actions)
[   0.000001] Initializing caffeine levels......................... [ OK ]
[   0.000002] Mounting /dev/brain.................................. [ FAILED: Corrupted File System ]
[   0.000003] Injecting SuSFS 4.14 & KernelSU hooks............... [ HIDDEN FROM SAFETYSENSE ]
[   0.000004] Executing build.sh... 666 compiler warnings ignored.
[   0.000005] KERNEL PANIC: Bootloop detected on target 'camellia'.
[   0.000006] System halted. Re-flashing stock boot.img at 3:00 AM... 💀


<p align="center">
  <img src="https://img.shields.io/badge/Kernel-Linux_4.14.x-7aa2f7?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Platform-MediaTek_MT6833-ff9e64?style=for-the-badge&logo=android&logoColor=black" />
  <img src="https://img.shields.io/badge/Toolchain-LLVM%2FClang_17+-7dcfff?style=for-the-badge&logo=llvm&logoColor=black" />
  <img src="https://img.shields.io/badge/CI%2FCD-Vercel_%2B_GitHub_Actions-9ece6a?style=for-the-badge&logo=githubactions&logoColor=black" />
</p>

</div>

---

### 🖥️ `cat /proc/developer_info`

| Parameter | Value / Live Status |
| :--- | :--- |
| **Main Architecture** | ARM64 (aarch64) — Linux 4.14 Custom Kernel Tree |
| **Target Device** | MediaTek MT6833 (`camellia` / `camellian`) |
| **Security Hooks** | KernelSU (Official / Next / SUKISU / ReSUKISU) + SuSFS 4.14 + BBG |
| **Debugging Method** | `adb pull /sys/fs/pstore/` & screaming at `ramoops` |
| **Compiler Strategy** | `-Wno-everything` *(If the compiler doesn't report errors, it's a feature)* |
| **Mental Health** | `0x00000000` (NULL Pointer Dereference / Core Dumped) |

---

### 💀 SYSTEM DIAGNOSTICS & CRASH LOGS

```text
[   0.000000] Linux version 4.14.x-KonToLKzuu (rwxrx-rx@github-actions)
[   0.000001] Initializing caffeine levels......................... [ OK ]
[   0.000002] Mounting /dev/brain.................................. [ FAILED: Corrupted File System ]
[   0.000003] Injecting SuSFS 4.14 & KernelSU hooks............... [ HIDDEN FROM SAFETYSENSE ]
[   0.000004] Executing build.sh... 666 compiler warnings ignored.
[   0.000005] KERNEL PANIC: Bootloop detected on target 'camellia'.
[   0.000006] System halted. Re-flashing stock boot.img at 3:00 AM... 💀
```

---

### 🛠️ TECH MATRIX & TOOLCHAIN

<table align="center" width="100%">
  <tr>
    <td align="center" width="22%"><b>Languages</b></td>
    <td><code>C</code> • <code>C++17/20</code> • <code>Rust (lpud)</code> • <code>Bash</code> • <code>Python3</code></td>
  </tr>
  <tr>
    <td align="center" width="22%"><b>Kernel & Root</b></td>
    <td><code>ARM64 Linux 4.14</code> • <code>KernelSU Multi-Fork</code> • <code>SuSFS 4.14</code> • <code>Baseband-Guard</code></td>
  </tr>
  <tr>
    <td align="center" width="22%"><b>Toolchains</b></td>
    <td><code>Proton-Clang 17+</code> • <code>AOSP Clang</code> • <code>GCC 13+</code> • <code>LLVM LTO</code></td>
  </tr>
  <tr>
    <td align="center" width="22%"><b>Automation & Cloud</b></td>
    <td><code>GitHub Actions</code> • <code>Vercel Serverless API</code> • <code>Telegram Bot Webhook</code> • <code>Docker</code></td>
  </tr>
</table>

---

### 📦 FEATURED DEPLOYMENTS

| Repository | Scope & Description | Status |
| :--- | :--- | :---: |
| ⚡ **[kernel_xiaomi_mt6833](https://github.com/rwxrx-rx/kernel_xiaomi_mt6833)** | Custom 4.14 kernel tree for MT6833 (`camellia`) tuned with ThinLTO & latency patches | `BUILDING` 🚀 |
| 🛡️ **[KonToLKzuu](https://github.com/rwxrx-rx/KonToLKzuu)** | Automated CI/CD pipeline for 4.14 non-GKI kernels, SuSFS, KernelSU & APK Manager | `STABLE` ⚡ |

---

### 📊 TELEMETRY MATRIX

<p align="center">
  <img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=rwxrx-rx&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=rwxrx-rx&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=rwxrx-rx&theme=tokyonight&hide_border=true&border_radius=8" height="150"/>
</p>

---

### 📡 TRANSMISSION ENDPOINTS

<p align="center">
  <a href="https://github.com/rwxrx-rx">
    <img src="https://img.shields.io/badge/PRIMARY_NODE-@rwxrx--rx-7aa2f7?style=for-the-badge&logo=github&logoColor=black" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/weslahmales">
    <img src="https://img.shields.io/badge/ALT_ARCHIVE-@weslahmales-bb9af7?style=for-the-badge&logo=github&logoColor=black" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:akbarfatur.dev@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-akbarfatur.dev@gmail.com-f7768e?style=for-the-badge&logo=gmail&logoColor=black" />
  </a>
</p>

<p align="center">
  <code>do { compile(); } while (!kernel_panic && sanity > 0); // Segmentation fault (core dumped) 💀🖤</code>
</p>
```
