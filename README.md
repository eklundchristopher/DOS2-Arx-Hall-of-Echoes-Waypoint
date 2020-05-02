**A Divinity Original Sin 2 Definitive Edition Mod**

# Hall of Echoes Waypoint (Arx)
Under certain circumstances upon entering Arx, you will no longer have access to the Lady Vengeance in the Hall of Echoes. This mod aims to solve that by adding another waypoint statue in the starting area of Arx. Once you've discovered the waypoint, you'll be able to reach the Hall of Echoes and do whatever you must do there. The forced waypoint will also disappear as soon as you discover the original waypoint onboard Lady Vengeance (you may re-discover it by approaching the statue yet again).


## Download
+ [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2080785118)
+ [GitHub Releases](https://github.com/eklundchristopher/DOS2-Arx-Hall-of-Echoes-Waypoint/releases)


## Building
```bash
git clone https://github.com/eklundchristopher/DOS2-Arx-Hall-of-Echoes-Waypoint.git

git checkout definitive-edition

# Change "STEAMINSTALLATION" to your actual Steam installation path

cp -R Data/Projects/HallOfEchoesTeleporter \
    STEAMINSTALLATION/steamapps/common/Divinity Original Sin 2/DefEd/Data/Projects/HallOfEchoesTeleporter

cp -R Data/Mods/HallOfEchoesTeleporter_dbe70215-f476-452a-8aee-1575ce76d56f \
    STEAMINSTALLATION/steamapps/common/Divinity Original Sin 2/DefEd/Data/Mods/HallOfEchoesTeleporter_dbe70215-f476-452a-8aee-1575ce76d56f
```

Now launch **The Divinity Engine 2** from Steam, when prompted for the version of the engine, select the **Definitive Edition**.

From the project manager, select the **HallsOfEchoesTeleporter** project. When the project has loaded, you want to open the `Story Editor` tool from the toolbar.

Within the `Story Editor`, hit `File > Generate Definitions, Build and Reload` to build the mod.

