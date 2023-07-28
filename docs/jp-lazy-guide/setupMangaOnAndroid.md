# Setup: Manga on Android

- You can use your `Android` to read `Manga` using `Kiwi Browser` to scan words using `Yomichan` on it

- This includes automated `Manga` screenshot even if you are in `Android`

---

## Download and Install

- Download and Install [Ankiconnect Android](https://github.com/KamWithK/AnkiconnectAndroid/releases/latest) and [Local File Server](https://github.com/Aquafina-water-bottle/LocalFileServerAndroid/releases/latest) in Assets `.apk` file

- Install [Ankidroid](https://play.google.com/store/apps/details?id=com.ichi2.anki)

- Install [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=en_US)

Requirements:

- Processed Manga from [Setup: Mokuro Manga](https://xelieu.github.io/jp-lazy-guide/setupMangaOnPC/#setup-mokuro-manga)

- [Yomichan On Android](https://xelieu.github.io/jp-lazy-guide/setupYomichanOnAndroid/) already set-up

---

## Setting Up

1. Transfer your `Processed Manga` in `~/Android/data/com.rayrtheii.localfileserver/files/`

2. Open `Ankiconnect Android` > `settings` > `CORS Host` > `http://localhost:8976`

    ![CORS Host](../img/cors-host.png){height=200 width=400}

3. `Start the Service` on both `AnkiConnect Android` and `Local File Server`

4. Open your `Kiwi Browser` > http://localhost:8976/browse > Manga's `.html` file

    ![Manga Android HTML File](../img/android-html-file.png){height=150 width=300}

5. Go to `settings` > `advanced settings` then copy this:

    ![Manga Android HTML File](../img/android-mokuro-settings.png){height=500 width=1000}

    - Uncheck the `show page number` so it doesn't get included on mining

6. You can now mine with `Yomichan`, don't forget to click the blue `●` after the `+` to be able to `screenshot`
    
    - See [Android Mining Demo](https://xelieu.github.io/jp-lazy-guide/setupMangaOnAndroid/#info-1-android-mining-demo)


You are now finally done in setting up Manga Mining in Android, how about checking out Anime Mining?

[Proceed to Setup: Anime on PC Setup](setupAnimeOnPC.md){ .md-button .md-button }

<small>If you have any problems check [FAQs](https://xelieu.github.io/jp-lazy-guide/setupMangaOnAndroid/#faqs) or contact me on Discord: [xelieu](https://www.discordapp.com/users/719459399168426054)</small>

---

## Extra Info and Tips

#### Info 1: Android Mining Demo

??? info "Android Mining Demo <small>(click here)</small>"

    - Mining Demo with Manga screenshot

    ![Android Manga Mining](../img/android-manga-mining.gif){height=200 width=400}s

#### Tip 1: Export your Settings

??? tip "Export your settings <small>(click here)</small>"

    - `Export your settings` as every time you have new manga/volume you need to re-import the settings

## FAQs

#### Question 1: How to use Monolingual Setup on Android?

??? question "How to use Monolingual Setup on Android? <small>(click here)</small>"

    1. Go to your `Yomichan` settings > `Dictionary` > Enable `all`

        ![Dictionary Toggle](../img/dictionary-toggle.png){height=250 width=500}

    2. `Yomichan` settings > `Anki` > `Configure Anki card templates...`
        - Switch the `highlighted text` to `monolingual` (case-sensitive)

        ![Dictionary Toggle](../img/switch-to-mono.png){height=250 width=500}