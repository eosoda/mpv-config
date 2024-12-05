# Personal mpv Configuration for Windows

## Overview

This repository contains my personal configuration files for [mpv](https://mpv.io/), a free, open-source, and cross-platform media player. The setup focuses on delivering a high-quality and practical viewing experience with:

- Tuned profiles for upscaling/downscaling, live-action, and anime.
- Custom key bindings for improved usability.
- A minimalist and customizable GUI.
- Scripts, shaders, and filters for various enhancements.

It’s suitable for both high-end and low-end systems with minor tweaks.

---

## Scripts and Shaders

Here is a curated list of the scripts and shaders included in this configuration:

| **Name**                                                                                          | **Description**                                                                                                                                                  |
|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [uosc](https://github.com/darsain/uosc)                                                          | Adds a minimalist but highly customizable GUI.                                                                                                                   |
| [evafast](https://github.com/po5/evafast)                                                        | Enables fast-forwarding and seeking on a single key.                                                                                                             |
| [thumbfast](https://github.com/po5/thumbfast)                                                    | Provides high-performance on-the-fly thumbnail generation.                                                                                                       |
| [memo](https://github.com/po5/memo)                                                              | Saves watch history and integrates it with uosc in a menu.                                                                                                       |
| [InputEvent](https://github.com/natural-harmonia-gropius/input-event)                            | Enhances input configurations with better, conflict-free, low-latency event mechanisms.                                                                           |
| [autoload](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua)                 | Automatically loads playlist entries from the current directory.                                                                                                 |
| [autodeint](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autodeint.lua)               | Automatically applies the appropriate deinterlacing filter based on the video content.                                                                            |
| [webtorrent-mpv-hook](https://github.com/mrxdst/webtorrent-mpv-hook)                             | Streams torrents via mpv and displays an on-screen overlay. Requires [setup](https://github.com/mrxdst/webtorrent-mpv-hook#install).                             |
| [Anime4K](https://github.com/bloc97/Anime4K)                                                     | Enhances anime playback with shaders for line sharpening and upscaling.                                                                                          |
| [FSRCNNX-TensorFlow](https://github.com/igv/FSRCNN-TensorFlow)                                   | Resource-intensive prescaler based on convolutional neural networks.                                                                                            |
| [SSimDownscaler, SSimSuperRes, KrigBilateral, Adaptive Sharpen](https://gist.github.com/igv)     | Collection of shaders for sharpening, downscaling, and high-quality chroma scaling.                                                                              |
| [AMD FidelityFX Super Resolution (FSR)](https://gist.github.com/agyild/82219c545228d70c5604f865ce0b0ce5) | Provides consistent spatial upscaling quality regardless of frame movement.                                                                                      |
| [SmartCopyPaste_II](https://github.com/Eisa01/mpv-scripts#smartcopypaste_ii) | Gives mpv the capability to copy and paste while being smart and customizable... movement.                                                                                      |

---

## Installation (Windows)

To set up this configuration on Windows, follow these steps:

1. **Download mpv**:  
   Obtain the latest 64-bit version of mpv from [mpv.io](https://mpv.io/installation/) and extract it to a directory of your choice.

2. **Run the Setup Script**:  
   Inside the extracted folder, open the `installer` directory and execute `mpv-install.bat` with Administrator privileges. This will configure mpv on your system.

3. **Add Configuration Files**:  
   Clone or download this repository, and copy the `portable_config` folder into the root directory of your mpv installation.

4. **Adjust Script Configurations**:  
   Update the paths in the `portable_config/script-opts/*.conf` files to reflect your setup and preferences.

5. **Fine-Tune mpv Settings**:  
   Open `mpv.conf` to customize options for your system. Use the [mpv manual](https://mpv.io/manual/master/) as a reference for understanding and modifying settings.

6. **Start Using mpv**:  
   Launch mpv and enjoy an optimized viewing experience!
---

## Key Bindings

You can customize or add key bindings in the `portable_config/input.conf` file. Refer to the [mpv manual](https://mpv.io/manual/master/) and the [uosc documentation](https://github.com/darsain/uosc#commands) for detailed guidance and additional options.

---

## Useful Links

- [mpv Wiki](https://github.com/mpv-player/mpv/wiki) - Comprehensive guide with scripts, shaders, FAQs, and more.
- [Awesome mpv](https://github.com/stax76/awesome-mpv) - A curated list of mpv tools, extensions, and enhancements.
- [mpv Manual](https://mpv.io/manual/master/) - Detailed configuration guide for mpv.
