# PK Minecraft Server Mods
**Proximity Voice Chat setup for PK Server**

PK Minecraft server has proximity voicechat.  
The server is playable with the vanilla launcher, but if you want to **use voicechat**, follow the steps below.  
*Takes 5 mins max.*

---

# Windows Instructions

## Install Fabric
1. Download Fabric Installer:  
   [Direct Link](https://maven.fabricmc.net/net/fabricmc/fabric-installer/1.1.0/fabric-installer-1.1.0.exe)  
   [Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/fabric-installer-1.1.0.exe)

2. Run the installer with these settings:
   - Minecraft Version: `1.21.10`
   - Loader Version: `0.17.3`

   ![Fabric Installer Screenshot](https://github.com/user-attachments/assets/1bcac0db-b566-4e49-b181-915ca30ba863)

## Install Simple Voice Chat Mod
1. Download Voice Chat mod:  
   [Direct Link](https://cdn.modrinth.com/data/9eGKb6K1/versions/BjR2lc4k/voicechat-fabric-1.21.10-2.6.6.jar)  
   [Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/voicechat-fabric-1.21.10-2.6.6.jar)

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

## Install Fabric
1. Download Fabric Installer:  
   [Direct Link](https://maven.fabricmc.net/net/fabricmc/fabric-installer/1.1.0/fabric-installer-1.1.0.jar)

2. Run installer with these settings:
   - Minecraft Version: `1.21.10`
   - Loader Version: `0.17.3`

   ![Fabric Installer Mac Screenshot](https://github.com/user-attachments/assets/2ac31d0b-e577-4a2b-b930-9eae4d1608ee)

## Install Simple Voice Chat Mod
1. Download Voice Chat mod:  
   [Direct Link](https://cdn.modrinth.com/data/9eGKb6K1/versions/BjR2lc4k/voicechat-fabric-1.21.10-2.6.6.jar)  
   [Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/voicechat-fabric-1.21.10-2.6.6.jar)

2. Download Fabric API:  
   [Direct Link](https://cdn.modrinth.com/data/P7dR8mSH/versions/UuXf1NbU/fabric-api-0.138.0%2B1.21.10.jar)

3. Move both mods into your Minecraft mods folder:
   - Open **Finder** → press `⌘ + Shift + G`
   - Type `~/Library/Application Support/minecraft/mods`
   - Drag both downloaded files into that folder.

   ![Mods Folder Mac Screenshot](https://github.com/user-attachments/assets/4afe56a8-ca25-4577-b5d8-3965c4c7cd5e)

## Install Prism Launcher
- Download Prism Launcher:  
  [Direct Link](https://github.com/PrismLauncher/PrismLauncher/releases/download/9.4/PrismLauncher-macOS-9.4.zip)
- Use this launcher to open Minecraft.  
  *(macOS should be on the latest version)*

## Launch Minecraft
![Prism Launcher Screenshot](https://github.com/user-attachments/assets/1119a717-4fbd-4a47-ba68-bd03fc6d60c4)

1. Launch with **Prism Launcher**.  
   When the game first tries to use your mic, macOS should ask permission.
2. If it doesn't:
   - Go to **System Preferences → Security & Privacy → Privacy → Microphone**
   - Make sure Prism Launcher or Java has permission.
   - If neither appear in that list, open **Terminal** and run:

     ```bash
     tccutil reset Microphone
     ```

   - Then relaunch Minecraft and try voice chat again.

---

## Notes
- Client version must be latest (**Minecraft 1.21.10**)
- Device Java version: **17 ≤ version ≤ 21**
- Setup voice chat by pressing **V** after joining
- Ensure **Simple Voice Chat** is enabled in the Mods menu
