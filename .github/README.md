# Dotfiles

  
[![FreeBSD](https://img.shields.io/badge/FreeBSD-13.0-red?style=flat&logo=freebsd)](https://www.freebsd.org/) [![River](https://img.shields.io/badge/River-0.1.3-blue?style=flat&logo=i3)](https://github.com/riverwm/river)
<div align=left>
  I don't really know what to say here, but here are some screenshots 
<img src="https://raw.githubusercontent.com/bunself/dotfiles/assets/placeholder.png" alt="img" align="right" width="400px">
### Programs Used
  
## Installation 
 * Clone this repostory
 * Make sure the following packages are installed (or your alternative/s of choice) `waybar` `river` `kitty` `firefox`
 * If you wish to install the firefox theme go to about:config and set "toolkit.legacyUserProfileCustomizations.stylesheets" to true
   * After this find your firefox profile at about:support (labeled "Profile Folder")
   * If the chrome directory in your profile folder isnt already present create it 
   * Move the userChrome.css file to it
   * Install the[ Tab Center Reborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/) extension
   * Copy the contents of tabCenterReborn.css to the custom stylesheet menu under the preferences for the vertical tab extension
   * Remove the firefox directory from the config folder
 * Move the reamaining folders under config to your .config folder **(Note: The modules for waybar will not work on non FreeBSD systems, so some tinkering may be needed to get them to work)**
   
 
## Inspiration
*  [IBM deisgn guidelines](https://www.ibm.com/design/language/) and this [rice](https://github.com/bunself/dotfiles/blob/main/.github/assets/shaunsingh.png) (Hi_Im_Bored#1741)
* [Simple-Bar](https://github.com/Jean-Tinland/simple-bar) for yabai
* [This](https://www.reddit.com/r/foobar2000/comments/ogs88y/my_dark_mode_foobar_theme/) foobar2000 theme
