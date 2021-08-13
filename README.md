# TF2 FPS Config + Launch Options

This is a place for that was made to increase performance and decrease lag for Team Fortress 2, so unlike many other configs; every single command and launch option works!

# To install the config:
  1) Copy all of the commands from the autoexec.cfg file
  2) Paste them in your own autoexec.cfg file
  2) Start up TF2


# Launch options to get more out of the config:

-novid -noff -nojoy -nosteamcontroller -softparticlesdefaultoff -reuse -nohltv -no-browser -nostartupsound -precachefontchars -dxlevel 81 -noquicktime


# How to use the launch options:
  1) Go to your Steam Library
  2) Right-click on Team Fortress 2
  3) Left-click Properties
  4) Copy and paste the launch options above into the Launch Options bar
  5) Boot up the game


# Launch options explained:

  -novid : disables the intro from playing when you start up the game to waste less time and subtly reduce load on your pc

  -nojoy : disables joysticks to hasten startup time and reduce memory usage

  -nosteamcontroller : disables the steam controller for faster startup and less memory usage

  -softparticlesdefaultoff : disables scene depth blending for particles and sprites, gives you more fps

  -reuse : allows your game to reuse things when it's busy so it doesn't have to re-render

  -nohltv : disables hltv for less resource usage

  -no-browser : disables html motd browser; stops you from getting kicked for using 'cl_disablehtmlmotd 1', this will not disable the steam overlay browser

  -nostartupsound : disables the sound on startup so your pc doesn't have to play the audio files, slightly reduces memory usage and speeds up startup

  -precachefontchars : pre-caches font characters

  -freq x : sets your "in-game monitor" 's refresh rate to value x (replace x with your monitor's refresh rate

  -dxlevel 81 : makes TF2 use directX level 8.1 (this launch option resets your settings every time you launch with it but it saves your set directX level, so you only need to launch it once.)


# Extra/Experimental Launch Options + Explaination:

  -r_emulate_gl : makes TF2 support opengl; fps increase/decrease depending on hardware

  -primarysound : windows and 2 speakers/ 1 headphone only, makes tf2 always use a direct hardware sound buffer format to reduce stuttering

  -snoforceformat : windows only, no force setting hardware sound buffer format, fixes minor issues with -primarysound

  -noquicktime : makes TF2 not initialise quicktime when you start the game; don't use this if you use the replay features

  -nosound : disables sounds from the game; only use if game is unplayable without it

  -small : makes the game allow smaller resolutions than 640x480


# If you still want more fps, disable the steam overlay:

  To disable the Steam Overlay:
  1) Head on to TF2 in your Steam Library
  2) Right-click on TF2
  3) Left-click Properties
  4) Uncheck the box that says: "Enable Steam Overlay while in-game"
  5) Launch the game
