The Great Ace Attorney - English Fan Translation Patch for Dai Gyakuten Saiban
============================

Please feel free to log typos and errors in the issues page.


We require Luma3DS 7.2 or above. You can check this version by holding SELECT when powering on the console. **Luma3DS will remove the region lock on your 3DS, so any region 3DS will be able to play this game!**

* If you do not have Luma3DS installed, follow this guide to install it: https://3ds.hacks.guide/get-started
* If you are on **Luma3DS 7.0.5 or lower**, follow these instructions: https://3ds.hacks.guide/a9lh-to-b9s
* If you are on **Luma3DS 7.1**, follow these instructions to update: https://3ds.hacks.guide/updating-b9s
* If you are on **Luma3DS 7.2** or above, you can proceed.


You must have either a physical DGS cartridge inserted or a digital DGS copy installed to your 3DS.

**It is very important that you follow this guide and do not experiment on your own if something goes wrong. Make sure you see the DGS logo on the top screen in Step 3.**
### **Warning: installing this firm to your FIRM partition will require you to follow the iderped guide at the bottom of this page.**
*This is **perfectly safe**. Ask on the FTI Discord (https://discord.gg/3nYQ9aG) in #dai-gyakuten-saiban if you need help or assistance.*

1. Download the latest release from this repository: https://github.com/ScarletStudy/DGS1-3DS-Release/releases/latest
2. Extract the release to the root of your 3DS SD Card. `DGS1-Patcher.firm` goes into `sd:/luma/payloads/`, `DGS1-PatchData-v2.X.X.bps` goes into `sd:/3DS/ScarletStudy/`.
3. Hold START while booting your 3DS and choose `DGS1-Patcher` from the menu. **Make sure you see the Great Ace Attorney logo on the top screen before you proceed - if you don't see it, start over or ask on Discord**, then press A to begin patching. If you don't see the Great Ace Attorney logo on the top screen, you probably booted into GodMode9 or a different payload by mistake. Turn off your 3DS and try again.
4. Patching will take about two minutes. After it is complete, press A again and your 3DS will restart.
5. Launch FBI and navigate to `SD:/3DS/ScarletStudy/DGS1-English-v2.X.X.cia`, then install it.

### **DO NOT INSTALL THE PATCHER TO YOUR FIRM PARTITION. IF YOU END UP IN GODMODE9 IN STEP 3, YOU DID SOMETHING WRONG!**

You may now run The Great Ace Attorney on your console, and will only need to repeat these steps to install a new update.

Unfortunately, the Banner can not be translated via a Game Update. The eManual is in English, however.

### **iderped Guide**
Although installing the patching firm is something you probably won't do on accident, it's not too hard to fix.
1. Download the latest SafeB9SInstaller from its repository: https://github.com/d0k3/SafeB9SInstaller/releases
2. Download the latest Boot9Strap from its repository: https://github.com/SciresM/boot9strap/releases/
3. Place the `SafeB9SInstaller.firm` on the root of your SD card (that's outside any folders) renamed to `iderped.firm`
4. Place the extracted contents of Boot9Strap's zip in `SD:/boot9strap`.
5. Turn your 3DS on and follow the on screen prompt to reinstall Boot9Strap.

Congratulations! Your 3DS will now load Luma from its boot.firm, just like it did before.
