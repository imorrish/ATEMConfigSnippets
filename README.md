# ATEMConfigSnippets
Visual Studio Code Snippet file for Blackmagic ATEM Configuration XML file
This has now been published to the market place. See https://ianmorrish.wordpress.com/2019/10/06/atem-macro-editing-snippets-for-vscode/

The Blackmagic ATEM software allows users to export all or a subset of the switcher configuration as an XML file. This can be useful for manipulating complex functions such as keyers and DVE options but has become even more important with the support for macros.
The ATEM software allows recording of simple macros by watching what you do in the software or hardware panel but these macros will often require some post editing to get them working just the way you want.

After exporting the configuration from the software, you will need to edit the file. Any text or code editor can be used for this.
A good open source, cross platform, code editor I use is VS-Code https://github.com/Microsoft/vscode. 
I have created this snippet definition for VS-Code to insert some common macro operations or create an entire ATEM configuration file for macros.
Just copy the xml.jason file to the default location based on your OS:
    Windows: %APPDATA%\Code\User\snippets\
    MAC: $HOME/Library/Application Support/Code/User/snippets/
    Linux: $HOME/.config/Code/User/snippets/

Once the snippet is more complete I'll publish it to the VS-Code gallery.
![Alt text](https://github.com/imorrish/ATEMConfigSnippets/blob/master/MacroSnippet.gif?raw=true "Animated Gif")
