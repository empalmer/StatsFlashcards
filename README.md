# StatsFlashcards

## About

Created for studying for my OSU grad stats comps

Feel free to open issues with mistakes/spelling/suggestions - please include the card number - the ID field.

Two folders are Methods and Theory, for the first year year-long sequences. Each has several .tex files corresponding to the topic the flashcards cover (which correspond to tags in anki). To have a full deck of flashcards, import each file separately, or import the Theory_flashcards file to import all at once. (Note this conversion of 1 file overall to multiple separate files corresponding to different tags is in progress). I've been having some glitches with tags, so they might have to be

These flashcards are intended to use with the free Anki software https://apps.ankiweb.net

The desktop version is needed to open a .tex document, and requires a local LaTeX installation. You can then sync the flashcards with Ankiweb https://ankiweb.net after creating an account, which can be accessed on web or mobile devices (iOS app costs, but accessing via mobile browser works great for me).

The pdf files have an overview of all the flashcards, but are not intended to be used to study

Make sure to install the latex importer add on before trying to import .tex files. https://ankiweb.net/shared/info/1199027445. Go to Tools > Get Add ons > Get Add ons, and paste the code found on the website.

## Support for updating flashcards
Anki doesn't do a great job of tracking changes and updating notes with new imports.
Go to Tools > Manage Note Types > Add > Select Add:Basic
 and name it something like Basic-uniqueID
 Then select it and click "Fields" > Add > name it ID > Reposition, and move the id field to the top.

 Save your new card type. Now make sure to always import using this note type so that updates can match correctly.


## My workflow to use these flashcards:
- Make sure the latex header matches the document: Go Tools>Manage Note Types> Options, and paste the correct latex header in the Header section
- Import the .tex flashcard file from the main screen by clicking Import file
- Make sure the "Deck" selected is the one intended to import to - You can either select or add a deck at this time
- Make sure the Note type is the Basic-ID type you created above
- Make sure all LaTeX has been rendered by Tools>Check Media... Click Render LaTeX
- Click Sync
- You should be able to access these flashcards anywhere!



## In progress flashcards
### Theory
 - Theory 3
 - Useful math facts
 - Distribution relationships

### Methods
 - Methods 3

## If you want to study a specific topic (eg Distribution Relationships)
 - On desktop version, click on deck
 - At bottom, click Custom Study
 - Click Select by card state or tag > Choose Tags
 - Select tag of interest
 - This will create a new deck with only the flashcards of interest

## Current Files/tags/topics available

### Theory
 - File: Theory1.tex tag: Theory1
 - File: Theory2.tex tag: Theory2
 - Distribution Relationships (distributionrelationshps)
 - File: Calculus.tex tag: Calculus
 - From online stats cheatsheet (FromStatCheatsheet)
 - From my undergraduate probability textbook

### Methods

- Methods_flashcards.tex (Contains Methods1 and Methods2 tags)(working on splitting this into two files)
