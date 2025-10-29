# About
This is an open source repository for translations for Node games by ByerN: https://store.steampowered.com/app/3648370/Node_Math/

# Contribution Guidelines

Thank you for helping translate the game!

By submitting your translation to this project, you confirm that:
- you are the author of your contribution or have the right to share it,
- you agree to release your translation under the **Apache License 2.0**,
- you understand that your translation may be used in the game and in materials related to it (both commercial and non-commercial).

This ensures that everyone - including the game's author - can safely use and distribute your translations.

# How to join community-driven translations?
- create and activate your GitHub account,
- send me a private message with your GitHub username (or email used for registration) on the Discord server: https://discord.com/invite/sfgr7YCv2z
- when I get a message, I will accept you as a contributor,
- now you can edit files and create new ones.

# How to add a new translation?
- open a directory with game translations, for example Node Math: <img width="1390" height="573" alt="image" src="https://github.com/user-attachments/assets/3bd8ffd3-8cea-4144-87ac-f640e02665ef" />
- click create new file <img width="1402" height="516" alt="image" src="https://github.com/user-attachments/assets/8b25fdb8-5375-4e2c-ab97-542d113dd866" />
- add a file name (for example "chinese.txt"), add the content of translations, and click "Commit changes..." <img width="1419" height="712" alt="image" src="https://github.com/user-attachments/assets/b4c9175b-4ca4-42dd-99fa-3ae6d7a56aab" />
- to simplify the process, you just click "Commit changes" in the next step <img width="709" height="738" alt="image" src="https://github.com/user-attachments/assets/dfdbd1d5-c4ba-4f2a-804b-4d64745d3804" />
- after this, you should see your file here: <img width="1424" height="581" alt="image" src="https://github.com/user-attachments/assets/4adef084-8b9f-4e48-885b-2d9b8c430448" />
- last thing is to update "translations-config.txt"

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

Also, there are the following fonts available in the game (let me know if you see your language missing with a different alphabet):
- any Latin-based alphabet: Lato-Bold.ttf
- Arabic: NotoSansArabic-Bold.ttf
- Japanese: NotoSansJP-Bold.otf
- Chinese: NotoSansSC-Bold.otf

(Any new fonts will probably be from the Nato Sans family as well)

How to edit the config file:
- click on the config file <img width="1419" height="595" alt="image" src="https://github.com/user-attachments/assets/f8fffa78-2890-44a8-8769-1991afe15d52" />
- click edit file <img width="1409" height="299" alt="image" src="https://github.com/user-attachments/assets/524eeb0b-01ee-4b38-bd49-7ac89dea3be4" />
- edit file and commit changes <img width="1369" height="351" alt="image" src="https://github.com/user-attachments/assets/b0c2cd76-ceb0-45fc-b866-2bbc972a0340" />
- accept commit <img width="705" height="736" alt="image" src="https://github.com/user-attachments/assets/1a2f3cd4-13b4-439b-a49f-4c10326db026" />
- done. Now you can ping me on Discord so I can check if everything is ok and upload it into the game :)

# How to test your changes in the game?
You can edit both the translation files and the config file in the game. Fonts are in the "fonts" folder.
