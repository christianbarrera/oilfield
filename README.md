# oilfield

An interactive oil reservoir simulator that models pressure distribution throughout a 2D ground grid using finite difference methods. Designed for engineers and students to visualize and analyze reservoir behavior over time.

## Features
- Simulate pressure evolution in a rectangular reservoir with multiple wells (producers/injectors)
- Adjustable grid, reservoir, and well parameters
- 3D and interactive Plotly visualizations
- Export results to CSV and Excel
- Example: Add interactive widgets for parameter selection (ipywidgets)
- Modular, well-documented Jupyter notebook

## Getting Started
1. **Install requirements:**
   ```zsh
   pip install numpy scipy matplotlib plotly pandas ipywidgets
   ```
2. **Open `Reservoir Simulator.ipynb` in Jupyter or VS Code.**
3. **Follow the notebook instructions to set parameters, run simulations, and visualize results.**

## Example Outputs
- 3D surface plots of pressure at different time steps
- Interactive Plotly model (see below)
- Exported CSV/Excel files (e.g., `pressure_day50.csv`)

## Interactive Model
Interactive model available at: [Plotly Nichelik Field](https://plot.ly/~keedanbarrera/2/nichelik-field/#/)

## File List
- `Reservoir Simulator.ipynb` — Main simulation notebook
- `pressure_day50.csv` — Example exported results
- `pressure_day50.xlsx` — Example exported results
- `README.md` — Project documentation

---

For questions or suggestions, see the notebook or contact the project maintainer.
