# Expand Chord Symbols

This MuseScore 3 plugin finds all the chord symbols in the current score, then generates the corresponding notes into a staff.

The user can choose whether to generate
* all the notes for each chord, which could be 8 or 9 notes for a complex chord (e.g. C13), or
* a condensed chord containing only the 4 most harmonically important notes, plus a bass note, and inverted as needed 
so that most of the notes are near or below middle C. This "condensed" mode gives results almost identical
to Marc Sabatella's recommended voicings shown [here](https://www.youtube.com/watch?v=iaca_EAmBCE&feature=youtu.be%0A) and [here](https://musescore.com/marcsabatella/chord-symbol-voicings-for-playback).

Notes are always added to voice 1 of the last staff in the score. Any notes in that voice in that staff will be overwritten.

To install the plugin:
1. click on ExpandChordSymbols.qml (above)
1. on the resulting page, find the button "Raw", just above the text
1. right-click on the Raw button, and select Save Link As... (your browser may have different wording)
1. download the file to the Plugins folder, in the following location...
   * Windows: %HOMEPATH%\Documents\MuseScore3\Plugins
   * Mac: ~/Documents/MuseScore3/Plugins
   * Linux: ~/Documents/MuseScore3/Plugins
1. launch MuseScore
1. select the menu item Plugins > Plugin Manager...
1. in the resulting dialog, enable expandChordSymbol
   
To use the plugin:
1. make sure that the last staff in the score is the one you want the plugin to modify. If necessary, go to Edit > Instruments and move or add staffs as required. It will look best in bass clef.
1. select the menu item Plugins > Expand Chord Symbols….
1. the resulting dialog tells you which staff it will write to, warns you if any existing notes will be overwritten, and allows you to select raw vs. condensed mode.
1. click OK
      
     
      



