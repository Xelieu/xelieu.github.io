# Setup: Manga on PC

- MangaOCR is a tool used to scan a `Japanese` text and return it to your clipboard which you can scan in `Yomichan`

- (Recommended) Mokuro Manga is a setup that first processes the `manga` to be able to hover the words and scan them using `Yomichan`

---

## MangaOCR

Requirements

- Install [CDisplay](https://www.cdisplay.me/)
    - Manga Reader for `PC`
- [Yomichan](https://xelieu.github.io/jp-lazy-guide/jp-lazy-guide/setupYomichan/) and [ShareX](https://xelieu.github.io/jp-lazy-guide/jp-lazy-guide/setupShareX/) already set-up

---

## Setup: MangaOCR

1. Download [python](https://www.python.org/downloads/release/python-31011/)
    - Then choose Windows/mac `INSTALLER (64-bit)` and install
    - Check `Add Python to Path`

2. Open `command prompt` by winkey/search > cmd

3. Type `pip3 install manga-ocr`
    - Then just let it download/install for a few mins until its done and you can type again
    - If `pip3 is not recognized...` then just `uninstall Python` > `restart` > `install Python` (repeat if it didn't work)

4. Either Type `manga_ocr` or `manga_ocr "\path\to\sharex\screenshot\folder"`(OCR from a folder only) to start the program, then just minimize the window
    - If you want a `shortcut` program see: [Info 1](https://xelieu.github.io/jp-lazy-guide/jp-lazy-guide/setupMangaOnPC/#info-1-mangaocr-shortcut-program)

5. Capture anything using `Shift + Alt + Q` or whatever you set in `OCR (manga_ocr)` hotkey in `ShareX`
    - Make sure Yomichan Search window is opened
    - If you want to `scan using mouse button`, see [Info 2](https://xelieu.github.io/jp-lazy-guide/jp-lazy-guide/setupMangaOnPC/#info-2-scan-using-mouse-button)

??? info "Video How-to"
    <iframe width="560" height="315" src="https://user-images.githubusercontent.com/22717958/150238361-052b95d1-0152-485f-a441-48a957536239.mp4" title="MangaOCR How-to" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

=== "Yomichan Search Page"
    ![Anki | Dark](../img/yomichan-search-page.png){height=300 width=600}
=== "CDisplay Manga"
    ![Anki | Light](../img/cdisplay-manga.png){height=300 width=600}

That's it for MangaOCR!

---

## Setup: Mokuro Manga


You can now mine Manga on PC, see how its done in Android!

[Proceed to Manga on Android Setup](setupMangaOnAndroid.md){ .md-button .md-button }

---

## Extra Info and Tips

#### Info 1: MangaOCR Shortcut Program

??? info "MangaOCR Shortcut Program <small>(click here)</small>"
    1. `Right click` in an empty space in your `Desktop` > `New` > `Shortcut`

        ![MangaOCR Shortcut](../img/mangaocr-shortcut.png){height=300 width=600}

    2. Type the location of the item as:
        - Default: `C:\Windows\System32\cmd.exe /k manga_ocr`
        - OCR only from specific folder: `C:\Windows\System32\cmd.exe /k manga_ocr "\path\to\the\screenshot\folder"`
            - For example: `C:\Windows\System32\cmd.exe /k manga_ocr "F:\Pictures\OCR Picture"`
            - `Next` then `choose your name` and done

#### Info 2: Scan using Mouse Button

??? info "Scan using Mouse Button <small>(click here)</small>"
    1. Download and install [AutoHotkey](https://www.autohotkey.com/)

    2. Download my [Hotkey](https://drive.google.com/drive/folders/1bIgKmWubUvipRyymsvhvLCtoQYSUD1q3?usp=sharing) then run it

    3. Use `Forward Button` to use it
        - This is assuming the `OCR (manga_ocr)` hotkey in `ShareX` is unchanged from `Shift + Alt + Q`
        - You can edit the hotkey by editing the script if you like