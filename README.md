# Myanmar-Koreader-Dictionary

## Installation

1.  Download the the `Dict.zip` archive from the [latest release](https://github.com/laminthurein1411/Myanmar-Koreader-Dictionary/releases/download/main/Dict.zip).
2.  Extract the `Dict.zip` file 
3.  Copy the `Dict` directory to the `koreader/data/dict/` folder on your device.
4.  Restart KOReader.

## Add Myanmar font in Koreader UI

1. Koreader default font can't support Myanmar text so you need to add NotoSan Myanmar font [manually.](https://github.com/koreader/koreader/discussions/8655#discussioncomment-1950420)
2. Noto Sans Myanmar fonts to be used as [UI fallback fonts](https://github.com/koreader/koreader/pull/8722)
3. Skip this step if you have already support Myanmar font


## Note

Edited this dictionary's `.ifo` file as non-HTML and changed `sametypesequence=h` in it to `sametypesequence=x`. So KOReader will strip the HTML tags to get and display plain text (while trying to preserve line breaks). You won't get italic or bold.

## Credits
* [ornagai](https://www.ornagai.com/) - For the dictionary data
