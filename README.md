![](https://github.com/marynate/godot/wiki/images/godot_logo.png)

### About

[Godot](https://github.com/okamstudio/godot) is a fully featured, open source, MIT licensed, game engine.  
The Goal of Godot Localization Project is to help translating Godot Editor to your own language.

### License

All translations are licensed under same MIT license as Godot Game Engine.

### Directory Structure

- __templates__  	
po template file(s)
- __lang__  
po files which contain actual translations, stored by locales.
- __fonts__  
godot font files, mostly for display of CJK or other unicode characters.

### Translation process

__Generate PO Template__  
PO Template can be extracted from [GNU gettext](http://www.gnu.org/software/gettext/). For windows users, [GetText for WIndows](http://gnuwin32.sourceforge.net/packages/gettext.htm) can be used instead.

__Translating (offline)__  
[Poedit](https://github.com/vslavik/poedit) is recommended for Gettext translation, but you are welcome to use whatever your favorite PO editor.  

__Translating (Online)__  
You are also welcome to contribute to [Godot online translation project](https://poeditor.com/join/project?hash=15721c79eff2d02de1670f8e8664af13).  
(Thanks [POEditor](https://poeditor.com) team for free hosting!)


__Install PO to Godot Editor__  

First, make sure you choose a CJK font in editor settings dialog:  
![](http://oi61.tinypic.com/2q8108i.jpg)
Then you can install the translation file (.po)   
![](http://oi57.tinypic.com/293ehq9.jpg)

__Test with localized editor__

You can build localized editor from: https://github.com/marynate/godot/tree/PR-editor-tr  
Or if you can use pre-built windows binary: https://sourceforge.net/projects/godotengine/files/Builds/translation/

### Credits

ardy  
DayBreakWalker  
marynate  
nobot  
tappy  

### Screeshots

![](http://oi62.tinypic.com/13zzndv.jpg)

![](http://oi62.tinypic.com/155kl05.jpg)

![](http://oi62.tinypic.com/2qw0cpi.jpg)

![](http://oi57.tinypic.com/4smw7q.jpg)

please blame Google for funny translations :)
