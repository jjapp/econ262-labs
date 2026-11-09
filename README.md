# ECON 262 labs and games

Student-facing materials for ECON 262 (Introduction to Statistics) at Western
Nevada College: Colab notebooks, lab data, and browser games.

**This repo is generated. Do not edit it.** Every file here is mirrored
automatically from a private development repo, so a change made here is
overwritten on the next push. Open an issue instead.

## Notebooks

Each one opens in Google Colab with no account linking and no download. Colab
will ask you to save your own copy to Drive before you can run it.

| Notebook | Module | What it does |
|---|---|---|
| [Module 1 on-ramp](https://colab.research.google.com/github/jjapp/econ262-labs/blob/main/notebooks/ECON262_M01_lab_onramp.ipynb) | 1 | Orientation, about 20 minutes, ungraded. Teaches every move the graded labs need. |

## Games

Single HTML pages. No login, no cookies, no analytics, and nothing about you
is stored or sent anywhere.

| Game | Module | What it teaches |
|---|---|---|
| [G0 Sample Factory](https://jjapp.github.io/econ262-labs/games/g00_sample_factory/) | 1 | Why a bigger sample buys a better estimate, and when it stops being worth paying for. |

Every game is also described in text on its Canvas lecture page, so a game is
never the only route to required content.

## Data

CSVs under `data/`, loaded by the notebooks straight from GitHub:

```python
URL = "https://raw.githubusercontent.com/jjapp/econ262-labs/main/data/<file>.csv"
df = pd.read_csv(URL)
```

Nothing in this repo is student data.
