# 📚 EduBuddy Timetable Generator

EduBuddy is a **smart study timetable generator** built with **HTML, CSS, JavaScript (frontend)** and a **Node.js + Express + SQLite backend**.  
It helps students automatically create personalized study or college timetables based on subjects, credits/chapters, available days, and study hours.

---

## ✨ Features
- 🎓 **Login & Register system** (SQLite database)
- ⏱️ **Generate smart study timetables** (College or Self-study mode)
- 📊 **Balanced distribution** of hours/chapters across days
- 💾 **Saves timetables to database** for each user
- 🌐 **Frontend-Backend integration** using Fetch API
- ⚡ Simple, lightweight, and open-source

---

## 🛠️ Tech Stack
### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js
- SQLite (with `sqlite3` + `sqlite` npm packages)

---

## 📂 Project Structure
```
edubuddy/
│
├── frontend/
│   └── index.html        # Main frontend page
│   └── style.css
│
├── backend/
│   └── script.js          # Express + SQLite backend
│   └── edubuddy.db        # SQLite database (auto-created)
│
└── README.md              # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/mandeepsingh2005/edubuddy.git
cd edubuddy/backend
```

### 2️⃣ Install dependencies
```bash
npm init -y
npm install electron-builder
```

### 3️⃣ Run the backend server
```bash
node server.js

---

## 🖼️ Screenshots
*(Add screenshots of your frontend UI + sample generated timetable here)*

---

## 📌 To-Do
- [ ] Add password hashing (security)
- [ ] Add user sessions (JWT/Express-session)
- [ ] Export timetable as PDF/Excel
- [ ] Add drag-and-drop timetable editor

---

## 🤝 Contributing
Pull requests are welcome!  
For major changes, open an issue first to discuss what you’d like to change.

---

## 📜 License
This project is licensed under the MIT License.
