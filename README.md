# 📘 Library Management System (C++)

A console-based **Library Management System** built in C++ to master Object-Oriented Programming (OOP), SOLID Principles, Design Patterns, and clean Low-Level Design (LLD) practices.

---

## 🎯 Purpose

This project is built with the following goals:

- Hands-on practice of C++ OOP fundamentals
- Practice **UML Diagramming**, Clean Code, and maintainable project structure
- Learn to refactor iteratively using **SOLID principles**
- Apply **Design Patterns** to real-world use cases
- Get comfortable with iterative development, versioning, and Git-based workflow

---

## 🏗️ Folder Structure

LibraryManagementSystem/
├── .vscode/ → VS Code build/run configurations
├── bin/ → Compiled binaries
├── src/ → Source code (C++)
├── docs/ → Documentation per milestone
│ ├── v1.0.md
│ ├── v1.1.md
│ └── uml/
│ └── class-diagram.drawio
├── .gitignore
└── README.md


---

## 📌 Features (Initial Version)

- Add books to library
- Search books by title or author
- Issue and return books
- Track inventory and issued books
- Maintain list of users and their issued books
- Simple CLI interface

---


## 🚧 Milestones & Versions

| Version | Description | Tags | Docs | Status |
|--------|-------------|------|------|--------|
| **v0.9** | Identify core classes and draw UML | `UML`, `ClassDesign` | [docs/v0.9.md](docs/v0.9.md), [uml/class-diagram.drawio](docs/uml/class-diagram.drawio) | 🔜 In Progress |
| **v1.0** | Working OOP-based code using class design | `OOP`, `Prototype` | [docs/v1.0.md](docs/v1.0.md) | 🔜 |
| **v1.1** | Refactor using **SOLID principles** | `SOLID`, `Refactor` | [docs/v1.1.md](docs/v1.1.md) | 🔜 |
| **v1.2** | Apply **Design Patterns** (e.g., Strategy, Factory) | `DesignPattern`, `BestPractices` | Planned | 🔜 |
| **v1.3** | Add validations, CLI UX, and modular error handling | `Robust`, `Maintainable` | Planned | 🔜 |
| **v2.0** | Final public release with clean docs + Git tags | `Public`, `Documented` | Planned | 🔜 |

---

## 🧠 UML & Design Thinking

| Task | Status | File |
|------|--------|------|
| Identify core entities & relationships | ✅ | – |
| Create **UML Class Diagram** | 🔜 | [docs/v0.9.md](docs/v0.9.md), [uml/class-diagram.drawio](docs/uml/class-diagram.drawio) |
| Keep diagram updated with each refactor | 🔁 | As needed |

> Use [draw.io](https://draw.io) or VS Code PlantUML extension for UML design

---

## 🧪 Feedback and Refactor Loop (Every Version)

- ✅ Initial self-review (code clarity, modularity, naming)
- ✅ Peer/GPT feedback
- ✅ Action points and refactor
- ✅ Update versioned docs in `docs/`
- ✅ Git commit and push with version tag: `vX.X`

---

## 📁 Versioned Documentation

Each major milestone will be documented separately in `docs/`. This helps keep the main README concise while preserving all learning notes.

| Version | Document |
|---------|----------|
| v0.9    | [docs/v0.9.md](docs/v0.9.md), [uml/class-diagram.drawio](docs/uml/class-diagram.drawio) |
| v1.0    | [docs/v1.0.md](docs/v1.0.md) |
| v1.1    | [docs/v1.1.md](docs/v1.1.md) |

> 📝 GPT feedback, class design explanations, SOLID application reasoning, etc., in these files.

---

## 🚀 How to Run

Option 1 : run command every time

```bash
g++ src/main.cpp -o bin/libraryApp && ./bin/libraryApp

```
Option 2:

📁 File: .vscode/tasks.json
```json
{
  "version": "2.0.0",
  "tasks": [
    {
      "label": "Build and Run Library App",
      "type": "shell",
      "command": "cmd",
      "args": [
        "/c",
        "g++ -std=c++17 src/main.cpp -o bin\\libraryApp && bin\\libraryApp"
      ],
      "group": {
        "kind": "build",
        "isDefault": true
      },
      "problemMatcher": [],
      "detail": "Builds and runs the Library Management System on Windows"
    }
  ]
}
```
🟢 Simply press Ctrl + Shift + B in VS Code to compile and run the project.

---

## ✅ TODOs

- [x] Set up folder structure and versioned README
- [x] Plan milestones and documentation flow
- [x] Create `tasks.json` to build and run automatically
- [ ] Complete v0.9: Identify classes & UML diagram
- [ ] Implement v1.0: OOP-based working version
- [ ] Collect feedback, create v1.1 plan (SOLID refactor)
- [ ] Refactor and add design patterns (v1.2)
- [ ] Improve modularity, UX (v1.3)
- [ ] Finalize for public GitHub push (v2.0)

---
## 👨‍💻 Author Notes

This project is my hands-on journey to deeply understand **Low-Level Design (LLD)** in a practical, iterative way. I'm focusing on:

- Writing code from scratch for real-world use cases
- Facing the pain of vague requirements, design trade-offs, and naming dilemmas
- Applying feedback from peers and ChatGPT
- Using **VS Code**, **Git/GitHub**, and **versioned iterations** to track design maturity

My goal isn’t just to “complete” the project — but to gradually evolve the code through **better design choices**, **solid architecture**, and **clean structure**, version by version.

---

 