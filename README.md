# XTMP Fallback Fonts for Casualties: Unknown

These fonts are intended to be metrically-compatible fallback fonts for Casualties: Unknown, where the fonts for the Main UI and Health panel UI have extended language support, covering a ton more languages of Latin and Cyrillic scripts, as well as Greek.

You will need to have XTMP already set up in order to add fallback fonts into the game.


## Usage guide

1. Install [XTMP](https://github.com/kawalain/XTMP) in your [BepInEx](https://github.com/BepInEx/BepInEx) plugin. (Check the tutorial links provided by the repositories for instructions to set up.)
2. Place the `.ttf` font files into the `BepInEx/plugins/XTMP/fonts` directory.
3. Write the configuration file as provided below, then save it as a `.ini` file (e.g.: `configuration.ini`) and put it in the same directory as the `.ttf` font files.
```
Retro Gaming Plus

[Retro Gaming]
Retro Gaming Plus

[I-pixel-u]
I-pixel-u Plus
```
  > If you wish to customise the fallback/replacement font, refer to the [configuration syntax](https://github.com/kawalain/XTMP#configuration-syntax).


## Supported languages

145 total languages are supported by both fonts, as detected by https://fontdrop.info: 

Azerbaijani, Belarusian, Bosnian, Bulgarian, Chechen, Macedonian, Ossetic, Russian, Sakha, Serbian, Ukrainian, Uzbek, Greek, Afrikaans, Aghem, Akan, Albanian, Asturian, Asu, Bafia, Basaa, Basque, Bemba, Bena, Breton, Catalan, Chiga, Colognian, Cornish, Croatian, Czech, Danish, Duala, Dutch, Embu, English, Esperanto, Estonian, Ewe, Ewondo, Faroese, Filipino, Finnish, French, Friulian, Fulah, Galician, Ganda, German, Gusii, Hawaiian, Hungarian, Icelandic, Igbo, Inari, Sami, Indonesian, Irish, Italian, Jola-Fonyi, Kabuverdianu, Kabyle, Kako, Kalaallisut, Kalenjin, Kamba, Kikuyu, Kinyarwanda, Koyraboro, Senni, Koyra, Chiini, Kwasio, Lakota, Langi, Latvian, Lingala, Lithuanian, Lower, Sorbian, Luba-Katanga, Luo, Luxembourgish, Luyia, Machame, Makhuwa-Meetto, Makonde, Malagasy, Maltese, Manx, Masai, Meru, Metaʼ, Morisyen, Mundang, Nama, Ngiemboon, Ngomba, Northern, Sami, North, Ndebele, Norwegian, Bokmål, Norwegian, Nynorsk, Nuer, Nyankole, Oromo, Polish, Portuguese, Prussian, Quechua, Romanian, Romansh, Rombo, Rundi, Rwa, Samburu, Sango, Sangu, Scottish, Gaelic, Sena, Serbian, Shambala, Shona, Slovak, Slovenian, Soga, Somali, Spanish, Swahili, Swedish, Swiss, German, Tachelhit, Taita, Tasawaq, Teso, Tongan, Turkish, Upper, Sorbian, Uzbek, (Latin), Vai, Vietnamese, Volapük, Vunjo, Walser, Welsh, Western, Frisian, Yangben, Yoruba, Zarma, Zulu.


## Credits

The effort of expanding language support for _Retro Gaming Plus_ was done by Catterio.

_I-pixel-u_ Plus was made by Catterio.

_Retro Gaming_ was made by Daydarius.

_I pixel u_ was made by rodrigosrtz.
