# PK Minecraft Server Mods
**Proximity Voice Chat setup for PK Server**

PK Minecraft server has proximity voicechat. The server is playable with vanilla launcher but if you want to **use voicechat**, follow the steps below.<br>
*Takes 5 mins max.*

# <u>Windows instructions</u>
## Install Fabric
1. Download Fabric Installer: [Direct Link](https://maven.fabricmc.net/net/fabricmc/fabric-installer/1.1.0/fabric-installer-1.1.0.exe) [[Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/fabric-installer-1.1.0.exe)]
2. Run installer with these settings:
   - Minecraft Version: 1.21.10
   - Loader Version: 0.17.3
<img width="424" height="249" alt="image" src="https://github.com/user-attachments/assets/1bcac0db-b566-4e49-b181-915ca30ba863" />

## Install Simple Voice Chat mod
1. Download Voice Chat mod: [Direct Link](https://cdn.modrinth.com/data/9eGKb6K1/versions/BjR2lc4k/voicechat-fabric-1.21.10-2.6.6.jar) [[Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/voicechat-fabric-1.21.10-2.6.6.jar)]
2. Move the mod into your Minecraft mods folder:
   - Press Win + R
   - Type `%appdata%\.minecraft\mods`, and drag the downloaded file to the folder. (e.g. "C:\Users\<YourName>\AppData\Roaming\.minecraft\mods")
<img width="1550" height="794" alt="Screenshot 2025-11-05 185605" src="https://github.com/user-attachments/assets/9b711a12-5329-4f3b-8909-8de292872452" />

## Launch Minecraft 
Launch with **Fabric** profile, voicechat will work automatically when you join the server.

<img width="1276" height="745" alt="Screenshot 2025-11-05 190335 last" src="https://github.com/user-attachments/assets/53c1e92d-85e3-49cb-a820-92c5f5bed538" />

# <u>MacOS instructions</u>

## Launch Minecraft 
Launch with **Fabric** profile, voicechat will work automatically when you join the server.

## Install Fabric
1. Download Fabric: [Direct Link](https://maven.fabricmc.net/net/fabricmc/fabric-installer/1.1.0/fabric-installer-1.1.0.jar)
2. Run installer with these settings:
   - Minecraft Version: 1.21.10
   - Loader Version: 0.17.3
<img width="708" height="408" alt="image" src="https://github.com/user-attachments/assets/2ac31d0b-e577-4a2b-b930-9eae4d1608ee" />

## Install Simple Voice Chat mod and Fabric API
1. Download Voice Chat mod: [Direct Link](https://cdn.modrinth.com/data/9eGKb6K1/versions/BjR2lc4k/voicechat-fabric-1.21.10-2.6.6.jar) [[Alternative Download](https://github.com/ohnoltrane/PK-Minecraft-Server-Mods/blob/main/voicechat-fabric-1.21.10-2.6.6.jar)]
2. Download Fabric API: [Direct Link](https://cdn.modrinth.com/data/P7dR8mSH/versions/UuXf1NbU/fabric-api-0.138.0%2B1.21.10.jar)
3. Move both mods into your Minecraft mods folder:
   - Open Finder and press ⌘ + Shift + G
   - Type `~/Library/Application Support/minecraft/mods`, and drag the downloaded files to the folder. (e.g. "~/Library/Application Support/minecraft/mods/")
<img width="951" height="273" alt="image" src="https://github.com/user-attachments/assets/4afe56a8-ca25-4577-b5d8-3965c4c7cd5e" />

## Launch Minecraft 
<img width="1112" height="734" alt="Screenshot 2025-11-08 at 4 46 49 AM launch with" src="https://github.com/user-attachments/assets/1119a717-4fbd-4a47-ba68-bd03fc6d60c4" />
1. Launch with **Fabric** profile. When the game first tries to use your mic, macOS should ask permission.
   - If it doesn’t:
      - Go to System Preferences → Security & Privacy → Privacy → Microphone
      - Make sure Minecraft Launcher or Java has permission.
   - If neither appear in that list, open Terminal and run:
      - `tccutil reset Microphone`
   - Then relaunch Minecraft and trigger voice chat again — it should now prompt.

## Notes
- Client version must be latest. (Current: **Minecraft 1.21.10**)
- Device Java version must be at least **Java 17** and no higher than **Java 21**.
- Setup voicechat by pressing "v" on join
- Ensure “Simple Voice Chat” is enabled in the **Mods** menu
