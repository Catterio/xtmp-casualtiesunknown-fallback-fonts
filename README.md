# XTMP Fallback Fonts for Casualties: Unknown

These fonts are intended to be metrically-compatible fallback fonts for Casualties: Unknown, where the fonts for the Main UI and Health panel UI have extended language support, covering a ton more languages of Latin and Cyrillic scripts, as well as Greek.

You will need to have XTMP already set up in order to add fallback fonts into the game.


## Usage guide

1. Install the [BepInEx](https://github.com/BepInEx/BepInEx/releases) plugin. (Refer to this [KrokMP installation tutorial](https://youtu.be/heVTSZc2a20) for instructions on how to set up BepInEx.)
2. Create a folder named `XTMP` inside `BepInEx/plugins`. Download `XTMP.dll` and `XTMP.pdb` from the [XTMP repository](https://github.com/kawalain/XTMP/releases/latest) and place them in the newly-created folder.
3. Download the `.ttf` font files ([here](https://github.com/Catterio/xtmp-casualtiesunknown-fallback-fonts/releases/latest)) and place them in the `XTMP` folder.
4. Write a configuration file as provided below, then save it as a `.ini` file (e.g.: `configuration.ini`) and place it in the same folder.
```
Retro Gaming Plus

[Retro Gaming]
Retro Gaming Plus

[I-pixel-u]
I-pixel-u Plus
```
  > If you wish to customise the fallback/replacement font, refer to the [configuration syntax](https://github.com/kawalain/XTMP#configuration-syntax).


  At the end, your `BepInEx/plugins/XTMP` directory should look something like this:
```
BepInEx/plugins/XTMP/
├── configuration.ini
├── XTMP.dll
├── XTMP.pdb
├── I-pixel-u Plus.ttf
└── Retro Gaming Plus.ttf
```


## Supported languages

144 total languages are supported by both fonts, as detected by https://fontdrop.info: 

Afrikaans, Aghem, Akan, Albanian, Asturian, Asu, Azerbaijani, Bafia, Basaa, Basque, Belarusian, Bemba, Bena, Bosnian, Breton, Bulgarian, Catalan, Chechen, Chiga, Colognian, Cornish, Croatian, Czech, Danish, Duala, Dutch, Embu, English, Esperanto, Estonian, Ewe, Ewondo, Faroese, Filipino, Finnish, French, Friulian, Fulah, Galician, Ganda, German, Greek, Gusii, Hawaiian, Hungarian, Icelandic, Igbo, Inari Sami, Indonesian, Irish, Italian, Jola-Fonyi, Kabuverdianu, Kabyle, Kako, Kalaallisut, Kalenjin, Kamba, Kikuyu, Kinyarwanda, Koyraboro Senni, Koyra Chiini, Kwasio, Lakota, Langi, Latvian, Lingala, Lithuanian, Lower Sorbian, Luba-Katanga, Luo, Luxembourgish, Luyia, Macedonian, Machame, Makhuwa-Meetto, Makonde, Malagasy, Maltese, Manx, Masai, Meru, Metaʼ, Morisyen, Mundang, Nama, Ngiemboon, Ngomba, Northern Sami, North Ndebele, Norwegian Bokmål, Norwegian Nynorsk, Nuer, Nyankole, Oromo, Ossetic, Polish, Portuguese, Prussian, Quechua, Romanian, Romansh, Rombo, Rundi, Russian, Rwa, Samburu, Sango, Sangu, Scottish Gaelic, Sakha, Sena, Serbian, Shambala, Shona, Slovak, Slovenian, Soga, Somali, Spanish, Swahili, Swedish, Swiss German, Tachelhit, Taita, Tasawaq, Teso, Tongan, Turkish, Upper, Sorbian, Ukrainian, Uzbek, Uzbek (Latin), Vai, Vietnamese, Volapük, Vunjo, Walser, Welsh, Western Frisian, Yangben, Yoruba, Zarma, Zulu.


## Credits

Expanding language support for _Retro Gaming Plus_ was done by Catterio.

_I-pixel-u_ Plus was made by Catterio (independent of _I pixel u_).

_Retro Gaming_ was made by Daydarius.

_I pixel u_ was made by rodrigosrtz.
