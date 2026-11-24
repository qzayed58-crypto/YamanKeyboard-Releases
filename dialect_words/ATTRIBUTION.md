# SauDial word-list attribution

Source: [SauDial: The Saudi Arabic Dialects Game Localization Dataset, version 2](https://data.mendeley.com/datasets/mzdwkb2t6d/2), by Hussein Abu-Rayyash and Naif Alanazi, Mendeley Data, DOI [10.17632/mzdwkb2t6d.2](https://doi.org/10.17632/mzdwkb2t6d.2). The dataset is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Changes made: extracted Arabic words only from the dataset's **Dialect Translation** column; excluded one-character fragments and number-attached article fragments; removed diacritics, punctuation, and duplicate spellings within each dialect; sorted words by their frequency in the source. English text, Modern Standard Arabic, dialogues, context notes, and the source's Python generator were not copied. The word lists are not a complete dictionary or a context model, and retaining them does not imply endorsement by the dataset creators.

Files and sizes (unique entries):
- `najdi.txt` — 2162 words (271 source entries)
- `hijazi.txt` — 2156 words (265 source entries)
- `southern.txt` — 1815 words (223 source entries; the source uses the label “Southern”)
- `eastern.txt` — 1982 words (241 source entries)

The four plain-text lists are published at `YamanKeyboard-Releases/dialect_words/` for direct download. Yaman caches the downloaded lists in its private app storage; it does not package them as Android assets or include them in the APK. Only the extracted Arabic words are distributed here—no source code or dialogue sentences.
