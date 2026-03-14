# 📝 Word Counter App

A clean and lightweight web app that instantly analyzes your text
and gives you a real-time breakdown of characters, words, and sentences
as you type.

---

## 🚀 Live Demo

🔗 https://musical-marshmallow-9a53e0.netlify.app/

---

## ✨ Features

- **Character Count** — Counts every character in your text (excluding leading/trailing spaces)
- **Word Count** — Detects and counts all words, ignoring extra whitespace
- **Sentence Count** — Splits text by `.` `!` `?` to count total sentences accurately
- **Real-time Updates** — All counts update instantly on every keystroke, no button needed

---

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript (DOM Events, Regex)

---

## 📂 Project Structure
```
word-counter/
│
├── index.html     # App structure and layout
├── style.css      # Styling and card design
└── script.js      # Core logic for counting characters, words, sentences
```

---

## ⚙️ How It Works

1. User types inside the textarea
2. The `input` event fires on every keystroke
3. JavaScript reads the textarea value and:
   - Measures `.length` for character count
   - Splits by whitespace regex `/\s+/` for word count
   - Splits by punctuation regex `/[.!?]+/` for sentence count
4. All three counts update live in the UI

---

## 📌 What I Learned

- DOM selection and event listeners
- Using regular expressions (Regex) for text analysis
- Real-time UI updates without any framework
- Debugging case-sensitive ID mismatches in HTML & JS

---

## 👤 Author

**Ferdous Ali**
Part of my #30DaysOfJavaScript challenge — Day 16
