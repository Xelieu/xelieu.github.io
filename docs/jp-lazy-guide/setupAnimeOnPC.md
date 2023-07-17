# Setup: Anime on PC

- `asbplayer` is a browser video player that supports uploading of `Anime` and `subtitle` to be able hover over the words to use `Yomichan`

---

## Download and Install

- Download your `Anime` and `JP Subtitle`
    - To get `JP subtitles` go to [kitsunekko](https://kitsunekko.net/dirlist.php?dir=subtitles%2Fjapanese%2F)

Requirements

- [Yomichan on PC](https://xelieu.github.io/jp-lazy-guide/setupYomichanOnPC/) and [ShareX](https://xelieu.github.io/jp-lazy-guide/setupShareX/) already set-up

---

## Setting Up

1. In your browser, go to `chrome://flags` or `edge://flags`
    - Search for `Experimental Web Platform features` > `Enabled`

    ![Enable Experimental Web Platform](../img/enable-experimental-web-platform.png){height=300 width=600}

2. Go to [asbplayer](https://killergerbah.github.io/asbplayer/)
    - Ignore `request permission` to `Anki` and installing of `Chrome extension`

3. Upload your `Anime` and `Subtitle` to the `asbplayer`

    ![Pick Anime & Subtitle](../img/pick-anime-sub.png){height=300 width=600}

4. You can now mine with `Yomichan` and [ShareX](https://xelieu.github.io/jp-lazy-guide/setupShareX/)'s `screenshot` and `audio recording` hotkeys
    - See [Anime Mining Demo](https://xelieu.github.io/jp-lazy-guide/setupAnimeOnPC/#info-1-anime-mining-demo)



You can now mine Anime on PC, why not do it on Android too? (RIP eyes)

[Proceed to Setup: Anime on Android Setup](setupAnimeOnAndroid.md){ .md-button .md-button }

---

## Extra Info and Tips

#### Info 1: Anime Mining Demo

??? info "Anime Mining Demo <small>(click here)</small>"

    <iframe width="560" height="315" src="https://www.youtube.com/embed/CujTp1DxbtM" title="Mining Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

#### Tip 1: Synchronizing Subtitle

??? tip "Synchronizing Subtitle <small>(click here)</small>"

    Depending on the source of your `Anime`, the `Subtitle` could be out of sync, to remedy that problem:

    - +100ms - `CTRL + SHIFT + LEFT ARROW KEY`

    - -100ms - `CTRL + SHIFT + RIGHT ARROW KEY`

#### Tip 2: Skip Audio Recording when Mining

??? tip "Skip Audio Recording when Mining <small>(click here)</small>"

    - You can skip the audio recording when mining as it is time consuming

    - If you also manage to do your Anki Cards below 5s each, you will barely hear the recorded Audio

---

## FAQs

#### Question 1: Why Enable Experimental Web Platform features?

??? question "Why Enable Experimental Web Platform features? <small>(click here)</small>"

    - Some `Anime` have multiple `audio sources` such as `en` and `jp`, by enabling this we can pick `jp` source if its not the default

#### Question 2: Why Ignore Request Permission to Anki?

??? question "Why Ignore Request Permission to Anki? <small>(click here)</small>"

    - Because we are using the normal method where we can use the full features of `Anki` and `Yomichan` setup

#### Question 3: Why not install the Chrome Extension?

??? question "Why not install the Chrome Extension? <small>(click here)</small>"

    - Same as `Question 1`, `asbplayer` has a built-in `Anki` support that lacks the feature of our own `Anki` and `Yomichan` support