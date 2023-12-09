# Setup: VN on Android

- You can play `Visual Novel` using an `Android` device running `Steam Link`
- Your `PC` must be running as the `Android` device will stream from your `PC`
- It still has all the features just as if you were in your `PC`

---

## Requirements

For `PC`:

- Running `Anki`, `Steam` and `Texthooker` page

For `Android`:

- Install and Run [Steam Link](https://play.google.com/store/apps/details?id=com.valvesoftware.steamlink&hl=en_US)

!!! info "Note"

    `Visual Novel` doesn't have to be a steam game and `Steam Link` can run basically any games

---

## Setting Up

1. In your `PC`, open your `Steam Settings` > `Controller` > `Desktop Configuration`
    - You must have your `Steam Link` connected and opened in your android while doing this on your PC

    ![Steam Settings](../img/steam-settings.png){height=250 width=500}

2. Customize your `M1-M8` with whatever keybinds you like for your mining or whatever like ShareX e.g. `alt + shift + C`

    ![Steam Controller Settings](../img/steam-controller-settings.png){height=500 width=1000}

3. In your `Android`, open `Steam Link` > `Settings` > `Streaming` > `2nd page` > `Launch Mode` > `Desktop` (to disable Big Picture)

    ![Steam Link Settings](../img/steam-link-settings.png){height=500 width=1000}

4. Use `Steam link` > `shake your android`(if icon is not there) > open the `top left icon` > `Touch Controller` ENABLED > `Layout Controls` > add your macros wherever, erase controller buttons as you won't need them

    ![Steam Link Macros](../img/steam-link-macros.png){height=500 width=1000}

5. Use `Mouse Trackpad` not direct cursor (or you can't switch monitor)

    ![Steam Link Mouse](../img/steam-link-mouse.png){height=500 width=1000}

6. Launch your VN

!!! danger "Note"

    Make sure `Big Picture` is not disabled/selected from step 3 and that you launch your `Visual Novel` out of steam, or else controller layout will not work

---

## Yomitan Configuration

1. On `PC`, [Texthooker 5.2.0](https://drive.google.com/drive/folders/1oHdD3DL8BqAxEEvUoSK-ow8snK6_Qn6y?usp=sharing) folder, open `texthooker - android` page

2. In your `texthooker - android` page, copy the `URL`

    ![Texthooker URL](../img/texthooker-url.png){height=250 width=500}

3. On `PC`, open `Yomitan Settings` > `Profile` > `Configure Profiles...` > `Android (VN)` > `Options` > `Edit conditions...`

    ![Yomitan Profile Option](../img/yomitan-profile-option.png){height=250 width=500}

4. Set it to `If URL` and `Matches RegExp` and paste the `URL` on the `3rd box` from `step 2`

    ![Yomitan Profile Condition](../img/yomitan-profile-condition.png){height=250 width=500}

---

## Mining VN on Android

1. `Drag your mouse` out of your screen to where your 2nd monitor

2. `TAP` your screen to switch monitor

3. `Add Yomitan` word like usual

4. `Use the macros` that you've set for screenshot/audio (`ShareX`)

!!! info "Note"

    If you only have 1 monitor, customize your `Steam Controller Settings` > `M1-M8` and put a `alt-tab` macro

Macros on my Steam Link:

![Steam Link Macros 2](../img/steam-link-macros-2.png){height=500 width=1000}

Yomitan on my Android:

![VN on Android Yomitan](../img/vn-android-yomitan.png){height=500 width=1000}



You now mine VN on Android, why not check out Mining Light Novel on PC?

[Proceed to LN on PC Setup](setupLnOnPC.md){ .md-button .md-button }

<small>If you have any problems check [FAQs](https://xelieu.github.io/jp-lazy-guide/setupVnOnAndroid/#faqs) or contact me on Discord: [xelieu](https://www.discordapp.com/users/719459399168426054)</small>

---

## Extra Info and Tips

#### Tip 1: Zoom in your `texthooker - android` page

??? tip "Zoom in your texthooker - android page <small>(click here)</small>"

    - If it's not big enough for you, on your `PC` > `texthooker - android` page, Zoom in with `Ctrl + Mouse Scroll Wheel` to the `%` that you like

## FAQs

#### Question 1: How to use Monolingual Setup?

??? question "How to use Monolingual Setup? <small>(click here)</small>"

    1. In your `PC`, go to `Yomitan` settings > `Profile (Editing)` > `Android (VN)`
    
    2. `Yomitan` settings > `Dictionary` > Enable `all`

        ![Dictionary Toggle](../img/dictionary-toggle.png){height=250 width=500}

    3. `Yomitan` settings > `Anki` > `Configure Anki card templates...`
        - Switch the `highlighted text` to `monolingual` (case-sensitive)

        ![Dictionary Toggle](../img/switch-to-mono.png){height=250 width=500}
