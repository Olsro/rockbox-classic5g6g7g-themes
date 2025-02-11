# digitalReduxDetox
Modified/Derived from digitalRedux theme by D Juarez. The base theme supports CJK characters out of the box, so I didn't need to work on this aspect for this one.

Changelog:
- Time to detox from excess of informations in the WPS. These non-necessary infos have been removed:
	- Battery percentage (but is still available anywhere else)
	- The big "Now playing" label has been removed
	- The format name, the frequency, and the codec name have been removed
	- The disk accesses animated icon has been removed (but is still available anywhere else)
- Detox yourself from excessive texts in the WPS: the cover art is now bigger than ever, increasing your immersion and focus into the music that you are currently listening to !
- Fixed alignment of status bar icons into each others, so it look better overall
- Fixed vertical alignments from Title/Artist/Album in the WPS
- The clock is the status bar is now a proper white label, which makes it way easier to read the clock when the backlight is off rather than the orange text on black blackground.
- When changing the volume in the WPS, you can now see the precise decibel numerical value the time being.

![Alt text](digitalReduxDetox/screenshots/wps1.png?raw=true "WPS1")
![Alt text](digitalReduxDetox/screenshots/wps2.png?raw=true "WPS2")
![Alt text](digitalReduxDetox/screenshots/menu.png?raw=true "MENU")

# retroTapeFixed
Modified/Derived from retroTape theme for iPod Video (CC-BY-SA 3.0) by Humberto Santana.

Changelog : 
- Use the font "Rockbox-Mix" in menus and in WPS. This design choice results in full compatibility with Chinese/Japanese/Korean characters.
- Removed the visual lines in the background of the menus. This was causing visual issues depending on the size of the selected font.
- Cover art is now hidden in the quick screen menu. Showing album art in the menu was causing visual glitches when using shortcuts in this menu.
- Show icons in menus by default

![Alt text](retroTapeFixed/screenshots/wps.png?raw=true "WPS")
![Alt text](retroTapeFixed/screenshots/menu.png?raw=true "MENU")

# ipodmod3blkFixed
Modified/Derived from iPodMod3Blk Theme theme for iPod Video (CC-BY-SA 3.0) by K4sum1.

Changelog : 
- Use the font "Rockbox-Mix" in WPS to show the artist name, album name, and year. This provides full compatibility with Chinese/Japanese/Korean characters.
- Use the font "18-Cantarell-Bold.fnt" in menus and to show the title of the song in WPS. This provides full compatibility with Chinese/Japanese/Korean characters.
- The playback icons (replay status) in status bar was not properly vertically centered with the shuffle icon
- The lock icon was never appearing outside the WPS
- The play/pause icons were never appearing outside the WPS
- If "Year" can't be found in ID3Tags, it will now appear as an empty space rather than showing an ugly "null" string
- Some formats like MPCV8 appeared as "?" in WPS, it is now fixed

![Alt text](ipodmod3blkFixed/screenshots/wps.png?raw=true "WPS")
![Alt text](ipodmod3blkFixed/screenshots/menu.png?raw=true "MENU")