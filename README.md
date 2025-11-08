# PK Minecraft Server Mods
**Proximity Voice Chat setup for PK Server**

PK Minecraft server has proximity voicechat.  
The server is playable with the vanilla launcher, but if you want to **use voicechat**, follow the steps below.  
*Takes 5 mins max.*

[Windows Instructions](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/README.md#windows-instructions)  
[macOS Instructions](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/README.md#macos-instructions)

---

# Windows Instructions

## Install Fabric
1. Download Fabric Installer: [Direct Link](https://maven.fabricmc.net/net/fabricmc/fabric-installer/1.1.0/fabric-installer-1.1.0.exe)  [[Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/fabric-installer-1.1.0.exe)]

2. Run the installer with these settings:
   - Minecraft Version: `1.21.10`
   - Loader Version: `0.17.3`

   ![Fabric Installer Screenshot](https://github.com/user-attachments/assets/1bcac0db-b566-4e49-b181-915ca30ba863)

## Install Simple Voice Chat Mod
1. Download Voice Chat mod: [Direct Link](https://cdn.modrinth.com/data/9eGKb6K1/versions/BjR2lc4k/voicechat-fabric-1.21.10-2.6.6.jar) [[Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/voicechat-fabric-1.21.10-2.6.6.jar)]

2. Move the mod into your Minecraft mods folder:
   - Press **Win + R**
   - Type `%appdata%\.minecraft\mods`
   - Drag the downloaded file to that folder (e.g. `C:\Users\<YourName>\AppData\Roaming\.minecraft\mods`)

   ![Mods Folder Screenshot](https://github.com/user-attachments/assets/9b711a12-5329-4f3b-8909-8de292872452)

## Launch Minecraft
Launch with the **Fabric** profile — voice chat will work automatically when you join the server.

![Launch Screenshot](https://github.com/user-attachments/assets/53c1e92d-85e3-49cb-a820-92c5f5bed538)

---

# macOS Instructions

## Install Prism Launcher
Download Prism Launcher: [Direct Link](https://github.com/PrismLauncher/PrismLauncher/releases/download/9.4/PrismLauncher-macOS-9.4.zip)  
*(macOS version should be minimum Monterey (12.7.6))*

## Add new Minecraft instance (w/ Fabric)
1. Press add instance  
<p align="left"><img src="https://github.com/user-attachments/assets/2b349b30-d17e-47a1-96df-d49e21c2de0f" width="700"></p>
2. Add Fabric and press "OK"  
<p align="left"><img src="https://github.com/user-attachments/assets/f2ea1343-9ff0-4e08-bd85-2b4b50e4f225" width="700"></p>

## Add Simple Voice Chat Mod & Fabric API
1. Press Edit  
<p align="left"><img src="https://github.com/user-attachments/assets/a08b385c-cb61-437e-a884-63ce51728a88" width="700"></p>

2. In the Mods tab, press "Download mods"  
<p align="left"><img src="https://github.com/user-attachments/assets/befee863-efe8-4e1c-b20f-54ee4424f0c3" width="700"></p>

3. Search for **Simple Voice Chat** and **Fabric API**, selecting each mod for download.  
<p align="left"><img src="https://github.com/user-attachments/assets/9bae7ffe-c19b-46fa-98dd-13acb1cc39e5" width="700"></p>

4. Confirm mods selection  
<p align="left"><img src="https://github.com/user-attachments/assets/7920d30c-b950-4040-84e5-5b1a09d8c554" width="700"></p>

## Launch Minecraft
1. Launch with **Prism Launcher**.  
<p align="left"><img src="https://github.com/user-attachments/assets/b3612ca2-a7b2-48b6-b25a-59b974ab4815" width="700"></p>

   When the game first tries to use your mic, macOS should ask permission.  

<p align="left"><img src="https://github.com/user-attachments/assets/2aea4be3-3dc9-4252-b011-255e6d7410ca" width="700"></p>

3. If it doesn't:
   - Go to **System Preferences → Security & Privacy → Privacy → Microphone**
   - Make sure Prism Launcher or Java has permission.
   - If neither appear in that list, open **Terminal** and run:
     ```bash
     tccutil reset Microphone
     ```
   - Then relaunch Prism Launcher and try a Minecraft server again.

---

## Notes
- Client version must be latest (**Minecraft 1.21.10**)
- Device Java version: **17 ≤ version ≤ 21**
- Setup voice chat by pressing **V** after joining
- Ensure **Simple Voice Chat** is enabled in the Mods menu
