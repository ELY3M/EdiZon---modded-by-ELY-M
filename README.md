# EdiZon - Mooded by ELY M.
  <p align="center"> <a href="https://github.com/ELY3M/EdiZon---modded-by-ELY-M/releases/latest"><img src="https://raw.githubusercontent.com/ELY3M/EdiZon---Modded-by-ELY-M/master/icon.jpg"><br />Latest Release</a>

  </p>

A Homebrew save file dumper, injector and on-console editor for Horizon, the OS of the Nintendo Switch.

# Overview
  EdiZon consists of 3 different main functionalities.
  - **Save file management**
    - Extraction of game saves.
    - Injection of extracted game saves (Your own and your friends save files).
    - Uploading of savefiles directly to https://anonfile.com.
    - Batch extraction of all save files of all games on the system.
  - **Save file editing**
    - Easy to use, scriptable and easily expandable on-console save editing.
      - Lua and Python script support.
    - Built-in save editor updater.
  - **On-the-fly memory editing**
    - Cheat Engine like RAM editing.
    - Freezing of values in RAM via Atmosphère's cheat module.
    - Interface for loading, managing and updating Atmosphère cheats.

  All packed into one easy to use and easy to install Homebrew.

# Images
  <p align="center"><img src="https://raw.githubusercontent.com/ELY3M/EdiZon---modded-by-ELY-M/master/assets/main_menu.jpg"></p>
  <p align="center"><img src="https://raw.githubusercontent.com/ELY3M/EdiZon---modded-by-ELY-M/master/assets/save_editor_1.jpg"></p>
  <p align="center"><img src="https://raw.githubusercontent.com/ELY3M/EdiZon---modded-by-ELY-M/master/assets/save_editor_2.jpg"></p>
  <p align="center"><img src="https://raw.githubusercontent.com/ELY3M/EdiZon---modded-by-ELY-M/master/assets/ram_editor.jpg"></p>

# Save editor Config and Script files

  To download working Editor Config and Editor Script files, visit [this repository](https://github.com/WerWolv/EdiZon_ConfigsAndScripts/tree/master)

  Check out our [Wiki page](https://github.com/WerWolv/EdiZon/wiki) for more information on how to build your own Editor Config and Editor Script files.

# How to install

  1. Download the latest release from the [GitHub release page](https://github.com/ELY3M/EdiZon---modded-by-ELY-M/releases/latest).
  2. Unpack the downloaded zip file, put the files on your Nintendo Switch's SD card and let the folders merge.
  3. Use a free open source CFW like [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere) to launch the hbmenu and start EdiZon from there.
     1. If you want to use the cheat manager you absolutely have to use [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere) as only their cheats are supported.
	 2. grab cheats from [switchcheatsdb.com](https://switchcheatsdb.com) - you need to rename the first folder in the cheat zip to atmosphere.  if you are using atmosphere 0.10.0 or above, you need to rename titles to contents inside the first folder.   	 

# How to compile

  1. Clone the EdiZon repo to your computer using `git clone https://github.com/ELY3M/EdiZon---modded-by-ELY-M`.
  2. Download and install devkitA64. It comes bundled with the [devkitPro](https://devkitpro.org) toolchain.
  3. Use the pacman package manager that comes with devkitPro to download and install libNX, portlibs (`switch-portlibs`) and freetype2 (`switch-freetype`).
  4. The rest of the compilation works using the `make` command.

# Discord

  For support with the usage of EdiZon or the creation of save editor configs and scripts, feel free to join the EdiZon server on Discord: https://discord.gg/qyA38T8

# Credits

  Thanks to...

  - [devkitPro](https://devkitpro.org) for their amazing toolchain!
  - [3096](https://github.com/3096) for [save dumping/injecting](https://github.com/3096/nut)
  - [Bernardo Giordano](https://github.com/BernardoGiordano) for some code from [Checkpoint](https://github.com/BernardoGiordano/Checkpoint).
  - [SwitchBrew](https://switchbrew.org/) for the [Homebrew Launcher](https://github.com/switchbrew/nx-hbmenu) GUI and shared font code.
  - [thomasnet-mc](https://github.com/thomasnet-mc/) for most of the save backup and restore code and the updater script.
  - [trueicecold](https://github.com/trueicecold) for batch backups and the editable-only mode.
  - [onepiecefreak](https://github.com/onepiecefreak3) for the edizon debugger and LOTS of reviewing implementations.
  - [Jojo](https://github.com/drdrjojo) for the Travis CI configuration and the config creator.
  - [Ac_K](https://github.com/AcK77) for help with the server side update scripts and the EdiZon save website.
  - [jakibaki](https://github.com/jakibaki) for his massive help with the implementation of RAM editing and sys-netcheat which was used as inspiration.
  - [SciresM](https://github.com/SciresM) for the aarch64 hardware accelerated SHA256 code, his implementation of the Atmosphère cheat engine and his support during development.
  - **kardch** for the beautiful current icon.
  - **bernv3** for the beautiful old icon.
  - **All config creators** for bringing this project to life!

  <br>

  - [nlohmann](https://github.com/nlohmann) for his great json library.
  - [Martin J. Fiedler](https://svn.emphy.de/nanojpeg/trunk/nanojpeg/nanojpeg.c) for the nanojpeg JPEG decoding library.
  - [Lua](https://www.lua.org/) for their scripting language.
  - [Python](https://www.python.org/) and [nx-python](https://github.com/nx-python) for their scripting language respectively their python port to the switch.


  <br>
  <p align="center"><img src="https://www.lua.org/images/logo.gif">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg"><p>
