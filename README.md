# 🇩🇪 German Vocabulary Flashcard App

An interactive flashcard application built with Python to help users effectively memorize German vocabulary through timed recall and active repetition.

## 📝 Description

This flashcard app is designed to support learners in building their German vocabulary. The app displays a German word on-screen, and after a 3-second delay, its English translation is revealed. Users then self-assess their recall by clicking ✅ (correct) or ❌ (incorrect).

- If the user clicks **✅**, the word is considered "learned" and is permanently removed from the dataset.  
- If the user clicks **❌**, the word remains in the rotation and will appear again later, reinforcing learning through repetition.

This method encourages focused learning by ensuring that only unmastered vocabulary is repeated.

## ⚙️ Features

- Timed card flipping: German word shown first, then English revealed after 3 seconds
- Self-evaluation with ✅ and ❌ buttons
- Words marked correct are automatically removed from the learning list
- Only unlearned words continue to appear
- Clean and intuitive interface using Tkinter
- Data persistence through CSV file updates

## 📂 Technologies Used

- **Python 3**
- **Tkinter** – for the graphical interface
- **Pandas** – for handling the vocabulary dataset
- **CSV** – for storing and updating word lists
