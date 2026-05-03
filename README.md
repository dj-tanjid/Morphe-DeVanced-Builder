<p align="center">
 <p align="center">⚠️⚠️⚠️</p>
 <p align="center"><b>Avoid downloading APKs or modules from untrusted websites, as they may be harmful and impersonate official Morphe/ReVanced/ReVanced Extended projects. Always download builds from official sources or trusted open-source builders like this one.</b></p>
</p>

<h1>Morphe x ReVanced Builder</h1>

[![GitHub License](https://img.shields.io/github/license/dj-tanjid/Morphe-ReVancedX-Builder?logo=github&label=License&link=https%3A%2F%2Fgithub.com%2Fdj-tanjid%2FMorphe-ReVancedX-Builder%2Fblob%2Fmain%2FLICENSE)](https://github.com/dj-tanjid/Morphe-ReVancedX-Builder/blob/main/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/dj-tanjid/Morphe-ReVancedX-Builder?label=Latest%20Release&logo=android)](../../releases/latest)

A fork of j-hc's [ReVanced Builder](https://github.com/j-hc/revanced-magisk-module) by **TanJid Creations**

This ReVanced/Morphe builder creates both APKs and [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) modules for [Morphe](https://github.com/MorpheApp), [ReVanced](https://github.com/ReVanced), [ReVanced Extended by Anddea](https://github.com/anddea/revanced-patches) and [Piko](https://github.com/crimera/piko) versions of **YouTube**, **YouTube Music**, **Google Photos**, **Reddit** & **Twitter**.

<details><summary><big><b>&nbsp;Features</b></big></summary>
<ul>
 <li> Supports all present and future ReVanced & Morphe apps (including projects implementing the same API)</li>
 <li> Can build root Modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimizes APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk/KSU app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
     <li> have custom banner</li>
    </ul>
</ul>
</details>

<h3 align="center">Note on YouTube Shorts Background Playback</h3>
<p align="center">
 If you want <b>YouTube Shorts Background Playback</b>, download the latest patched YouTube Morphe v21.11.486 from the <a href="../../releases">releases</a>. As currently this is the only version confirmed to work.<br><i>This version(v21.11.486) is regularly updated and patched whenever a stable Morphe patch becomes available.</i>
</p>

## Installation
### Non-root users
- Install [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) or [Morphe MicroG-RE](https://github.com/MorpheApp/MicroG-RE/releases/latest).
- Download the APK files you want to install from the [releases page](../../releases/latest).
- (Optional) Import one of my [**Custom Settings**](../teejay/custom_settings-by_tanjid) into your application. [*How to do this?*](../teejay/?tab=readme-ov-file#import-custom-settings-in-revancedmorphe-applications)
- Enjoy!

### Root users
- Download the ZIP files you want to flash from the [releases page](../../releases/latest).
- (Optional) Import one of my [**Custom Settings**](../teejay/custom_settings-by_tanjid) into your application. [*How to do this?*](../teejay/?tab=readme-ov-file#import-custom-settings-in-revancedmorphe-applications)
- (Optional) Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules.
- Enjoy!

## Import custom settings in ReVanced/Morphe applications
I personally like my YouTube and YouTube Music applications to be as close as possible to the original look, but less cluttered, easier, and less annoying to use. If you feel the same, I highly recommend importing [my custom settings files](../teejay/custom_settings-by_tanjid).

**To do this, go to YouTube Settings &rarr; ReVanced/ReVanced Extended/Morphe &rarr; Miscellaneous &rarr; Import&nbsp;/&nbsp;Export settings.**

## To include/exclude patches or patch other apps

 * Star the repo :eyes:
 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## If you are having trouble with the classic mount method of the modules
such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

## Credits
- [j-hc](https://github.com/j-hc) for creating this amazing builder.
- [Peter Noël Muller](https://github.com/peternmuller) for his work and inspirations.
- And of course, [Morphe](https://github.com/MorpheApp) team, [anddea](https://github.com/anddea), [ReVanced](https://github.com/ReVanced) team and [crimera](https://github.com/crimera) for their work on the ReVanced/Morphe apps!

## License
    Copyright (C) 2024-2026 Tanjidul Hossain

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.
