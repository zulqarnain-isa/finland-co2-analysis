# Finland's CO₂ Emissions Analysis

A beginner data analysis project exploring how and why Finland's CO₂ emissions
have changed over time, using Python and pandas.

## Question

How have Finland's CO₂ emissions evolved, and what's driving the changes?

## Key findings

- Finland's emissions peaked at about 72.7 million tonnes in 2003 and have nearly
  halved to around 29.8 million tonnes by 2024.
- The decline is driven largely by a collapse in coal emissions, which fell from
  roughly 22 Mt in 1990 to under 8 Mt in 2024.
- Per-capita emissions tell a different story from total emissions when comparing
  countries — small petrostates rank highest per person, not the largest total emitters.

## Dataset

[Our World in Data — CO₂ and Greenhouse Gas Emissions](https://github.com/owid/co2-data)
One row per country per year, covering 1750–2024, with emissions, per-capita figures,
fuel-source breakdowns, population, and GDP.

## Tools

Python, pandas, matplotlib

## What this project covers

- Loading and inspecting a dataset (`shape`, `head`, `info`)
- Filtering rows and selecting columns
- Plotting trends over time with matplotlib
- Breaking emissions down by fuel source
- Ranking countries by per-capita emissions

## How to run

1. Clone this repository
2. Open `finland-co2-analysis.ipynb` in Jupyter
3. Run the cells top to bottom (the dataset loads automatically from the web)

Requires: Python 3, pandas, matplotlib (all included with Anaconda)
