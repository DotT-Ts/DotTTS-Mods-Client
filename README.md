# DotTTs-SMP Minecraft Client Setup Guide
---
## Important Notes

- The server **expects all provided mods to be installed on the client**.
- If mods are missing or incorrect, the server **may reject your connection**.
- For any issues, please contact us through the provided communication channels.

## Requirements

- **Java 17+ is required**  
  - **[Java 21](https://www.oracle.com/uk/java/technologies/downloads/#jdk21-windows) is recommended** for better performance.
- **[Minecraft Forge 1.20.1 (version 47.4.1)](https://maven.minecraftforge.net/net/minecraftforge/forge/1.20.1-47.4.1/forge-1.20.1-47.4.1-installer.jar)**

## Recommendation
- We recommend to use a [method 2 via a Multi-Launcher](https://github.com/DotT-Ts/DotTTS-Mods-Client/tree/main#using-a-multi-launcher-example-with-prism-launcher) for ease of use.
---
## Getting Started with the Vanilla Minecraft Launcher
1. **Install Forge 1.20.1 (47.4.1)** 

![file8](/Assets/file8.png)
   
Download the [Forge installer JAR](https://maven.minecraftforge.net/net/minecraftforge/forge/1.20.1-47.4.1/forge-1.20.1-47.4.1-installer.jar) and run it. Select **"Install Client"** and complete the installation. Once you see the success message, you can close the installer.

![file9](/Assets/file9.png)

2. **Launch the Minecraft Launcher**

![file10](/Assets/file10.png)

   - Go to **Minecraft: Java Edition > Installations**
   - Locate `forge-1.20.1-forge-47.4.1`
   - Hover over it and click the **folder icon** to open the installation directory (`.minecraft`)
 
![file11](/Assets/file11.png)

3. **Install Mods**

![file12](/Assets/file12.png)

   - Open the `mods` folder inside `.minecraft`
   - Move any unrelated mods into a subfolder to avoid conflicts
   - Copy the provided `.jar` mod files into the `mods` folder

   > Tip: We recommend using a multi-launcher like [Prism Launcher](https://prismlauncher.org/) to keep your instances clean and separated. Furthermore if you have existing mods in the folder already, it is recommended to move them to a folder inside the mods folder as this will disable them and reduce any potential issues as seen in the example.

4. **Install Shader Packs (Optional)**

![file13](/Assets/file13.png)

   - In your `.minecraft` folder, open the `shaderpacks` directory
   - Drop your preferred `.zip` shader pack there
   - Enable shaders in-game from the video settings

5. **Launch Your Client**
   - Your client is now ready to connect to the server
   
    > NOTE: When you launch the instance you will get popup overlay, mentioning that the version of the game is a modified client and may not have the latest player safety features, you may omit this popup as its just a warning that the client is not officialy made by Microsoft/Mojang.

---

## Using a Multi-Launcher (Example with [Prism Launcher](https://prismlauncher.org/))

> NOTE: You will have to login with a Microsoft account that has a Minecraft: Java Edition Account, and allow the multi-launcher to communicate with Microsoft, if you do not trust the multi-launcher or are using an unknown launcher then we recommend you to use the Vanilla Minecraft Launcher instead.

1. **Create a New Instance**

![file1](/Assets/file1.png)

   - Name it appropriately, e.g., `DotTTs-SMP`
   - Choose **version 1.20.1**
   - Select **Forge** as the mod loader with version `47.4.1`

![file2](/Assets/file2.png)

2. **Add Mods**

![file3](/Assets/file3.png)

   - Open the new instance and click **Edit**
   - Navigate to the **Mods** tab and click **View Folder**

![file4](/Assets/file4.png)

   - Place all provided `.jar` files into this folder  

![file5](/Assets/file5.png)
     
> Make sure only valid `.jar` mod files are present (Thus ignore the placeholder file in the example, as there should not be anything else apart from `.jar` files)



3. **Add Shader Packs (Optional)**

![file6](/Assets/file6.png)

   - Navigate to the `shaderpacks` folder within the instance directory
   - Drop in your shader `.zip` files


4. **Launch Your Client**
   - Your client is now ready to connect to the server

![file7](/Assets/file7.png)

---

(Written by Bluebookltd)
