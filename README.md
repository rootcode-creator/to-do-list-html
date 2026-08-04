<p align="center">
  <img src="Images/icon.png" alt="To-Do List logo" width="96" />
</p>

<h1 align="center">To-Do List</h1>

<p align="center">
  <i>A lightweight browser-based to-do list app built with HTML, CSS, and vanilla JavaScript for simple task management.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-%231572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/License-Apache%202.0-005571?style=for-the-badge&logo=apache&logoColor=white" alt="Apache License 2.0" />
  <img src="https://img.shields.io/badge/Status-Static%20App-4CAF50?style=for-the-badge&logo=rocket&logoColor=white" alt="Status" />
  <img src="https://img.shields.io/badge/Focus-Task%20Management-8B5CF6?style=for-the-badge&logo=check-circle&logoColor=white" alt="Focus" />
  <img src="https://img.shields.io/badge/Run-Local%20Browser-0EA5E9?style=for-the-badge&logo=firefox&logoColor=white" alt="Run locally" />
</p>

## Table of Contents

- [🚀 Project intro](#-project-intro)
- [📁 Project structure](#-project-structure)
- [⭐ Differentiators](#-differentiators)
- [🔧 Features](#-features)
- [🧰 Tech stack](#-tech-stack)
- [⚙️ Install methods](#️-install-methods)
- [ Deployment notes](#-deployment-notes)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## 🚀 Project intro

This project is a simple personal task manager that runs entirely in the browser. The interface includes an input field, an add button, and a dynamic task list that updates as the user interacts with it.

## 📁 Project structure

```text
to-do-list-html/
├── index.html
├── LICENSE
├── README.md
├── css/
│   └── style.css
├── Images/
│   └── icon.png
└── js/
    └── script.js
```

## ⭐ Differentiators

- Built as a lightweight static web app with no framework or build step required
- Uses plain JavaScript for direct DOM interaction and simple task management
- Keeps the experience easy to run locally and easy to extend for learning or small projects

## 🔧 Features

| Feature | Status | Description |
| --- | :---: | --- |
| Add tasks | ✅ | Users can enter a task and add it to the list with the Add to list button. |
| Remove tasks | ✅ | Each task includes a delete action so it can be removed from the list. |
| Dynamic updates | ✅ | The task list updates immediately as items are added or removed. |
| Simple styling | ✅ | Basic layout and hover effects make the interface more polished. |

### 🔄Flow diagram

```mermaid
flowchart TD
    A[Open app] --> B[Enter task]
    B --> C[Add to list]
    C --> D[View task]
    D --> E{Remove task?}
    E -- Yes --> F[Delete task]
    E -- No --> D
    F --> D
```

## 🧰 Tech stack

- **Framework:** None — built as a lightweight static web app
- **Structure:** HTML5 for page layout and content
- **Styling:** CSS3 for layout, colors, spacing, and hover effects
- **Interactivity:** Vanilla JavaScript for DOM updates and task handling
- **Storage:** No database required; tasks are managed in the browser

## ⚙️ Install methods

### 📦 Open locally

1. Clone or download this repository.
2. Open the project folder in your preferred code editor.
3. Launch the app by opening the index.html file in a browser.

No package installation or build process is required.


## 🚀 Deployment notes

This project is a static website, so it can be hosted on any simple web hosting service that serves files directly from the project folder. GitHub Pages is a suitable option for deployment.

## 🤝 Contributing

Contributions are welcome. If you would like to improve the app, feel free to open a pull request with your changes and a short description of what you updated.

## 📄 License

This project is licensed under the Apache License 2.0. See the LICENSE file for more information.
