# STAT163 — Week 4 notebooks: working with text in columns

Two notebooks to work through this week. Nothing to submit.

| Notebook | Time |
|---|---|
| `01-before-the-lecture-text-in-columns.ipynb` | 45 min |
| `02-before-the-practice-regex-and-split.ipynb` | 45 min, after RegexLearn's [Regex 101](https://regexlearn.com/learn/regex101) |

## Run them with nothing to install

[![Open the first notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week4-pre-lecture/blob/main/01-before-the-lecture-text-in-columns.ipynb) `01-before-the-lecture-text-in-columns.ipynb`

[![Open the second notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week4-pre-lecture/blob/main/02-before-the-practice-regex-and-split.ipynb) `02-before-the-practice-regex-and-split.ipynb`

**What Colab is.** Google Colab is a Jupyter notebook that runs in your browser, on a
computer at Google, instead of on your laptop. The cells, the order you run them in, and
pandas all work the way they do in a notebook on your laptop.

Two differences from a notebook on your laptop:

- **The computer at Google is temporary.** When you close the tab, it is gone. The
  notebook file in this repository does not change. To keep your edits, use
  **File → Save a copy in Drive**.
- **You cannot open the files on your laptop from it.** Here that does not matter: the
  data for these notebooks comes from the web, and you need no other file.

## Or run them on your machine

You need [`uv`](https://docs.astral.sh/uv/) and [Git](https://git-scm.com/downloads).

```bash
git clone https://github.com/stat163-2026t1/week4-pre-lecture.git
cd week4-pre-lecture
uv sync
```

Then open a notebook in [Positron](https://positron.posit.co/) and, when it asks which
Python to use, choose the one inside `.venv`. Or run `uv run jupyter lab`.
