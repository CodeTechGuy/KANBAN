# 📋 Simple Kanban Board

A minimalistic, web-based Kanban board application built using pure **HTML, CSS, and JavaScript**. This project allows users to manage tasks across three distinct stages: **To Do**, **In Progress**, and **Done**.



<img width="3179" height="1718" alt="Image" src="https://github.com/user-attachments/assets/6059d6c8-b1c0-48da-a23c-e15691f35b58" />


---

## ✨ Features

* **Task Management:** Easily add new tasks with a title and description.
* **Drag-and-Drop:** Intuitive drag-and-drop functionality to move tasks between columns.
* **Persistent Storage:** Tasks are saved locally using **Local Storage**, so they persist even after closing the browser.
* **Task Deletion:** Ability to delete individual tasks.
* **Real-time Counting:** Displays the count of tasks in each column.
* **Responsive Design:** Styled with a dark theme using modern CSS.

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You only need a modern web browser to run this application.

### Installation

1.  **Clone the repository** (if hosted on Git):
    ```bash
    git clone https://github.com/CodeTechGuy/KANBAN
    cd simple-kanban-board
    ```
2.  **Download the files** (`index.html`, `style.css`, `script.js`) and place them in a single directory.
3.  **Open `index.html`** in your preferred web browser.

---

## 🛠️ Usage

1.  Click the **"Add new Task"** button in the top-right corner to open the modal.
2.  Enter the **Task Title** and **Task Description**.
3.  Click **"Add Task"**. The new task will appear in the **"To Do"** column.
4.  **Drag** a task card and **drop** it into another column (**In Progress** or **Done**) to update its status.
5.  Click the **"Delete"** button on a task card to permanently remove it.

---

## 🏗️ Project Structure

The project consists of three main files:

* `index.html`: Defines the structure of the Kanban board, including the navigation, columns, and the modal for adding new tasks.
* `style.css`: Provides the styling for the application, featuring a dark theme and setting up the column layout and drag-and-drop visual effects.
* `script.js`: Handles all the application logic, including:
    * Adding new tasks to the "To Do" column.
    * Implementing drag-and-drop between the `todo`, `progress`, and `done` columns.
    * Managing **Local Storage** for data persistence.
    * Updating task counts.
    * Modal toggling logic.

---

## 💡 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)** - For all dynamic functionality and state management.

---

## 🤝 Contributing

This is a personal project, but feel free to fork the repository or suggest improvements!

