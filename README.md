<h1 align="center">UO Landscaper Mod</h3>

<div align="center">
    
  [![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()
  [![GitHub Issues](https://img.shields.io/github/issues/norad32/uo-landscaper-mod.svg)](https://github.com/norad32/uo-landscaper-mod/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/norad32/uo-landscaper-mod.svg)](https://github.com/norad32/uo-landscaper-mod/pulls)
  [![License](https://img.shields.io/github/license/norad32/uo-landscaper-mod.svg)](https://github.com/norad32/uo-landscaper-mod?tab=MIT-1-ov-file)
  
</div>

---

<p align="center"> A mod for UO Landscaper that aims to provide complete transition tables for modern Ultima Online maps.
    <br> 
</p>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About ](#about-)
- [Getting Started ](#getting-started-)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [Usage ](#usage-)
- [Authors ](#authors-)
- [Acknowledgements ](#acknowledgements-)

## About <a name = "about"></a>

The **UO Landscaper Mod** aims to enhance the Ultima Online mapping tool, UO Landscaper, by offering a complete and reliable collection of transition tables for all map tiles in the classic [Ultima Online](https://uo.com) (Time of Legends) client.

While this mod arrives fashionably about two decades too late, it serves as a testament to the lasting legacy of Ultima Online and its active Free Shard community.

**Note:** This repository includes only the data XML files used by UO Landscaper. It does not contain the source code or binaries of the UO Landscaper tool itself.

## Getting Started <a name = "getting_started"></a>

Follow these instructions to set up UO Landscaper Mod on your local machine.

### Prerequisites

Ensure you have the following installed on your system:

- **UO Landscaper**: The tool that this mod extends. You can still get it from [Ultima Online World](https://uo.wzk.cz/uolandscaper/) or the [ServUO Community](https://www.servuo.com/archive/uo-landscaper-v1-4-x.380/).
- **Git**: For version control and collaboration. [Download Git](https://git-scm.com/downloads).

For editing and collaboration, you may also need:

- **XML Editor**: Such as [Visual Studio Code](https://code.visualstudio.com/) or [Notepad++](https://notepad-plus-plus.org/).
- **UOFiddler**: To inspect the tile set and map. [Download UOFiddler](https://github.com/polserver/UOFiddler).
- **Ultima Online**: The Ultima Online client. [Download Ultima Online](https://uo.com/client-download/)

### Installing

Follow these steps to set up UO Landscaper Mod:

1. Install UO Landscaper
   If you haven't already, download and install UO Landscaper from one of the provided sources.
2. Remove System, Transition and Statics folder
   Open Command Prompt and execute the following commands to remove the `System`, `Transition`, and `Statics` folders:

```bash
cd "C:\Path\To\UO_Landscaper"
rd rmdir /s /q "Data\System" && rd /s /q "Data\Transition" && rd /s /q "Data\Statics"
```

3. Clone repo
   Clone the UO Landscaper Mod repository to your local machine:

```bash
git clone https://github.com/norad32/uo-landscaper-mod.git
```

This will create a uo-landscaper-mod folder with all the necessary data files.

4. Integrate the Mod
   Copy the data files from the cloned repository into the UO Landscaper's data directory:

```bash
xcopy /E /I "uo-landscaper-mod\Data" "C:\Path\To\UO_Landscaper\Data"
```

_Ensure you replace C:\Path\To\UO_Landscaper with your actual installation path._

## Usage <a name="usage"></a>

You can use UO Landscaper with the mod as usual.

For detailled instructions, refer to the [Wiki](https://github.com/norad32/uo-landscaper-mod/wiki)

## Authors <a name = "authors"></a>

- [@norad32](https://github.com/norad32)

## Acknowledgements <a name = "acknowledgement"></a>

- **Dknight** and **Admin Khaybel** of [OrBSydia](https://orbsydia.com/) for creating UO Landscaper.
- **Darus** for creating the best BMP2MAP conversion tool worldwide.
- **Richard Garriott**, **Starr Long**, **Raph Koster**, **Rick Delashmit**, **Scott Phillips**, **Kirk Winterrowd**, **Joe Basquez** and **Hal Milton** for creating Worlds.
- The **Ultima Online Free Shard Community** for their continuous support and inspiration.
