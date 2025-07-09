# **3DS Account Switcher**
**A tool for switching your Link3DS account on a 3DS console.** 🔄🎮

## Installation 🛠️
1. Download the latest release of `3ds_account_switcher.rar`.
2. Extract and place the `luma` and `3ds` folders on your SD card. 💾
3. Insert the SD card into your console. 🔌
4. Boot up your console and launch the Homebrew Launcher. 🚀
5. Open the Link3DS Switcher app and select your network. 🌐

## Building 🏗️

1. **Install devkitPro with 3DS includes:**
   ```bash
   pacman -S 3ds-dev
   ```
2. **Open a command prompt in the project folder and run:** 
   ```bash
   make
   ```  
   to compile the project. ⚙️
3. **Go to the `patchs` folder and run:**  
   ```bash
   make
   ```  
   to compile the patches. 🔧

## Credits 🙏
- **Zaksabeast** for the friends & account patches. 👾
- **SciresM** for the SSL patches. 🔒
