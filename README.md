# pythonic-practice

Pythonic exercises, LeetCode solutions, SQL practice, and data & automation projects.

This is a public repository where I practice writing clean, readable Python and follow
[PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/).

## 📂 Repository Structure

| Folder | Description |
| --- | --- |
| `pythonic/` | Small exercises on idiomatic Python (comprehensions, generators, decorators, etc.) |
| `leetcode/` | LeetCode solutions with notes on approach and complexity |
| `sql/` | SQL practice queries |
| `projects/` | Data processing and automation projects |

## 🐍 Style Guidelines

I aim to follow PEP 8, including:

- 4 spaces per indentation level
- Maximum line length of 79 characters
- `snake_case` for functions and variables, `CapWords` for classes, `UPPER_CASE` for constants
- Imports at the top of the file, grouped as: standard library → third-party → local
- Two blank lines around top-level functions and classes
- Docstrings for public modules, functions, classes, and methods

## 🛠️ Tools

- [Ruff](https://docs.astral.sh/ruff/) – linting and formatting
- [Black](https://black.readthedocs.io/) – code formatting (optional)

```bash
pip install ruff
ruff check .
ruff format .
```

## 📝 Notes

This repo is for learning purposes. Feedback and suggestions are welcome!
