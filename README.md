# Data interview

## Setup

Install [uv](https://docs.astral.sh/uv/getting-started/installation/), then from
the repository root:

```sh
uv sync
uv run jupyter lab
```

`uv sync` installs Python 3.12 (if needed) and the pinned packages from
`uv.lock` into `.venv/`. Open `analysis-interview-template.ipynb` in JupyterLab.

Please run the setup before the interview and check that the first cell of the
notebook runs without errors.

## Contents

- `analysis-interview-template.ipynb` — the notebook you will work through.
- `data/` — datasets used in the notebook.
