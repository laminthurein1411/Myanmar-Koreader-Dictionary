# Myanmar-Koreader-Dictionary

Edited this dictionary's `.ifo` file as non-HTML and changed `sametypesequence=h` in it to `sametypesequence=x`. So KOReader will strip the HTML tags to get and display plain text (while trying to preserve line breaks). You won't get italic or bold.

Koreader default font can't support Myanmar text so you need to add NotoSan Myanmar font [manually.](https://github.com/koreader/koreader/discussions/8655#discussioncomment-1950420)

Noto Sans Myanmar fonts to be used as [UI fallback fonts](https://github.com/koreader/koreader/pull/8722)
