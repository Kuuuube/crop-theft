# Yomitan Setup

You must have the [Ankiconnect](https://ankiweb.net/shared/info/2055492159) add-on installed in Anki to use Anki integration in Yomitan. Anki must also be running on your computer.

For android users, setting up [Ankiconnect Android](https://github.com/KamWithK/AnkiconnectAndroid/releases) is more complex. I recommend [Jidoujisho](https://github.com/arianneorpilla/jidoujisho/releases) for most use cases.

1. Open the Yomitan settings page. (Click the Yomitan icon and then the cog symbol)

2. Go to the `Anki` section of settings.

3. Enable `Enable Anki integration`.

4. Click `Configure Anki flashcards...`

5. Make sure you have the `Expression` tab selected.

    Optionally, you can repeat the below steps for the `Reading` tab. Just put `{reading}` for the first field instead of `{expression}`.

6. Select the desired deck and select `Crop Theft Vocab` for the model.

7. Copy and paste each item in the Yomitan column from [field setup](../../README.md#field-setup) into the `Value` section in Yomitan.

8. You will now be able to add a card to Anki by clicking the larger green plus button ![](../images/yomitan_add_button.svg) when scanning a word.
