# Faerie Solitaire Harvest Localization

This is the community translation project for Faerie Solitaire Harvest. We want to translate our games to as many languages as possible so that as many people in the world can enjoy our games. Many people have asked to help us translate our games so we are trying to make it easier to contribute to any language. We are a commercial company and we do invest money into paying for translations but it can also be incredibly expensive so naturally we prioritize the largest languages. If we could afford to pay for every language to be done professionally we would but we are also a small, independent company so rely on our friends and community to help.

We have a Discord server you can join if you own FSH and look at the About screen. There is a translation channel there as well as langauge specific chat rooms.

We translate store page text and game text. For game text there is general text and bulk text. General text includes things like text that goes on buttons, help screen text. Bulk text includes things such as character dialog, cutscenes, lore. Bulk text can be very large such as up to 20,000 words or more! Obviously by reading this text you could be exposed to spoilers and secrets better experienced first time through gameplay so beware. Currently we are not including much of the bulk text, only mostly core game text for now.

We put any professional translation done into this git too. Even pros can make mistakes. You might find issues in the English text too and corrections for it are also accepted. It's possible keys have embarrassing typos that we have not noticed yet too!

Sometimes new text is added for other languages. This missing text will show up as !KEY_NAME! (or English depending on settings) in game until it has been translated into whatever language the user is using. We also get analytics data for missing keys to help remind us what needs to be updated.

If you are a contributor, you may want to watch this git and look for English changes to know when to contribute changes or additions to whatever language you are maintaining.

Ideally we want to support as many languages as possible. The languages we have are not the only ones we want to add. If there is a language you want added but cannot add yourself please make an issue for it, or +1 as a comment if an issue for it already exists.

We want to follow what local gamers expect. This may mean not actually translating everything from English to Japanese for example where Japanese gamers expect certain things to be in English.

If you have any questions such as asking about context of text or what word should be used please make an issue.

# How to contribute: 

You will need a GitHub account to contribute. Some basic git knowledge may be necessary. If you're new to git you can use the github desktop client to make it somewhat easier. https://desktop.github.com/

Text is first done in English and then translated into other languages. People who are gamers themselves and native speakers of the target language should be the only ones doing translations. The spirit of the text should not be changed ever, but localization does sometimes require changes. All text should follow US law at a minimum. If text offends people it should not be changed to be less offensive without first discussing the matter in an issue. If you have questions about specific text you can open an issue about it. If you are native speaker and notice an issue in the text but do not wish to help edit you can create an issue about the text problem.

As an example of what we don't want, if text says "cheeseburger" we don't want that to be localized to "sushi" it should be translated as well as it can to describe whatever the original thing is. You should also never make up new text. If the meaning of the English and a target language for something is radically different then that is bad. If characters are completely different in English vs a target language then that is bad.

If font glyphs for your target language are not available in game please create an issue.

Currently RTL languages (Hebrew, Arabic, Farsi) are not supported but may be supported in the future.

# File Encoding and Line Endings

Make sure file encoding is UTF-8 without BOM

![encoding](https://user-images.githubusercontent.com/409170/57166969-c9462580-6db0-11e9-9e38-f48f4720f9ae.png)

Make sure line ending style is Unix

![line-ending](https://user-images.githubusercontent.com/409170/57166970-c9462580-6db0-11e9-8c1a-16df1ee6754a.png)

These can be set with many text editing programs such as Notepad++.

# How to add a new language:

Clone the git, copy and paste the en-us folder, and then edit its related files to the proper LCID string key (always lowercase). Here is a reference: http://wiki.freepascal.org/Language_Codes We're not strict on this though so if you think a better code would work go for it for example we use cz-hanz for Simplified Chinese and cz-hant for Traditional Chinese. We also use the country code (JP) for Japanese instead of its language code (JA).

If you want to edit a new langauge on the web interface only make an issue asking about it and we'll setup the folders and files for you.

Before you jump on a new langauge please make sure there is no other recent issue by anyone else saying they are starting on that language, otherwise please create an issue saying that just so others can see.

We probably don't need other versions of English but if you want to add one which is colour instead of color go for it.

Changes to the English (en-us) text will be made over time. Adding new strings or modifying existing strings to reflect changes in English version must be done manually. If the game does not find strings it is looking for in a language other than English it will select the English version instead.

(TODO: add game localization file setup instructions.)

(TODO: add commonly asked questions doc.)

(TODO: add term definitions doc.)

# Required legal message: 

By contributing to this project, you are giving exclusive rights and ownership of all text contributed to Subsoap for Subsoap to use in their games or marketing or for whatever reason they wish to use the text for. The text being available here does not mean it can be used by any other parties for commercial usage. Permission is granted to contributors to modify the text and contribute changes / additions. Contributions may or may not be accepted. While credit is generally given to people who contribute, it is up to Subsoap to add credits in game or not.



