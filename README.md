[![PyPI](https://img.shields.io/pypi/v/dryerlint)](https://pypi.org/project/dryerlint)
[![Python](https://img.shields.io/pypi/pyversions/dryerlint)](https://pypi.org/project/dryerlint)
[![License](https://img.shields.io/github/license/SpiritGun1/DryerLint)](https://github.com/SpiritGun1/DryerLint/blob/main/LICENSE)

# 🧺 DryerLint

> Remove the Fuzz.

**DryerLint** is a Python-powered code quality tool that:
- 🧼 Cleans up formatting with `black`, `isort`, and `ruff`
- 🧐 Runs deep linting, static analysis, type checks, and security scans
- 🎯 Outputs a color-coded summary with an overall code quality score
- 🚫 Ignores your `venv`, `.git`, and all the other gunk

---

## ✨ Features

- ✅ Auto-fixes formatting and imports
- 🔍 Deep linting, type checks, and security scans
- 🧠 Smart error summaries with scoring
- 🎨 Color-coded terminal output
- 🧺 One script to clean them all

---

## 💻 Installation

```bash
git clone https://github.com/SpiritGun1/DryerLint.git
cd DryerLint
python -m venv venv
venv\Scripts\activate   # or source venv/bin/activate on macOS/Linux
pip install -r requirements.txt

