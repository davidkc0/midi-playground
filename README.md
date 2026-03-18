# midi playground
bouncing square video, FOSS edition (and gamified)

![gif](https://github.com/user-attachments/assets/b2da77ce-b8b4-4a32-af93-23c02420e6af)


## how to do custom songs?

see [docs/SONGS.md](https://github.com/quasar098/midi-playground/blob/master/docs/SONGS.md) for custom song tutorial

## development guide

this is how you set up the code to run it from source, rather than a bundled pyinstaller executable

download python from [here](https://python.org) specifically (3.9.1 should work). do not download from windows store. that version is really janky and doesn't work that well for more complex python programs with lots of dependencies

install requirements with `python3 -m pip install -r requirements.txt`

start program with `python3 main.py`

build command: `pyinstaller main.py --noconsole --onefile --clean --hidden-import glcontext`


## contributors

- [quasar098](https://github.com/quasar098)
- [TheCodingCrafter](https://github.com/TheCodingCrafter) - Themes + QOL
- [PurpleJuiceBox](https://github.com/PurpleJuiceBox) - Reset to Default Button
- [sled45](https://github.com/sled45) - Mouse fix for high DPI displays
- [Times0](https://github.com/Times0) - dark_modern theme, Glowing, Colored pegs on bounce
- [Spring-Forever-with-me](https://github.com/Spring-Forever-with-me) - fix incorrect key name for screen resolution in the config
- [sj-dan](https://github.com/sj-dan) - opengl fix on mac os
- [zetlen](https://github.com/zetlen) - update shaders to use modern opengl api

- [cangerjun](https://github.com/cangerjun) - chinese translations
- [lucmsilva651](https://github.com/lucmsilva651) - brazilian portuguese and spanish translations
- [leo539](https://github.com/leo539) - french translations
- [simpansoftware](https://github.com/simpansoftware) - swedish translations
- [slideglide](https://github.com/slideglide) - turkish translations
- [Guavvva](https://github.com/Guavvva) - russian translations
- [SpeckyYT](https://github.com/SpeckyYT) - italian, ladin translations
- [suzuuuuu09](https://github.com/suzuuuuu09) - japanese translations
- [CoderMonkey1956](https://github.com/CoderMonkey1956) - german translations

## translation guide

want to add translations for a different language? please create a github pull request with the word "translations" in the title

if so, please add translations for as many of the texts (they are listed in translations.py) as you can

- "play"
- "config"
- "contribute"
- "open songs folder"
- "quit"
- "back"
- "midi-playground" text (this is the title of the software)
- the marquee on the title screen (the moving text that appears underneath the title on the main screen; see translations.py file for english example)
- "restart required"

(there are more in translations.py)

if you have any questions on what any texts are supposed to mean, see translations.py for the english examples before you make a github pull request

also, you can look at other languages' translations texts, which may be helpful to you

also, we are only adding real languages (no pirate speak or upside-down language like minecraft)

## (old) todo list

see [docs/TODO.md](https://github.com/quasar098/midi-playground/blob/master/docs/TODO.md)

