# 👑 Topper promax — Internal Marks & Scoreboard Tracker

**Topper promax** is a dynamic web application built for students and faculty of **Sathyabama University** to evaluate, record, and rank CAE internal marks in real time. Based on standard internal evaluation logic, the app automatically processes scores across multiple core subjects and ranks participants on a dynamic leaderboard.

---

## ✨ Features

- 📊 **Real-time Marks Calculation**: Converts raw marks (out of 50) into internal CAE scores (out of 20) using the university formula:
  $$\text{Internal Score} = (\text{Subject Marks} \times 2) \times 0.2$$
- 🏆 **Interactive Leaderboard**: Automatically ranks records based on total aggregate score (out of 100).
- 🎉 **Topper Celebration Animations**: Triggers festive confetti explosions and sound effects when students achieve top marks or break high score records.
- 🔐 **Host Password Protection**:
  - Requires host password authorization (`Roni@15`) to delete individual entries or clear the entire scoreboard.
- 💾 **Local Persistence**: Saves all records locally in the browser (`localStorage`), preserving data across sessions.
- 📱 **Fully Responsive UI**: Built with Tailwind CSS and dark-mode aesthetic for mobile and desktop screens.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS
- **Icons**: Font Awesome 6
- **Animations & FX**: Canvas Confetti API, Web Audio API
- **Logic**: Native JavaScript (ES6)

---

## 🚀 Quick Start & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/topper-promax.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd topper-promax
   ```
3. **Run the Application:**
   Open `index.html` directly in any standard browser or use a live server extension in VS Code.

---

## 🔒 Security & Authorization

| Action | Permission Required |
| :--- | :--- |
| **Add Marks Record** | Anyone |
| **Live Score Preview** | Anyone |
| **Delete Single Entry** | Host Password (`Roni@15`) |
| **Clear Entire Scoreboard** | Host Password (`Roni@15`) |

---

## 📁 Repository Structure

```text
├── index.html        # Main Application Interface & Logic
└── README.md         # Documentation
```

---

## 🎓 Academic Subjects Evaluated

1. Mathematics
2. Electrical & Electronics Engineering (EEE)
3. Physics
4. C Language
5. English

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).