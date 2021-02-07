# TF2-FPS-Config
Config for Team Fortress 2 that increases frames and decreases lag at the cost of graphical quality.

This config is made to help reduce lag and improve performance on TF2 for people like me with low-end pcs, hope this helps you too!

To install the config:
1. Download the autoexec.cfg on your pc
2. Place the config into your folder located at Team Fortress 2/tf/cfg/
3. Start up TF2

Launch options for even more fps (remove the brackets):
-high -novid -nojoy -full -nosteamcontroller -softparticlesdefaultoff -reuse -nohltv -nostartupsound -r_emulate_gl -particles 1 -precachefontchars -primarysound (windows only) -snoforceformat (also windows only) -freq 60 (change the value '60' to your monitor's refresh rate in hz rounded to the nearest whole number) -dxlevel 81(for more dxlevels, see details below. use this launch option only once then remove it to keep your in-game settings)

How to use the launch options:
1. Go to your Steam Library
2. Right-click on Team Fortress 2
3. Left-click Properties
4. Copy and paste the launch codes above
5. Leave the Properties
6. Boot up the game

Launch options explained for nerdy folk like me:
-high //sets the priority of the program to high so your pc puts more resources onto tf2 instead of other programs
-novid //disables the intro from playing when you start up the game to waste less time and subtly reduce load on your pc
-nojoy //disables joysticks to hasten startup time and reduce memory usage
-full //puts the game in fullscreen which reduces input lag and memory usage
-nosteamcontroller //disables the steam controller for faster startup and less memory usage
-softparticlesdefaultoff //disables scene depth blending for particles and sprites, gives more fps
-reuse //allows your game to reuse things when it's busy so it doesn't have to re-render
-nohltv //disables hltv for less resource usage
-no-browser //disables html motd browser; stops you from getting kicked for using 'cl_disablehtmlmotd 1', this will not disable the steam overlay browser
-nostartupsound //disables the sound on startup so your pc doesn't have to play the audio files
-r_emulate_gl //makes tf2 support opengl, still mainly runs using directx
-particles 1 //limits beam count to the minimum of 512
-precachefontchars //pre-caches font characters
-primarysound //windows and 2 speakers/headphones only, makes tf2 always use a direct hardware sound buffer format to reduce stuttering
-snoforceformat //windows only, no force setting hardware sound buffer format, fixes minor issues with -primarysound
-freq 60//sets your monitor's refresh rate in tf2 to 60hz
-dxlevel 81 //makes tf2 use a directx level of 8.1, which is more compatilble with slower pcs, to increase fps(at the cost of visual quality);
            //it's a more stable version of dxlevel 80(which gives slightly more fps than dxlevel 81 for older hardware but has lighting and texture issues 
            //fixed by dxlevel 81.)

Extra/Experimental Launch Options + Explaination:
-nouserclip //forces tf2 to use software clipping instead of hardware user clip planes, fps increase or decreases depending on individual hardware
-nosounds //disables sounds from the game, fps improvement only on literal potatos
-small //makes the game allow smaller resolutions than 640x480
-gl_enablesamplerobjects //linux and macOS only, enhances texture preloading using sampler objects
-gl_texclientstorage //makes tf2 use driver host copies for textures; reduces memory usage, but may cause texture display issues
-gl_amd_pinned_memory //linux only, uses amd pinned memory for efficient device memory handling; performance may worsen or improve depending on the individual hardware

//Supported TF2 DirectX Levels:
dxlevels under dxlevel 80 are not supported by tf2 any longer
dxlevel 98 is only for xbox
dxlevel 81 recommended for older hardware
dxlevel 80 is more unstable than dxlevel 81 but slight fps increase than dxlevel 81 on old hardware
dxlevel 90 is the default dxlevel set by tf2
dxlevel 95 is the recommended dxlevel for modern windows pc; use this instead of dxlevel 81 for more optimized rendering if you have a decent pc and also change 'mat_dxlevel 81' in the autoexec.cfg to 'mat_dxlevel 95'.

If you still want more fps, disable the steamwebhelper and the steam overlay:

To disable the Steam Overlay:
1. Head on to TF2 in your Steam Library
2. Right-click on TF2
3. Left-click Properties
4. Uncheck the box that says: "Enable Steam Overlay while in-game"
5. Launch the game

To disable Steamwebhelper:
You can find how to on the internet since i'm too lazy to write it down for u (it's 11:30pm at the time i'm writing this.)
