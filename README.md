# Bayesian Football Match Simulation

Real-time football match simulation powered by Bayesian hierarchical multinomial logistic regression, featuring live probabilistic updates, British-style commentary, and reactive crowd dynamics.

## Features

- **Bayesian Modeling**: Hierarchical multinomial logistic regression with live posterior updates
- **Real-time Simulation**: Time-based match events with adaptive uncertainty quantification
- **Audio Integration**: Synchronized British commentary and crowd reactions
- **Analytics Dashboard**: Interactive platform for analyzing match predictions and actionable insights
- **Uncertainty Calibration**: Temperature scaling for improved prediction reliability

## Project Structure
```
bayesian-football-simulation/
├── EPL Bayesian Model.ipynb    # Main notebook (EDA + Modeling + Simulation)
├── dashboard/                   # Analytics dashboard
├── requirements.txt             # Dependencies
└── report/                      # Project documentation
```

## Installation
```bash
pip install -r requirements.txt
```

## Usage

Open and run `bayesian_simulation.ipynb` in Jupyter Notebook.

## Requirements

- Python 3.8+
- PyMC for Bayesian inference
- See `requirements.txt` for full dependencies

## License

MIT
