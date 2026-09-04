# So You Want to Be a Data Scientist — notebooks

Runnable companions to the **Python Primer for Data Science**, one of the
[AI/Biz books](https://www.ai.biz/books/python-primer/).

Every notebook opens directly in Google Colab. Nothing to install.

| Ch | Notebook | Chapter | Open |
|---|---|---|---|
| 3 | `01-why-python.ipynb` | [Why Python Won](https://www.ai.biz/books/python-primer/why-python/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/01-why-python.ipynb) |
| 10 | `02-numpy.ipynb` | [NumPy: Thinking in Arrays](https://www.ai.biz/books/python-primer/numpy/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/02-numpy.ipynb) |
| 11 | `03-pandas.ipynb` | [Pandas: The Eighty Per Cent](https://www.ai.biz/books/python-primer/pandas/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/03-pandas.ipynb) |
| 12 | `11-files-and-formats.ipynb` | [Getting Data In: Files and Formats](https://www.ai.biz/books/python-primer/files-and-formats/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/11-files-and-formats.ipynb) |
| 14 | `13-cleaning.ipynb` | [Cleaning and Reshaping](https://www.ai.biz/books/python-primer/cleaning-and-reshaping/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/13-cleaning.ipynb) |
| 15 | `14-joining.ipynb` | [Joining Without Losing Rows](https://www.ai.biz/books/python-primer/joining-data/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/14-joining.ipynb) |
| 16 | `15-text.ipynb` | [Working With Text](https://www.ai.biz/books/python-primer/text/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/15-text.ipynb) |
| 17 | `16-dates.ipynb` | [Dates, Times and Time Zones](https://www.ai.biz/books/python-primer/dates-and-times/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/16-dates.ipynb) |
| 18 | `17-categories.ipynb` | [Categories and Encoding](https://www.ai.biz/books/python-primer/categories-and-encoding/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/17-categories.ipynb) |
| 19 | `18-visualisation.ipynb` | [Visualisation That Isn't Decoration](https://www.ai.biz/books/python-primer/visualisation/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/18-visualisation.ipynb) |
| 20 | `19-statistics.ipynb` | [The Statistics You Actually Need](https://www.ai.biz/books/python-primer/statistics/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/19-statistics.ipynb) |
| 21 | `20-evaluation.ipynb` | [Evaluation, and How It Lies to You](https://www.ai.biz/books/python-primer/evaluation/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/20-evaluation.ipynb) |
| 22 | `12-scikit-learn.ipynb` | [scikit-learn: The Interface, Not the Algorithms](https://www.ai.biz/books/python-primer/scikit-learn/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/12-scikit-learn.ipynb) |
| 23 | `22-feature-engineering.ipynb` | [Feature Engineering That Survives](https://www.ai.biz/books/python-primer/feature-engineering/) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibizx/python-primer-notebooks/blob/main/22-feature-engineering.ipynb) |

## Running locally instead

```bash
uv venv && source .venv/bin/activate
uv pip install -r requirements.txt
jupyter lab
```

## How this repo is maintained

Notebooks are authored alongside the chapters in the site repository and pushed
here through the GitHub Contents API. The Colab badge at the top of each
notebook is regenerated on every push, so the links never go stale. Every code
cell is executed before anything is pushed.

Each book gets its own notebook repository, so you can clone just the one you
are working through.

---

MIT licensed. © Sameer Gupta · [ai.biz](https://www.ai.biz/)
