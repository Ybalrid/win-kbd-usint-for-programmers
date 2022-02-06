# US International Layout (undead quote) for Windows

(US INTernational but for PRoGramers 🙂)

By default, Windows includes a layout called United States-International, which allows typing many non-ASCII characters. It is very useful for several Latin-script based languages.

The layout also designates several keys as "dead keys", particularly the apostrophe (') and double quotes ("). So to enter double quotes, you have to type " followed by space. Some other characters are available by using AltGr as a dead key.

For some use cases, this can be annoying, in particular if you don't need the non-ASCII characters that are entered with the help of those dead keys. With the US-International layout, you can type several languages by only using the AltGr dead key. For example, you can type ä å ö ü ß ø æ by using various AltGr combinations, meaning AltGr is sufficient for German, Danish, Norwegian and Swedish among others.

This repository contains a layout that is like United States-International but removes the apostrophe (') and double quotes (") as dead keys, while leaving the AltGr dead key combinations intact.

This is a fork of this repository https://github.com/umanovskis/win-kbd-usint-nodead

The modification made to the original were made to be a middle of the road option between totally removing all dead keys (like unamovskis keymap) and being able to still type characters that reauire ``` `~` `^` as dead keys.

My usecase is to be able to type in proper French (è and ê weren't accessible), while keeping using a US keyboard, and to not make using `'` and `"` a chore.

This keeps ``` being a dead key, so it might not be suitable for accessing some video game's in-game console.1 

# How to build / install

The layout file can be opened with Microsoft's Keyboard Layout Creator (MKLC) tool, which Microsoft distributes for free. After opening the file in MKLC, choosing Project -> Build DLL and Setup Package will create an installer that can be used to add this layout to Windows.

**Remember** to log off and on again, in order for the changes to take effect.

The USINTPRG folder contains the output of running the installer, if you do not want to bother with the tool. 
