# Technics RSBX-828 Cassette Deck
Theme for [foobar2000](https://www.foobar2000.org), imitating the Technics RSBX-828 cassette deck

Implemented based on [foo_uie_wsh_panel_mod_plus](https://github.com/ttsping/foo_uie_wsh_panel_mod_plus) from [ttsping](https://github.com/ttsping) for any resolution, up to 4K.

Scales to fit the window.

There are two options available:
- Full assembly (full.zip)
- Theme files for integration into other builds (theme.zip)

## Full assembly
The theme consists of two windows: 
- The cassette deck in the main foobar2000 window
<img src="images/screenshot.jpg" width=100%>

- A dockable control panel based on  [foo_dockable_panels](http://wiki.bowron.us/index.php/Foobar2000) by Christopher Bowron  

<img src="images/control_panel.jpg" width=100%>

### Installation
- Extract files from the full.zip archive
- Install fonts from the fonts folder of the full.zip archive (duplicated in foobar2000_hi-fi\themes\hi-fi\common\fonts)

Installation is complete

## Theme files for integration into the assembly
The archive contains theme files and the following components:
- foo_dockable_panels
- foo_uie_wsh_panel_mod_plus
- foo_vis_vumeter

### Installation
- Create an archive of your build
- Extract files from the theme.zip archive into the build
- Install the foobar2000_hi-fi\themes\hi-fi\common\fonts\lcd_technics_rsbx_828.ttf font
- Place panel foo_uie_wsh_panel_mod_plus
-	Load the script foobar2000_hi-fi\themes\hi-fi\cassette_deck_4k\Scripts\TechnicsRSBX_4K.txt into the panel

## Addition
Both options have a customized window based on foo_dockable_panels.

<img src="images/foo_dockable_panels_default.jpg" width=100%>

Window call:

<img src="images/foo_dockable_panels_call.jpg" width=100%>

## Management
<img src="images/control.jpg" width=100%>

- 1 - Exit foobar2000 (minimize the foo_dockable_panels deck window)
- 2 - Menu foobar2000
- 3 - Free (mouse drag / mouse wheel)
- 4 - Move along the track (mouse drag / mouse wheel)
- 5 - Switching the type of cassette compartment cover
- 6 - Reset the counter to 0
- 7 - Switching the counter mode (elapsed / remaining)
- 8 - Switch Playback Order. Left / Right side of the button - / +
- 9 - Switch indicator type (requires foo_vis_vumeter)
- 10 - Switches the cassette view. The left side of the button is the previous one, the right side is the next one (mouse click / mouse wheel)
- 11 - Switches the cassette reel view. The left side of the button is the previous one, the right side is the next one (mouse click)
- 12 - Deck Menu
- 13 - Switching the display of information about the current track
- 14 - Toggle the display of tooltips
- 15 - Previous track. Holding the button moves backward through the track. The step is adjusted with knob #27.
- 16 - Stop
- 17 - Play
- 18 - Next Track. While holding the button, move through the tracks. The step is adjusted with knob #27.
- 19 - Pause
- 20 - Mute
- 21 - Calling the Quick Convert window
- 22 - Calling the Control Panel window
- 23 - Volume (mouse drag / mouse wheel)
- 24 - Balance (requires foo_ui_hacks) (mouse drag / mouse wheel)
- 25 - Reel speed. Default is 50 ms. Decreasing the interval increases the reel speed and CPU load (mouse drag/mouse wheel).
- 26 - Free (mouse drag / mouse wheel)
- 27 - Track movement step. Default is 3 seconds (mouse drag / mouse wheel)

### Mouse movement
- Move the deck within the window: Shift + left button
- Move window: Ctrl + left button
- Align the deck in the window: double click

### Deck menu

<img src="images/deck_settings.jpg" width=100%>

- Scale 100% - displays the deck at full size. Move: Shift + left button
- Lock Scale - locks the current deck size. Resizing the window prevents scaling.
- Enable Sound Effects - plays sounds when buttons are pressed
- Bottom Position Deck - Positions the deck at the bottom of the window. When disabled, it's centered in the window.

Additionally for foo_dockable_panels:
  
- Transparency Window - Sets a transparent background
- Auto Size Window - Setting the window size to the deck

### Transparent background for the theme in the foobar2000 window
  
<img src="images/ui_hacks.jpg" width=100%>

### Transparent background for theme in foo_dockable_panels window:

<img src="images/dockable.jpg" width=100%>

-	Select Transparency Window from the theme menu
- Remove window border foo_dockable_panels

Support the author

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1N61ZS5FW)
