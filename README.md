# Tayo Programming Language

Tayo is a **beginner-friendly, cross-platform scripting language** designed to make programming simple, fun, and intuitive.  
It works seamlessly on **Windows, Linux, and MacOS** with a single syntax for all platforms.

---

## 🔹 Features

- **Simple Syntax** – Commands like `pr()`, `list`, `make folder`, `re`, and `install` are easy to learn.
- **Cross-Platform** – Same code works on Windows, Linux, and MacOS.
- **Error Codes** – Positive / Negative / Fatal error codes for clear feedback:
  - **0, 2, 4, 6** → Positive (success / actionable feedback)
  - **1, 3, 5** → Negative (user errors)
  - **99** → Fatal (cannot be recovered)
- **Script Files** – Save scripts with `.tayo` extension.
- **Single Commands File** – All core commands are centralized in `commands.py`.
- **Examples Included** – Pre-made example scripts to learn and test commands.
- **Unit Tests** – Verify commands and error codes with automated tests.

---

## 🔹 Basic Commands

| Command | Description | Example |
|---------|------------|---------|
| `pr("text")` | Print text to the console | `pr("Hello World")` |
| `list` | List contents of the current folder | `list` |
| `make folder <name>` | Create a new folder | `make folder my_folder` |
| `re <filename>` | Remove a file | `re example.txt` |
| `install <language>` | Install a programming language | `install python` |

---

## 🔹 Example Script

```tayo
# hello.tayo
pr("Hello, Tayo Programming Language!")
make folder test_folder
list
re test.txt
install python
