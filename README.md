lLyrics Musixmatch
===============

lLyrics Musixmatch is a fork of [lLyrics](https://github.com/dmo60/lLyrics) to works best with Musixmatch.

lLyrics is a plugin for [Rhythmbox](http://projects.gnome.org/rhythmbox/), which displays lyrics for the current playing song in the sidebar.

It is intended as a replacement of the built-in lyrics plugin of Rhythmbox with more features, better UI integration and more lyrics engines.



![Screenshot](img/lLyricsMusixmatch.png)




Lyrics sources
---------------

  - Musixmatch
  - Lyricwiki.org
  - Letras.terra.com.br
  - Vagalume.com.br
  - Metrolyrics.com
  - AZLyrics.com
  - Lyricsnmusic.com
  - Lyricsmania.com
  - Rapgenius.com
  - Darklyrics.com
  - Chartlyrics.com
  - Leoslyrics.com
  - Lyrdb.com

It is also possible to retrieve lyrics from the built-in Rhythmbox lyrics plugin, but this is not recommended since it has some bugs and may cause instabilities.




Requirements
---------------

The 'master' branch supports Rhythmbox 3.0 and above. **It is incompatible with older Rhythmbox 2.xx versions!**

To get the plugin for Rhythmbox 2.xx, change to branch 'RB2'! It provides the last version compatible with Rhythmbox 2.xx, but please note, that it will quite certainly not be updated or developed any further.

To install lLyrics from source you will need the package gettext.

#### Dependencies ####

lLyrics can be run without the need of any additional packages, but it is recommended to install the python module **"chardet"** for better handling of different encodings.



Installation
---------------

#### Manual installation ####

	1.) Press the "Download ZIP" button and extract the .zip file.

	2.) Change to the extracted folder and open a terminal.

	3.) Run `make install`.

	4.) Enable the plugin in Rhythmbox.

This will install the plugin for the current user only. If you want to install it systemwide for all users, run `make install-systemwide` in step 3.
It will ask for your sudo password, but don't worry, it is only required to install the schema file that is needed to save your preferences.

To uninstall, run `make uninstall`.

Note that you need Rhythmbox version 2.90 or higher to run lLyrics!




Features
---------------
  - Support Musixmatch and a lot of different lyrics sites (see above)
  - Integration into the Rhythmbox UI
  - Lyrics sources can be prioritised and deactivated
  - Automatically display lyrics on playback or only on-demand
  - Save retrieved lyrics to a file (can be deactivated)
  - Possibility to edit lyrics
  - Correct artist/title tag via Last.fm API for better results
  - Appearance customizable to adapt to your desires or your available screen space
  - Basic support for synchronized lyrics
  - more...




Credits
---------------

Thanks to [lLyrics](https://github.com/dmo60/lLyrics).

All lyrics are property and copyright of their owners.
