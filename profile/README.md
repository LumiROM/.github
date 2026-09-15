<div align="center">

# LumiROM Ecosystem

<img src="https://raw.githubusercontent.com/Luminous418/LumiROM/OneUI8.5/LumiROM/logo/LumiROM.png" alt="LumiROM Logo" width="400"/>

### One UI & Galaxy AI for Samsung MediaTek devices

![License](https://img.shields.io/badge/License-MIT-00ff88?style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/Luminous418?style=for-the-badge&logo=github&label=Followers)
![GitHub stars](https://img.shields.io/github/stars/Luminous418/LumiROM?style=for-the-badge&logo=github)

<br>

**LumiROM** takes official Samsung firmware and reconstructs it from scratch — applying heavy optimizations,
Galaxy AI features, Knox patches, and EROFS compression — to give low-end MediaTek devices a completely new life.

</div>

---

## Projects

<table>
  <tr>
    <td colspan="2" align="center">
      <h3>LumiROM</h3>
      <p><b>The core.</b> Custom ROM that downloads Samsung firmware, applies Galaxy AI, debloat, Knox patches, performance tweaks and EROFS packaging — via GitHub Actions or local build.</p>
      <p><sub>One UI 8.5 &bull; 6 devices &bull; 150+ apps removed &bull; Galaxy AI ✨</sub></p>
      <a href="https://github.com/Luminous418/LumiROM">
        <img src="https://img.shields.io/badge/LumiROM-Custom_ROM-7C3AED?style=for-the-badge&logo=android&logoColor=white" alt="LumiROM">
      </a>
      <a href="https://github.com/Luminous418/LumiROM/actions">
        <img src="https://img.shields.io/github/actions/workflow/status/Luminous418/LumiROM/OneUi8-5.yml?branch=OneUI8.5&style=for-the-badge&logo=github&label=Build" alt="CI Status">
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <h3>Cloudy</h3>
      <p><b>OTA client for LumiROM.</b> Checks for updates, downloads the ROM, verifies SHA-256, and triggers installation in recovery — all from the phone. Self-updates too.</p>
      <p><sub>Android app &bull; Kotlin &bull; Privileged system app</sub></p>
      <a href="https://github.com/Luminous418/cloudy">
        <img src="https://img.shields.io/badge/Cloudy-OTA_Updater-2563EB?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Cloudy">
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <h3>LumiROM Page</h3>
      <p><b>Official documentation site.</b> Sphinx-powered docs covering supported devices, features, build methods and changelogs.</p>
      <p><sub>HTML &bull; Sphinx &bull; Hosted on GitHub Pages</sub></p>
      <a href="https://github.com/Luminous418/LumiROM_page">
        <img src="https://img.shields.io/badge/LumiROM_Page-Docs-DB2777?style=for-the-badge&logo=sphinx&logoColor=white" alt="LumiROM Page">
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <h3>A32 Useful Things</h3>
      <p><b>Galaxy A32 dev resources.</b> Community-driven collection of custom recoveries (TWRP, OFOX, SHRP, PBRP), ADB/Fastboot installers, Odin, drivers and technical docs for the A325 series.</p>
      <p><sub>Galaxy A32 &bull; A325F / A325M &bull; MediaTek Helio G80</sub></p>
      <a href="https://github.com/Luminous418/a32-useful-things">
        <img src="https://img.shields.io/badge/a32_useful_things-Dev_Resources-0EA5E9?style=for-the-badge&logo=github&logoColor=white" alt="A32 Useful Things">
      </a>
    </td>
  </tr>
</table>

---

<div align="center">

## Supported Devices

| Device | Model | Fingerprint | Base |
| :--- | :---: | :---: | :---: |
| Galaxy A22 | SM-A225F | Side-FP | A24 (SM-A245F) |
| Galaxy A22 5G | SM-A226B | Side-FP | A24 (SM-A245F) |
| Galaxy A32 | SM-A325F | FOD | A34 (SM-A346B) |
| Galaxy A32 | SM-A325M | FOD | A34 (SM-A346B) |
| Galaxy F22 | SM-E225F | Side-FP | A24 (SM-A245F) |
| Galaxy M32 | SM-M325F | FOD | A34 (SM-A346B) |
</div>

---

## Highlights

<table>
  <tr>
    <td width="50%"><h4>Galaxy AI ✨</h4><p>Call Assist · Writing Assist · Note Assist · Transcript Assist · Browsing Assist · Photo Assist · Weather Wallpaper · Now Brief</p></td>
    <td width="50%"><h4>Knox Patches (no root)</h4><p>Secure Folder · Samsung Health · Samsung Flow · SmartThings · Auto Blocker · Secure Wi-Fi · Private Share · Samsung Cloud</p></td>
  </tr>
  <tr>
    <td width="50%"><h4>System Optimization</h4><p>150+ apps removed · Deodexed · EROFS · VoLTE fix · CPU/GPU tuning · FBE/FDE disabled · SELinux fixes · Init tweaks</p></td>
    <td width="50%"><h4>Build Pipeline</h4><p>GitHub Actions (cloud) or local build · Firmware cache · Auto-detect One UI version · HuggingFace / GoFile upload · EROFS output</p></td>
  </tr>
</table>

---

## Quick Start

**Just want the ROM?**
Get the latest flashable ZIP from the [Telegram channel](https://t.me/LumiROMs) and flash via Cloudy, recovery or ADB sideload.

**Want to build it yourself?**

```bash
# Local build
git clone https://github.com/Luminous418/LumiROM.git
cd LumiROM
bash build_local.sh -s SM-A325F -c DBT -i 353117555323497
```

Or fork the repo and run the **LumiROM Tools** workflow from the Actions tab.

---

## Community

[![Telegram](https://img.shields.io/badge/Telegram-LumiROMs-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/LumiROMs)
[![GitHub Issues](https://img.shields.io/badge/GitHub-Issues-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Luminous418/LumiROM/issues)
[![Documentation](https://img.shields.io/badge/Docs-Official_Site-DB2777?style=for-the-badge&logo=readthedocs&logoColor=white)](https://luminous418.github.io/LumiROM_page/)

---

<div align="center">

Made with passion by [Luminous418](https://github.com/Luminous418)

</div>
