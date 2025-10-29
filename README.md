# node-games-localisation
This is an open source repository for translations for Node games by ByerN

# How to edit translations-config.txt
If you want a new translation to be listed in the game, you have to edit "translations-config.txt" configuration file.

It may look like this:
```
eng,english,Lato-Bold.ttf
pol,polish,Lato-Bold.ttf
```

- First column - ISO language code (3 letters) https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes
- Second column - translations file name (without .txt extension)
- Third column - font.

I had to hardcode some ISO language codes with special settings as they didn't display properly. Affected languages are:
- jpn - Japanese
- zho - Simplified Chinese
- ara - Arabic
- rus - Russian
- ukr - Ukrainian

# Contribution
By contribution, you agree to the Apache-2.0 license.
