# 41_project03_10hours# 41_project03_10hours

## ✨ Project Overview
This solo project consists of three command-line Node.js applications:

1. **Rock Paper Scissors** – A terminal game where you play against the computer.
2. **Pig Latin Translator** – Translates English phrases to Pig Latin based on simple linguistic rules.
3. **Caesar Cipher** – Encrypts a phrase using the Caesar cipher method with positive or negative shifts.

---

## 📆 Duration
- **Full Time**: 5 Days  

---

## 🚀 Requirements Summary
### FR001 – Solo Project
You must work independently. Collaboration is not allowed.

### FR002 – Public GitHub Repository
- Keep the repository public.
- Do not add instructors as collaborators.

### FR003 – Incremental Development
- All updates to the `main` branch must be done via Pull Requests only.

### FR004 – Presentation
- Present the code to your peers and instructor.
- Walk through your code **line by line**.

### FR005 – Rock Paper Scissors
- Input: `process.argv` (e.g., `node rockPaperScissors.js rock`)
- The computer randomly selects rock, paper, or scissors
- Output result: win, lose, or draw

### FR006 – Pig Latin Translator
- Input: `process.argv` (e.g., `node pigLatin.js "Pig Latin is fun"`)
- Converts each word based on rules:
  - Starts with vowel → add "way"
  - Starts with consonant + vowel → move first letter to end + "ay"
  - Starts with 2 consonants → move both to end + "ay"

### FR007 – Caesar Cipher
- Input: Phrase + Shift value from `process.argv`
- Output: Encrypted phrase
- Supports positive (right shift) and negative (left shift) values

---

## 📊 File Structure
41_project03_10hours/
├── rockPaperScissors.js
├── pigLatin.js
├── caesarCipher.js
└── README.md

---

## 🔧 How to Run Each Program
node rockPaperScissors.js rock
node pigLatin.js "This is fun"
node caesarCipher.js "hello world" 3

---

🎤 Final Presentation
You will be expected to:
	•	Present each program
	•	Walk through code line-by-line
	•	Explain your logic, structure, and decisions

---

📚 License
This project is created as part of WBS Coding School curriculum.

---

💬 Questions?
Open an issue on this repo if you have questions, or talk to your instructor during check-ins! Let me know if you’d like a version with Markdown preview styling or emojis trimmed!
