## Step 3: Using Resources
Now that you have everything, let's put it all together!
1. Fast64 -> Blender  
a. Edit -> Preferences -> Add-Ons -> Install...  
b. Navigate and Open your Fast64 ZIP file.  
c. Enable the Add-On  
2. Magic UV -> Blender  
a. Search in ADD-Ons `UV`  
b. Select `Magic UV`  
b. Read the next point  
3. Blender -> HackerSM64  
a. On the right, click the arrow, if it's there  
b. Click `SM64` -> `SM64 File Settings`  
c. Click the folder icon to the left of the `Deco...` Selection  
d. Navigate to and open your HackerSM64 folder.  
e. Change `Compression ...` to `YAY0`  
f. Open an Ubuntu terminal (Step 1, in blockquote) and navigate to the HackerSM64 folder  
g. Type: `sudo apt update`, type you password, `sudo apt install build-essentials gcc-mips-linux-gnu`  
h. Back in Blender, make sure you're in object mode, and, on the right, select `myLevel` under `Collection`  
i. Open Tab `SM64 Level Exporter` in `SM64` on the right and click `Export Level`  
> Note: If the command says `execvp: tools/<program>: Permission denied`, type `chmod +x tools/<program>` and rerun `sudo make`. Keep doing this until the build succeeds.  
