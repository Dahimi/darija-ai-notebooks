# Darija AI — notebooks

The code that goes with the [Darija AI](https://github.com/Dahimi) YouTube
episodes. Each notebook runs in your browser on Google Colab — free, nothing to
install.

| Episode | Notebook | Open |
|---|---|---|
| ep10 — training a model, for real | `notebooks/ep10_house_prices.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Dahimi/darija-ai-notebooks/blob/main/notebooks/ep10_house_prices.ipynb) |

## The data

`data/` holds the same houses as the videos, so every number in a notebook
matches what you saw on screen.

| File | What it is |
|---|---|
| `houses.csv` | The eight houses from episode 1. |
| `city_sample.csv` | 200 houses sampled from the invented city of episode 8. `hay_raqi` is 1 for an upscale neighbourhood. |

Prices are in *milion* (millions of centimes), surfaces in m².

## Running locally

```bash
pip install -r requirements.txt
jupyter lab
```
