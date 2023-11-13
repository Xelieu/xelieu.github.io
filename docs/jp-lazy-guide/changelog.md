---
hide:
  - footer
---
# Changelog

---

## 2023

---

### November

**2023-11-13**

- Updated [Setup: Anki](https://xelieu.github.io/jp-lazy-guide/setupAnki/) because Aquafina and we can't update using `JPMN Manager` anymore
	- For existing users that installed before `2023-11-13`, go to: [Update: Anki JPMN Fork](https://xelieu.github.io/jp-lazy-guide/updateAnkiJPMNFork/)
	- Archived [Setup: Anki (Old)](https://xelieu.github.io/jp-lazy-guide/setupAnkiOld/) in case we can re-use `JPMN Manager` in the future

---

### August

**2023-08-05**

- Added a **VERY IMPORTANT** instruction: After installing `JPMN`, Rename `JPMN-Examples` to `Mining Deck` or it won't work at all

---

### July

**2023-07-18**

Yomichan: [LazyXel Yomichan Setup](https://drive.google.com/drive/folders/1s_PdQ9HWvpDFXkh_AGGzVgqrFBGhUsbI?usp=sharing) Update

- Updated Dictionary: `新明解国語辞典 第八版`
    - If you updated, please update Card [styling](https://pastebin.com/mu2jrrjB) on `Anki` too

**2023-07-17**

- Added [Setup: Anime](https://xelieu.github.io/jp-lazy-guide/setupAnimeOnPC/)

- Added more info and fix broken links

**2023-07-16**

- Rewrote [Lazy guide](https://xelieu.github.io/jp-lazy-guide/) using material mkdocs
- Abandoned updating [Rentry Lazy Guide](https://rentry.co/lazyXel/)
- Made [JPMN](https://aquafina-water-bottle.github.io/jp-mining-note/) as the main Anki Format and abandoned my `Lazy` Format

**2023-07-04**

- Added Manga Android Mining

---

### June

**2023-06-13:**

Updated: [Yomichan Local Audio](https://rentry.co/lazyXel/#optional-yomichan-local-audio-source) and [Android Yomichan Local Audio](https://rentry.co/lazyXel/#optional-android-yomichan-local-audio-source)

- You must redownload the file and only replace the `user_files` folder then `Tools` > `Local Audio Sever` > `Regenerate Database`

- For android you must regenerate the database again and paste, and update [AnkiConnect Android](https://github.com/KamWithK/AnkiconnectAndroid/releases/latest)

- Custom URL (JSON) has been replaced for both PC and android

---

### May

**2023-05-17:**

Added [Personal Setup](https://rentry.co/lazyXel/#personal-setup)

---

### March

**2023-03-17:**

Updated Immersion Data Spreadsheet up to 2035 check at [My Content](https://rentry.co/lazyXel#my-content)

### February

**2023-02-17:**

`Title` field: Just so it extracts the [title](https://imgur.com/w7hOpnP) to easily sort for niche uses

Yomichan

- Updated [Yomichan settings](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo) 

	- Added 2 new frequency [yomichan dictionary](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo): `Innocent Corpus Ranked`, `CC100`

	- Changed `Frequency sorting dictionary` to `CC100` (top results' reading is more accurate)

	- To accommodate `Title` field

Anki

- Added Additional field: `Browse` > `Card` > `Fields...`, add `Title` (case-sensitive)

Added [Modernized Core 2.3K Deck](https://rentry.co/lazyXel#other-resources): [Sample Format](https://imgur.com/BsJ2mTD)

**2023-02-06:**

In Yomichan; updated [settings](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo) and [yomichan dictionary](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo)(you need to update [JMdict](https://github.com/FooSoft/yomichan/raw/dictionaries/jmdict_english.zip) for settings to work):

- Updated pop-up yomichan custom CSS styling and to support [Light Mode](https://imgur.com/Yt6htdA): [manual update](https://pastebin.com/GzZGasvE)

	- Fixed stroke order not being shown

	- Added Kanji Info styling referenced from [Marv's kanji info dict css](https://github.com/MarvNC/yomichan-dictionaries#yomichan-css-for-kanji-dictionaries)

- Updated `freq` [Handlebar](https://pastebin.com/ZRTWSakg) from [Marv's sort by frequency](https://github.com/MarvNC/JP-Resources#sorting-mined-anki-cards-by-frequency)

- Added Kanji info dicts | Updated JMdict, JMnedict: [yomichan dictionary](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo)
	- If you are updating the dicts, you need to also update(manually if you didn't download my settings) the [Handlebar](https://pastebin.com/ZRTWSakg)(JMdict changes) and replace `{test}` with `{glossary-jmdict-compact-brief}` in `Configure Anki Card Format...`

- Updated [Text replacement pattern](https://pastebin.com/tzHgVe6V)

Added [Modernized Kanken Deck](https://rentry.co/lazyXel#other-resources): [Sample Format](https://imgur.com/ylH4yt2)

---

### January

**2023-01-17:**

In [Anki Modern and Simple Format](https://drive.google.com/drive/u/5/folders/1QSDSkkHnCiHOfNYAVtBQIZc7tQ6z7Jz1): added `Frequency` field (for Marv's [Frequency Sorter](https://github.com/MarvNC/JP-Resources#sorting-mined-anki-cards-by-frequency))

- Added addon [AutoReorder](https://ankiweb.net/shared/info/757527607)
In Anki (Modern Design): improved [styling](https://pastebin.com/DiyjKiRL) of color scheme on [dark mode](https://imgur.com/6Iklj8a)

In Yomichan: 

- Added `{freq}` to Anki format and [Handlebar](https://pastebin.com/ZRTWSakg)

Added [FSRS Algorithm](https://forums.ankiweb.net/t/how-to-use-the-next-generation-spaced-repetition-algorithm-fsrs-on-anki/25415) (still experimental) on [Retention How-to](https://rentry.co/lazyXel#retention-how-to)

---

## 2022

---

### December


**2022-12-26:**

Updated [Immersion Spreadsheet](https://rentry.co/lazyXel#my-content) up to 2025, existing users check the last bullet for instructions.

---

### August

**2022-08-26:**

In Anki (Modern Design): update [here](https://drive.google.com/drive/u/5/folders/1QSDSkkHnCiHOfNYAVtBQIZc7tQ6z7Jz1) or [front](https://pastebin.com/kGq0WJs3), [back](https://pastebin.com/4FpXEru1), [styling](https://pastebin.com/DiyjKiRL)

- Added Modern design(Simple will still exist): [[Light Mode](https://imgur.com/WJ04wsK) | [Dark Mode](https://imgur.com/SfV5xIv)], reference a lot from medamayaki#0328's grammar deck

- Fully supports mobile sizing

- Existing user: easier to update through copy and paste: `Browse Deck` > `Mining Deck` > `Card...` > `front/back/styling`

---

### July

**2022-07-01:**

- Added Yomichan Local Audio Source(optional), can be found by the end of [Yomichan Section](https://rentry.co/lazyXel#yomichan)

In Anki (Simple Design): update [here](https://drive.google.com/drive/u/5/folders/1QSDSkkHnCiHOfNYAVtBQIZc7tQ6z7Jz1) or [front](https://pastebin.com/vjgi6Lw0), [back](https://pastebin.com/7YALnSH3), [styling](https://pastebin.com/cqgicP8Z)

- Added [Light Mode](https://imgur.com/nm70jXt)

- Added [Alternative Dark Mode](https://imgur.com/CBYNlNq), go [here](https://rentry.co/lazyXel#alternative-anki-design)

- Added automatic sentence hint in front of the card when vocab is Furigana

- Added [Additional fields](https://imgur.com/0MzNr6v)(Browse > Card > Fields...), please add `Meikyou`, `Jitsuyou`, `Kenkyusha` (case-sensitive)
	- This is optional and existing anki format will work just fine, it just won't fetch this monolingual dictionaries
	- This is manual update for existing anki format users since you can't really copy paste fields

In [Yomichan settings](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo):

- Updated Monolingual profile; it didn't have the auto light/dark mode pitch accent graph

- [Design improvement](https://imgur.com/xAyv8ZM) for hovering; manual snippet [here](https://pastebin.com/GzZGasvE)

- Made a cleaner handlebar format that removes things like 〘v5m・vt〙or →さばを読む

- Added the new fields into anki mining template

---

### April

**2022-04-24:**

- Added [Manga with Yomichan](https://rentry.co/lazyXel#mangaocr-or-manga-with-yomichan)

- Added +1 yomichan frequency dictionary(JPDB), already added on my [7z file](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo) or individually [here](https://github.com/MarvNC/jpdb-freq-list/releases)

In [Yomichan settings](https://drive.google.com/drive/u/5/folders/1EJrp6kGNhDv-9Ndx_YAtCAn5lidAF9zo):

- Collapsible monolingual dictionary so it isn't hard to scroll down

- Minor handlebar changes

- Changed the Frequency sorting dictionary

In [Anki add-ons](https://drive.google.com/drive/u/5/folders/1QSDSkkHnCiHOfNYAVtBQIZc7tQ6z7Jz1):

- Added [forvo audio](https://ankiweb.net/shared/info/858591644) add-on, in 'Browse' you can highlight a card and click audio button to add audio

- Added [AJT Mortician](https://ankiweb.net/shared/info/1255924302) add-on, this is optional, you can edit the config on the toolbar through 'AJT'

**2022-04-03:**

- [Yomichan](https://rentry.co/lazyXel#yomichan) settings, just import it and you're good, mostly minor designs, code cleaning, forvo audio and added [Kiwi for Phone](https://rentry.co/lazyXel#read-light-novel-anywhere-with-yomichan-and-mining) Profile

- [Manga OCR or Manga with Yomichan](https://rentry.co/lazyXel#mangaocr-or-manga-with-yomichan) in replace of Capture2Text (It is inferior)

- Replaced [Read Light Novel ANYWHERE with yomichan and mining](https://rentry.co/lazyXel#read-light-novel-anywhere-with-yomichan-and-mining) FROM kiwi + zerotier TO Ankiconnect Android + ankidroid + kiwi setup (no PC turned on needed)

---

## 2021

---

### November

**2021-11-27:**

- Updated [Anki](https://rentry.co/lazyXel#anki) format sentence highlight from underline to purple, bilingual highlighted text not showing up fix

- Updated my [Immersion Data Spreadsheet(Clean; up to 2022)](https://docs.google.com/spreadsheets/d/1VnPPeWW5pWxDtNDGktyG5_F3JXckMgpJlF3ud5DHVDw/edit?usp=sharing) Overall tab which had formula errors (Just duplicate and replace the specific sheet so you don't have to redo your immersion)

---

### September

**2021-09-27 11:32 UTC**

- #### JP LAZY Guide was made
	- [Rentry Lazy Guide](https://rentry.co/lazyxel)