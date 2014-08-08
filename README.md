## Welcome to Railcraft's Localization repository on GitHub

### Submitting and editing a language file
If you intend to submit or edit a language file, please be aware that the file must be in UTF-8 encoding without Byte-Order-Marks(BOM).

If you do not know what any of that means, please do some research before submitting a language file.

Notepad++ is the recommend text editor for editing language files because it is capable of saving files in the correct format via the Encoding menu.

Other editors may not save files in the correct format (Notepad, Wordpad, etc...do not).

While editing a language file, you can simply drop it in the ".minecraft/config/railcraft/lang" folder and the game will load it automatically, overriding any existing translations.

### Java Formatting Tags
You may notice some translation entries have strange characters such as "@s" or "@2$s". These are identical to Java Formatting Tags, but with '@' replacing '%' for technical reasons. They will be replaced with another variable at run time. They can be used to reorder or format messages and the like.

More information can be found [here](http://docs.oracle.com/javase/6/docs/api/java/util/Formatter.html).

### Minecraft Formatting Tags
You may also notice some stuff like "�r" or "�5". These are Minecraft Formatting Tags and are generally used to set the text color and italicize/bold pieces of text.

More information can be found [here](http://www.minecraftwiki.net/wiki/Formatting_codes).