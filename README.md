# doom3 widescreen fix
**NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.**

**Create an autoexec.cfg file and drop it into your base doom3 directory in Steam client.**
```
seta r_renderer "best"
seta com_videoRam "1024"
seta com_machineSpec "3"
seta r_shadows "1"
seta r_skipBump "0"
seta r_skipSpecular "0"
seta r_skipNewAmbient "0"
seta image_anisotropy "8"
seta image_filter "GL_LINEAR_MIPMAP_LINEAR"
seta image_ignoreHighQuality "0"
seta image_roundDown "1"
seta image_preload "1"
seta image_forceDownSize "0"
seta image_downSize "0"
seta image_downSizeBump "0"
seta image_downSizeSpecular "0"
seta image_useCache "0"
seta image_usePrecompressedTextures "0"
seta image_useNormalCompression "0"
seta image_useCompression "0"
seta image_useAllFormats "1"
seta g_showBrass "1"
seta g_decals "1"
seta g_doubleVision "1"
seta g_bloodEffects "1"
seta g_projectileLights "1"
seta g_muzzleFlash "1"
seta r_customHeight "1080"
seta r_customWidth "1920"
seta r_fullscreen "1"
seta r_mode "-1"
seta r_aspectratio "1"
seta r_displayRefresh "60"
seta r_multisamples "0"
vid_restart
```

**Windows path:**
* ``C:\Program Files (x86)\Steam\steamapps\common\Doom 3\base``

**Linux path:**

* ``/home/user/.steam//steamapps/common/Doom 3/base``

*NB! Recommended Proton versions 5.13 and 6.8 (they don't give black textures as experimental does)*

**Explanation of settings**

**Your monitor resolution, it can be 2k/4k adjust accordingly 2k is 2560x1440 and 4k is 3840x2160::**
* ``seta r_customHeight "1080"``
* ``seta r_customWidth "1920"``

**Fullscreen On:**

* ``seta r_fullscreen "1"``

**FOV**

* ``seta r_mode "-1"``

**Aspect Ratio for 4:3 it will be 0,for 16:9 it will be 1,for 16:10 it will be 2**

* ``seta r_aspectratio "1"``

**Your display refresh v-sync rate current 60,you can set according to your monitor refresh rate 144.160,180,244,etc,just make sure you enabled it in display configuration.**

* ``seta r_displayRefresh "60"``

**Antialiasing from 0 to 4 to 8,depends on how you like it**

* ``seta r_multisamples "0"``
* ``vid_restart``

**My YT channel:**
https://www.youtube.com/@silentgameplays

**Enjoy  silentgameplays!**

