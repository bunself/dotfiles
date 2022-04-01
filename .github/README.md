# Dotfiles

  
[![FreeBSD](https://img.shields.io/badge/FreeBSD-13.0-ff7eb6?style=flat&logo=freebsd)](https://www.freebsd.org/) [![River](https://img.shields.io/badge/River-0.1.3-33b1ff?style=flat&logo=i3)](https://github.com/riverwm/river)
<div align=left>
  I don't really know what to say here, so here's a screenshot

  <img src="https://raw.githubusercontent.com/bunself/dotfiles/main/.github/assets/dots.png" alt="img" align="right" width="475px">
  
### Programs Used
    
 * [river](https://github.com/riverwm/river) (compositor)
 * [waybar](https://github.com/Alexays/Waybar) (status bar)
 * [kitty](https://github.com/kovidgoyal/kitty) (terminal emulator)
 * [deadbeef](https://github.com/DeaDBeeF-Player/deadbeef) (music player)
 * [firefox](https://www.mozilla.org/en-US/firefox/new/) (browser)
## Installation 
 * Clone this repostory
 * Make sure the following packages are installed (or your alternative/s of choice) `waybar` `river` `kitty` `firefox` `deadbeef` `wofi`

 #### Firefox
  <img src="https://raw.githubusercontent.com/bunself/dotfiles/main/.github/assets/firefox.png" alt="img" align="right" width="400px">
  
   * Go to about:config and set "toolkit.legacyUserProfileCustomizations.stylesheets" to true  
   * After this find your firefox profile at about:support (labeled "Profile Folder")
   * If the chrome directory in your profile folder isnt already present create it 
   * Move the userChrome.css file to it
   * Install the[ Tab Center Reborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/) extension
   * Copy the contents of tabCenterReborn.css to the custom stylesheet menu under the preferences for the vertical tab extension
   * You'll also need to fiddle around w/ the firefox color extension a bit
 
  
  #### Waybar
  
   <img src="https://raw.githubusercontent.com/bunself/dotfiles/main/.github/assets/waybar.png" alt="img" align="center" width="1000px">
  
   * Just two notes for now, the [JetBrains Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/JetBrainsMono/Ligatures/Regular/complete/JetBrains%20Mono%20Regular%20Nerd%20Font%20Complete.ttf) is recommended
   * (Most of) The modules for waybar **will not work on non FreeBSD systems**, so some tinkering may be needed to get them to work
  #### Deadbeef
  
   <img src="https://raw.githubusercontent.com/bunself/dotfiles/main/.github/assets/deadbeef.png" alt="img" align="right" width="400px">
  
  
   * Get [this](https://github.com/EliverLara/Nordic) gtk theme and move it to /usr/share/themes or wherever the gtk theme directory is on your distro
   * Replace /gtk-2.0/gtkrc with the gtkrc from this folder
   * Side note: You might need to fiddle around w/ playlist names, dimensions and whatnot; as this was made on a 1366x768 display with my specific music library.
 
 #### Placeholder
   * Move the reamaining folders under config to your .config folder
 
## Inspiration
*  [IBM deisgn guidelines](https://www.ibm.com/design/language/) and this [rice](https://github.com/bunself/dotfiles/blob/main/.github/assets/shaunsingh.png) (Hi_Im_Bored#1741)
* [Simple-Bar](https://github.com/Jean-Tinland/simple-bar) for yabai
* [This](https://www.reddit.com/r/foobar2000/comments/ogs88y/my_dark_mode_foobar_theme/) foobar2000 theme
