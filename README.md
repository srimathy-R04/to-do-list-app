# 📝 Task Manager App

A responsive and interactive Task Manager web application built using HTML, CSS, and JavaScript. This project demonstrates DOM manipulation, event handling, local storage persistence, CRUD operations, and state management.

## 🚀 Features

### ✅ CRUD Operations
- Create new tasks
- Read and display tasks
- Update existing tasks
- Delete tasks

### ✅ Task Management
- Mark tasks as completed
- Undo completed tasks
- Clear all completed tasks

### ✅ Filtering
- View All Tasks
- View Active Tasks
- View Completed Tasks

### ✅ Data Persistence
- Tasks are automatically saved using `localStorage`
- Data remains available after browser refresh

### ✅ User Experience
- Responsive design for desktop and mobile devices
- Dynamic task rendering
- Empty state handling
- Task counter
- Keyboard support (Press Enter to add tasks)

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Local Storage API

---

## 📂 Project Structure

```text
task-manager-app/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ⚙️ How It Works

### State Management

The application maintains all tasks inside a JavaScript array:

```javascript
let tasks = [];
```

Every operation updates this state and re-renders the UI.

### Local Storage

Tasks are stored in the browser using:

```javascript
localStorage.setItem("tasks", JSON.stringify(tasks));
```

and retrieved using:

```javascript
JSON.parse(localStorage.getItem("tasks"))
```

This ensures data persistence across page reloads.

---

## 📸 Features Demonstrated

- DOM Manipulation
- Event Delegation
- Array Methods (`map`, `filter`, `find`)
- Local Storage Persistence
- Responsive Web Design
- State-Driven UI Updates

---

## 🎯 Learning Outcomes

Through this project, the following concepts were implemented:

- JavaScript DOM Manipulation
- Event Handling
- Event Delegation
- Client-Side State Management
- CRUD Operations
- Local Storage API
- Responsive UI Design

---

## ▶️ Running the Project

1. Clone the repository

```bash
git clone https://github.com/srimathy-R04/to-do-list-app/
```

2. Open the project folder

3. Launch `index.html` in your browser

No additional setup or dependencies are required.

---

## 📌 Future Enhancements

- Task priorities
- Due dates
- Dark mode
- Drag and drop task sorting
- Backend integration
- User authentication

---

## 👨‍💻 Author

Developed as part of an internship project to demonstrate JavaScript logic, state management, CRUD functionality, and local data persistence.
