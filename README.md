# Day_31-Flash-card-app-Capstone_project-
A Flash Card Language app built using Python and tkinter.

This projects helps users learn French vocabulary by displaying flashcards that show a French word first, then automatically flips after a few seconds to reveal the English translation. The app also tracks progress, allowing users to tick words they got right and 'X' words they couldn't remember.


## How the Code / Project Works:
- The app loads vocabulary data from a CSV file using pandas
- If a “words to learn” file exists, it uses that to track progress otherwise, it   starts with the full dataset
- A random word is selected and displayed on a flashcard
- After 3 seconds, the card flips automatically to show the translation
- Users can interact with two buttons:
    ❌ Unknown → moves to the next word
    ✅ Known → removes the word from the learning list
- The app updates progress by removing known words and saving the remaining words   back into a CSV file
- A canvas widget is used to:
    Display card images (front and back)
    Overlay text for words and translations


## What I Learned:
- Advanced use of pandas {Converting data into dictionaries, Saving progress by     writing updated data to CSV}
Working with Tkinter Canvas:
  Displaying and switching between images
  Overlaying dynamic text on images
- Using timers in GUI apps
- Using window.after() to delay actions (card flipping)
- Combining UI, logic, and data persistence into one cohesive app


This capstone project brought together everything I’ve learned so far — from GUI design to data handling.
