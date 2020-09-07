# StatsFlashcards

## About

Created for studying for my OSU grad stats comps. For the Theory and Methods sequences.

Feel free to open issues with mistakes/spelling/suggestions - please include the card number - the ID field.

## How to use

## Set up Anki

These flashcards are intended to use with the free Anki software https://apps.ankiweb.net

The desktop version is needed to open a .tex document, and requires a local LaTeX installation. You can then sync the flashcards with Ankiweb https://ankiweb.net after creating an account, which can be accessed on web or mobile devices (iOS app costs, but accessing via mobile browser works great for me).

The pdf files have an overview of all the flashcards, but are not intended to be used to study

Choose one of the following Options to import the deck.

## Option 1
Option 1 is the easiest way and doesn't require a local TeX installation. However, I don't keep this files as up-to-date as the .tex file option described below. To follow this option, download the StatsFlashcards.apkg file and click "Import File" at the bottom of anki and select this file. This should import all theory and methods flashcards.

## Option 2 - import using TeX files

Make sure to install the latex importer add on before trying to import .tex files. https://ankiweb.net/shared/info/1199027445. Go to Tools > Get Add ons > Get Add ons, and paste the code found on the website.


### Make new note type

Anki doesn't do a great job of tracking changes and updating notes with new imports. To fix this, we need to create a new note type that includes a unique ID

Go to Tools > Manage Note Types > Add > Select Add:Basic
 and name it something like Basic-uniqueID
 Then select it and click "Fields" > Add > name it ID > Reposition, and move the id field to the top.

 Save your new card type. Now make sure to always import using this note type so that updates can match correctly.


### My workflow to use these flashcards:
- Make sure the latex header matches the document: Go Tools>Manage Note Types> Options, and paste the correct latex header in the Header section
- Import the .tex flashcard file from the main screen by clicking Import file
- Make sure the "Deck" selected is the one intended to import to - You can either select or add a deck at this time
- Make sure the Note type is the Basic-ID type you created above
- Make sure all LaTeX has been rendered by Tools>Check Media... Click Render LaTeX
- Click Sync
- You should be able to access these flashcards anywhere!
