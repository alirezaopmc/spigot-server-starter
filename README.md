# spigot-server-starter
Spigot Sever Starter Project


## Setup Server
1. Download the latest release from [here]() and extract the zip file into a new folder.
2. Get spigot jar file from [here](https://getbukkit.org/)(for begginers) or download it using [BuildTools](https://www.spigotmc.org/wiki/buildtools/)(if you are familiar with terminal commands you have pasion)
2. Put the jar file in the the folder containing the extracted files.
3. Edit the `run.bat` file according to the downloaded jar file.
```bash
@echo off
title Server Console
java -Xmx1G -jar <jar-file-name>.jar
PAUSE
```
Note that if you are using Spigot 1.18.1, you don't need to edit this file.

3. Open a terminal and run the `run.bat` from there.
4. After server stoped open and edit the created file `eula.txt`, set it to `true`.
5. Do the 3rd step step and wait for the server to be runned.
6. Connect to the ip: `localhost` in minecraft game.

Optional:

7. Open the `bukkit.yml` and set `allow-end=false`. It makes fast in the startup and runtime. [More optimization?](https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/)


Other tutorials:
* https://www.spigotmc.org/wiki/spigot-installation/
* https://www.youtube.com/watch?v=lNp4I-600wo
* https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_Spigot_server


## Setup Development Environment
Coming soon...
