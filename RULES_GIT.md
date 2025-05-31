# ✅ Git Rules for the "Heat Diffusion OpenMP" Project

These rules help keep the project clean, organized, and collaborative.

---

## 🔁 1. Always pull before starting to work

Before you begin coding, **make sure your local copy is up to date**:

```bash
git pull origin main
```

---

## 🧹 2. Commit often with clear messages

Use clear and meaningful commit messages:

```bash
git add .
git commit -m "Implemented anisotropic diffusion function"
```

✅ Good examples:
- "Created plotting script"
- "Fixed bug in temperature update"
- "Updated documentation"

❌ Avoid vague messages like "fix", "changes", or "stuff"

---

## 📤 3. Only push working code

Always test your code before pushing:

```bash
git push origin main
```

Never push code that:
- Doesn’t compile
- Breaks the program
- Is partially implemented

---

## 👀 4. Review changes before committing

Use these commands to see what you're committing:

```bash
git status       # See modified or new files
git diff         # See exact line changes
```

---

## 📦 5. Respect the folder structure

- `src/` → C/OpenMP source code
- `data/` → input/output files (e.g., CSV)
- `plots/` → plots and visualization scripts
- `report/` → final report (PDF, TeX)
- `slides/` → presentation materials

---

## 🚫 6. Don’t track temporary files

Make sure `.gitignore` excludes:
- Build artifacts (`*.o`, `*.exe`)
- Output files (`*.csv`, `*.png`, `*.txt`)
- Temporary or IDE folders (`cmake-build-*`, `.idea/`)

---

## 🔒 7. Don’t edit others’ code without notice

If someone else is working on a file, **communicate before editing it**. For major changes, consider using a pull request.

---

## 🧩 Most useful Git commands

| Task                          | Command                  |
|-------------------------------|--------------------------|
| Add all files                 | `git add .`              |
| Commit with a message         | `git commit -m "..."`    |
| Push to GitHub                | `git push origin main`   |
| Pull updates from GitHub      | `git pull origin main`   |
| Check file status             | `git status`             |
| See changes before commit     | `git diff`               |

---

## 🔁 Golden Rule

> **Always pull before pushing.**

```bash
git pull origin main
# If no conflict:
git push origin main
```

---

## ✍️ Team

List the GitHub usernames of team members below.

- [@username1](https://github.com/username1)
- [@username2](https://github.com/username2)
