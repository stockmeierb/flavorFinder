# flavorFinder
React-Native learning project to query MTG database for text and images and share across devices

About: This is intended to be a practice project/playground where I will learn react-native and create a project that will query a database of the trading card game Magic the Gathering for card art and "flavor" text via a publicly available api. The use of this application is intended to be for the benefit of Dungeon Masters running Dungeons and Dragons or similar creative tabletop roleplaying games who wish to illustrate their games or borrow quotes to enhance gameplay.

MVP Functionality: Upon entering the app, the user will encounter a search box with an option to search for either text or artwork. They will enter their terms (example: "minotaur") and will then be brought to a results page which will list the search results. They will be able to select an image and "share it" any number of ways, via sending it through text message or via an outside app like Discord, or just downloading it to your photos. Text can also be shared, or copied to a ciipboard and pasted whereever desired.

Final Product: MVP, but ideally will also allow users to narrow their search criteria to things like a card's "name" or "type". The search results will also be tabbed to organize results (hits coming from the card name will be separated from hits coming from the card type, or text). When viewing results, you'll be able to select and temporarily "save" images and text during the session to prevent losing track of them. You can edit text in the app directly before sharing it. Duplicate search results will not be shown.

Spikes:
- What is the best publicly available API for querying a MTG database today? (Scryfall?)