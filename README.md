# BF550 · TA office hours

Materials I use in office hours for BF550 (Fall 2026). Each topic sits in its own numbered
folder. Every notebook runs on its own: it builds its own data, so it needs no downloads.

Office hours cover **any** course question. A topic notebook is just something to work through
together when the room is quiet, or a place to start when several people ask the same thing.

## Topics

| # | Topic | Notebook | First used |
|---|---|---|---|
| 01 | Plotting with Matplotlib | [01-matplotlib/plotting_with_matplotlib.ipynb](01-matplotlib/plotting_with_matplotlib.ipynb) | 2026-09-21 |

## Running the notebooks

Use the course `bf550` conda environment and pick the `bf550` kernel in VS Code or JupyterLab.

```bash
module load miniconda
conda activate bf550
```

**The course environment does not include pandas.** Some notebooks here use it (01 does). If
you want to run those, install pandas into your own copy of the environment:

```bash
conda install -n bf550 -c conda-forge pandas
```

## Cell tags

Cells in the notebooks carry tags you can filter or collapse on:

- `core`: worked through live
- `exercise`: pause, predict, edit, rerun
- `solution`: one possible answer; keep it collapsed until someone needs it
- `deep-dive`: optional, only if there's time

## Adding a new topic

1. Create `NN-topic/` using the next free number.
2. Put the notebook in that folder. Restart the kernel and run all cells before committing, so the saved outputs match the code.
3. Add a row to the table above.
