# Brusselator System Analysis

This project provides numerical simulation and visualization of the Brusselator chemical reaction model, a classic example of non-equilibrium thermodynamics.

## Features

- Numerical integration using 4th order Runge-Kutta method
- Static plots for key parameter values
- Interactive animation showing system behavior across parameter space
- Phase portraits and time series visualization

## Requirements

- Python 3.6+
- NumPy
- Matplotlib
- Jupyter Notebook (for interactive visualization)

## Installation

```bash
git clone https://github.com/yourusername/brusselator-analysis.git
cd brusselator-analysis
pip install -r requirements.txt
```

## Usage

Run in Jupyter Notebook:

```python
from brusselator import plot_static_graphs, create_animation

# Display static graphs for key parameter values
plot_static_graphs()

# Create and display interactive animation
animation = create_animation()
display(animation)
```

Or execute as a script:

```bash
python brusselator.py
```

## Key Parameters

The system behavior changes based on parameter A:
- A < 1.44: Stable node/focus
- 1.44 < A < 5.56: Unstable focus
- A > 5.56: Stable focus

## Output Examples

Static plots show:
1. Time series of x(t) and y(t) concentrations
2. Phase portraits with trajectory and final state

Animation shows:
- Continuous transition between different regimes
- Current parameter values and stability status

## License

MIT License - free for academic and research use
