# Data Science Course

Additional material for the Data Science course.

## `colab` setup

You can open the notebooks directly in `colab` by clicking on the badges below. You'll need to uncoment the installation prompts `!pip install ...`, as they were removed for local runtimes.

- [TME1](./notebooks/TME1.ipynb): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xmaster-eu/data-science/blob/main/notebooks/TME1.ipynb)


## `uv` setup

Use this setup if you want to run the notebooks locally.
First you'll need to install `uv` (see [uv](https://docs.astral.sh/uv/)). Then, after cloning the repository, you can install the dependencies with:

```bash
uv sync
```

Then you can run the notebooks using the virtual environment created. 

In VSCode or Cursor, you can select the python interpreter using `cmd+shift+p`/`ctrl+shift+p` and then `Python: Select Interpreter`, choose `.venv/bin/python`.

## Feedback

At any point during the course, you can submit feedback using this [form](https://nuage.lip6.fr/index.php/apps/forms/s/sbzSqCtGBq9M9cGq762pdn3r).
