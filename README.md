# Prophet by Meta

A notebook guide for Meta\'s Prophet forecasting toolset based on their documentation [here](https://facebook.github.io/prophet/docs/quick_start.html).

## Environment Setup

First create a virtual environment for this project:

```python
python -m venv .prophet_venv
```

Activate the venv:

```python
.prophet_venv/bin/activate
```

And, be sure to install the requirements:

```python
pip install -r requirements.txt
```

## Notes & Guides

The `NOTES/` directory contains write-ups and example notebooks used while exploring time-series modeling techniques in this repository. Brief descriptions of each file:

- `ARIMA_guide.ipynb` — A Jupyter notebook that walks through fitting and diagnosing ARIMA models on sample datasets. Includes code examples, model selection notes, and diagnostic plots.
- `prophet_guide.ipynb` — A Jupyter notebook demonstrating how to use Meta's Prophet for forecasting, with example preprocessing, changepoint tuning, and visualization of forecasts and components.
- `Fourier Series.tex` — LaTeX source for a short write-up on using Fourier series to model seasonality or periodic components in time series. This is the main source file.

### How to use these notes:

- Open the notebooks (`.ipynb`) with Jupyter, JupyterLab, or VS Code's notebook viewer to run the examples interactively.
- Compile the LaTeX source (`Fourier Series.tex`) with a LaTeX toolchain (for example, `pdflatex`) if you want a PDF render of the write-up. The `.aux` and `.toc` files are created by the compiler and can be ignored or removed if you recompile.

These files are intended as educational references and are not required to run the core scripts in this repository.


# Data Inventory

See `DATA/data.info` for a short inventory of datasets included in this repository (descriptions, column summaries, and source links when available).

