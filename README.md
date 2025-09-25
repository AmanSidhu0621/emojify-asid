# emojify-asid

Creating text with emojis based on input text with the help of NLP.

> **What is this?** A tiny module utility that takes plain text and suggests/augments it with relevant emojis. Useful for social captions, messaging bots, and playful UX.

---


## 🧱 Project structure

```
.
├── emojify/                 # Library code (core logic & utilities)
├── tests/                   # Unit tests
├── pyproject.toml           # Build config (PEP 517/518)
├── setup.py                 # Legacy packaging shim
└── README.md                # You are here
```

---

## 📦 Installation

### Option A: Local development

```bash
# clone
git clone https://github.com/AmanSidhu0621/emojify-asid
cd emojify-asid

# create & activate a venv (recommended)
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\\Scripts\\activate

# install in editable mode
pip install -e .
```

### Option B: Use directly in another project

```bash
pip install emojify-asid==0.1.3
```

> Requires Python 3.8+ (bump this to whatever you support).

---

## ⚡ Quickstart

### Python Use

```python
from emojify import emojify_text  # or Emojifier class if you expose one

text = "I just smashed my workout and feel amazing"
print(emojify_text(text))
# Can also customize the mapping
# → "I just smashed my workout and feel amazing 💪🔥😄"
```

---


## 🙌 Acknowledgements

* Emoji data sources such as the Unicode consortium
* Open‑source NLP libraries that make this possible

---

## 📣 Roadmap (nice‑to‑haves)

* Multilingual emoji mapping
* Emoji diversity/skin tone configuration
* Named‑entity‑aware inline placement
* Web demo (Streamlit/Gradio)

---


## 🗺️ Maintainers

* @AmanSidhu0621 (repo owner)

> PRs improving the heuristics/examples are especially welcome.
