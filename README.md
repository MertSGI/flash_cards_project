
# Flashcards Manager 🃏

This Flashcards Manager is a Python program designed to help you create, manage, and test flashcards interactively. It's ideal for improving memory and learning through repetition.

---

## 🚀 Features

- **Add Cards**: Add new flashcards with terms and definitions.
- **Remove Cards**: Remove existing flashcards.
- **Import and Export Cards**:
  - Import flashcards from a file.
  - Export flashcards to a file for saving progress.
- **Quiz Yourself**: Test your knowledge using the flashcards.
- **View Hardest Cards**: Identify cards with the most incorrect answers.
- **Reset Statistics**: Reset error statistics for all cards.
- **Activity Log**: Save input and output to a log file for review.

---

## 🛠️ How to Use

1. **Run the Program**  
   Execute the script using Python:
   ```bash
   python flash_cards.py
   ```

2. **Commands**  
   The program provides the following commands:
   ```
   add, remove, import, export, ask, log, hardest card, reset stats, exit
   ```

3. **File Import and Export**  
   You can pass file arguments when starting the script:
   - `--import_from=<file>`: Automatically load flashcards from a specified file.
   - `--export_to=<file>`: Automatically save flashcards to a specified file upon exit.

---

## 📖 Example Usage

### Adding Cards
```
Input the action (add, remove, ...): add
The card:
> Capital of France
The definition for card:
> Paris
The pair ("Capital of France":"Paris") has been added.
```

### Testing Knowledge
```
Input the action (ask, ...): ask
How many times to ask?
> 1
Print the definition of "Capital of France":
> Paris
Correct!
```

---

## 📂 Project Structure

```
flash_cards_project/
├── flash_cards.py    # Main Python script
├── README.md         # Documentation
```

---

## 🛠️ Requirements

- Python 3.x

---

## 📬 Contributing

Contributions are welcome! If you find any issues or have ideas for new features, feel free to create an issue or submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

### Thank you for using the Flashcards Manager! 😊
