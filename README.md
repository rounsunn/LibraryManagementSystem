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

## 🧰 Tech Stack

- **Language**: C++17
- **IDE**: Visual Studio Code
- **Compiler**: MinGW-w64 g++ 15.1.0
- **Version Control**: Git + GitHub
- **Diagramming**: draw.io

---

## 🗂️ Folder Structure

<pre>
📁 LibraryManagementSystem/
├── .vscode/              # VS Code build/run configs
├── bin/                  # Compiled output
├── src/                  # C++ source files
├── docs/                 # Design notes per version
│   ├── v1.0.md
│   ├── v1.1.md
│   └── uml/
│       └── class-diagram.drawio
├── .gitignore
└── README.md
</pre>

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
|---------|-------------|------|------|--------|
| **v0.9** | Identify core classes and UML diagram | `UML`, `ClassDesign` | [docs/v0.9.md](docs/v0.9.md), [uml/class-diagram.drawio](docs/uml/class-diagram.drawio) | 🔜 In Progress |
| **v1.0** | Working OOP-based code using class design | `OOP`, `Prototype` | [docs/v1.0.md](docs/v1.0.md) | 🔜 |
| **v1.1** | Refactor using **SOLID principles** | `SOLID`, `Refactor` | [docs/v1.1.md](docs/v1.1.md) | 🔜 |
| **v1.2** | Apply **Design Patterns** (Strategy, Factory, etc.) | `DesignPattern`, `BestPractices` | Planned | 🔜 |
| **v1.3** | Add validations, CLI UX, and modular error handling | `Robust`, `Maintainable` | Planned | 🔜 |
| **v2.0** | Final public release with clean docs + Git tags | `Public`, `Documented` | Planned | 🔜 |

---

## 🧠 UML & Design Thinking

| Task | Status | File |
|------|--------|------|
| Identify core entities & relationships | ✅ | – |
| Create **UML Class Diagram** | 🔜 | [uml/class-diagram.drawio](docs/uml/class-diagram.drawio) |
| Keep diagram updated with each refactor | 🔁 | As needed |

> 💡 Use [draw.io](https://draw.io) or the PlantUML VS Code extension for creating/updating class diagrams.

---

## 🔁 Feedback and Refactor Loop (Every Version)

- ✅ Initial self-review (code clarity, modularity, naming)
- ✅ Peer/GPT feedback
- ✅ Action points and refactor
- ✅ Update versioned docs in `docs/`
- ✅ Git commit and push with version tag: `vX.X`

---

## 📁 Versioned Documentation

Each major milestone is documented in the `docs/` folder to preserve thought process, design notes, and review learnings.

| Version | Document |
|---------|----------|
| v0.9    | [docs/v0.9.md](docs/v0.9.md), [uml/class-diagram.drawio](docs/uml/class-diagram.drawio) |
| v1.0    | [docs/v1.0.md](docs/v1.0.md) |
| v1.1    | [docs/v1.1.md](docs/v1.1.md) |

> 📝 Design discussions, SOLID decisions, GPT feedback, etc., are included in these files.

---

## 🚀 How to Run

### 🔹 Option 1: Manually compile and run
```bash
g++ -std=c++17 src/main.cpp -o bin/libraryApp && ./bin/libraryApp
```
### 🔹 Option 2: Use Build Task in VS Code
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
Then press Ctrl + Shift + B in VS Code to compile and run.

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
- Embracing the challenges of vague requirements, design trade-offs, and naming decisions
- Applying feedback from peers and ChatGPT
- Using **VS Code**, **Git/GitHub**, and versioned iterations to track design maturity

> 💡 My goal isn't just to complete the project, but to evolve it step-by-step through better design, architecture, and coding practices.


💡 My goal isn't just to complete the project, but to evolve it step-by-step through better design, architecture, and coding practices.