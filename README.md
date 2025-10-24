# 📝 ToDo List App

A simple and elegant **ToDo List web application** built using **React.js**, allowing users to **create**, **edit**, **delete**, and **persist** tasks efficiently. Each task is displayed in a neat card layout containing a **title**, **description**, **date**, and **action icons** for easy management.

This app also utilizes **Local Storage** to save all your tasks — so even if you close or reload the browser, your tasks remain safely stored.

---

## 🚀 Features

* ➕ **Add New Task:**
  Create a new task with a title, description, and date.

* ✏️ **Edit Task:**
  Modify existing tasks anytime using the edit icon on each task card.

* ❌ **Delete Task:**
  Remove tasks easily with the delete icon.

* 💾 **Local Storage Integration:**
  Tasks are stored in the browser’s local storage, ensuring your list remains intact even after reloading or reopening the app.

* 🧩 **Card-based Layout:**
  All tasks are displayed as responsive cards in the main container.

* ⚡ **Dynamic Rendering:**
  The UI updates instantly as you add, edit, or delete tasks.

* 🧼 **Clean & Intuitive UI:**
  Simple, user-friendly design for managing daily tasks.

---

## 🏗️ Project Structure

```
ToDoList-App/
│
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
│
├── src/
│   ├── index.js
│   ├── index.css
│   ├── App.js
│   ├── App.css
│   │
│   └── compnents/
│       ├── Card.js
│       ├── Card.css
│       │
│       ├── CreateTask.js
│       ├── CreateTask.css
│       │
|       ├── EditTask.js
│       ├── EditTask.css
│       │
│       ├── TodoList.js
│       └── TodoList.css
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

Follow the steps below to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Munazza-Iman/ToDoList.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd todolist-app
```

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Run the App

```bash
npm start
```

After running the command, your ToDo List App will be available at:
👉 **[http://localhost:3000](http://localhost:3000)**

---

## 🧠 How It Works

### 🪄 Create a Task

* Click on the **“Add Task”** button.
* Fill in the **Title**, **Description**, and **Date** fields.
* Click **Save** — your task will appear instantly on the main screen.

### 📝 Edit a Task

* Click the **Edit (✏️)** icon on the task card.
* Update the desired fields and save changes.

### 🗑️ Delete a Task

* Click the **Delete (🗑️)** icon to remove a task from the list.

### 💾 Persistent Storage

* All tasks are automatically stored in **Local Storage**.
* When you refresh or reopen the app, previously added tasks are reloaded and displayed automatically.

### 🗂️ View All Tasks

* All created tasks are displayed as **cards** in the main container.
* Each card shows the **title**, **description**, **date**, and **action icons**.

---

## 🧩 Components Overview

| Component         | Description                                                                     |
| ----------------- | ------------------------------------------------------------------------------- |
| **App.js**        | Root component managing app logic and state. Handles local storage operations.  |
| **Card.js**       | Displays individual tasks with title, description, date, and edit/delete icons. |
| **CreateTask.js** | Handles creation of new tasks via an input form/modal.                          |
| **EditTask.js**   | Handles editing existing tasks.                                                 |
| **TodoList.js**   | Manages the display of all tasks in a card grid layout.                         |

---

## 🎨 Styling

Each component has its own CSS file for modular styling:

* **index.css** – global styles for the app.
* **App.css** – layout and main container styling.
* **Component CSS files** – individual styling for CreateTask, EditTask, TodoList, and Card.

---

## 🛠️ Built With

* ⚛️ **React.js** – Frontend library for building user interfaces
* 🧰 **JavaScript (ES6+)** – Logic and interactivity
* 💾 **Local Storage API** – For persistent data storage
* 🎨 **CSS3** – Styling and layout
* 🧱 **HTML5** – Base structure

---

## 📸 Example UI

Each task card displays:

* **Title** – short name of the task
* **Description** – details about the task
* **Date** – task creation or due date
* **Icons** – edit (✏️) and delete (🗑️) options

Tasks appear dynamically in the main container as they are added or loaded from local storage.

---

## 📦 Future Improvements

* 🗓️ Add task due-date reminders
* ☑️ Mark tasks as “Completed”
* 🔍 Add search and filter options
* 🌙 Add dark mode
* 🔗 Sync tasks with backend (MongoDB/Firebase)

---

## 🧑‍💻 Author

**Munazza Iman**

---