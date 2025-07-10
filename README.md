# 📝 Todo List Web App using React.js

A clean and modern ToDo app built with **React** and powered by the **Context API** for global state management. Styled using **Tailwind CSS**, it allows users to efficiently create, update, delete, and manage tasks — all while storing data in browser `localStorage`.

---

## ⚙️ Features

- ✅ Add, edit, delete tasks
- 📌 Mark tasks as complete/incomplete
- ♻️ Real-time state updates using **React Context API**
- 🎨 Beautiful UI with **Tailwind CSS**
- 💾 Data persistence with `localStorage`
- 🧩 Clean component structure
- 📱 Responsive design

---

## 🚀 Live Demo

🔗 [Live App Link](https://harshita-todo.netlify.app)  
*(Replace with actual link if needed)*

---

## 🛠 Tech Stack

- **React.js** – JavaScript library for building UI
- **React Context API** – Global state management
- **Tailwind CSS** – Utility-first CSS framework
- **localStorage** – For persisting tasks
- **HTML5 + JavaScript (ES6)**

---

## 📂 Folder Structure
React-ToDo-App/
├── public/
│ └── index.html
├── src/
│ ├── components/
│ │ ├── AddTodo.jsx
│ │ ├── TodoList.jsx
│ │ └── TodoItem.jsx
│ ├── context/
│ │ └── TodoContext.jsx
│ ├── App.jsx
│ ├── index.js
│ └── index.css (Tailwind directives)
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── README.md


---

## 🧠 Key Concepts Used

### 🔄 React Context API
Used for managing todos and actions (add/delete/toggle) globally without prop drilling.

### 🎨 Tailwind CSS
Utility-first CSS classes are used directly in components for fast, responsive design without writing custom stylesheets.

### 💾 localStorage
Todos are saved in the browser, so they persist even after refreshing the page.

---

## 📦 Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/harshsinghpujari/React-ToDo-App.git
cd React-ToDo-App
```
2. **Install dependencies**

```bash
npm install
```
3. **Run the development server**

```bash
npm start
```

**🧪 Build for Production**
```bash

npm run build
```

Creates an optimized production build in the build/ directory.


🔧 Future Improvements

    Filter tasks (All / Active / Completed)

    Due date & reminders

    Drag-and-drop task reordering

    Firebase or Express backend

    Dark mode toggle


🧑‍💻 Author

Himanshu Singh
GitHub: @harshsinghpujari


🙌 Contributing

Contributions are welcome!

    Fork the repo

    Create your feature branch: git checkout -b feature-name

    Commit your changes: git commit -m 'Add some feature'

    Push to the branch: git push origin feature-name

    Open a pull request

Made with ❤️ using React + Tailwind + Context API