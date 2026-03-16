# The 37% Rule Analysis

A Jupyter notebook project exploring mathematical concepts related to the 37% rule in decision-making and job search strategies.

## Project Overview

This project contains interactive Python notebooks analyzing the 37% rule and its connection to optimal decision strategies and randomness. Perfect for developers and data enthusiasts learning about math concepts and their practical applications.

## Notebooks

- **prime_37_job_search_37percentage_rule.ipynb** - Analysis of the 37% rule in job search scenarios

## Prerequisites

- Python 3.14 or higher
- [UV package manager](https://github.com/astral-sh/uv) (for dependency management)

## Quick Start

### 1. Clone the Repository

```bash
git clone <repository-url>
cd final-project
```

### 2. Set Up Environment with UV

This project uses UV to manage Python dependencies. UV is a fast, reliable Python package installer that makes reproducible environments easy.

Install UV (if not already installed):
```bash
# On macOS or Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# On Windows
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### 3. Sync Dependencies

Run UV to install all required packages:

```bash
uv sync
```

This command will:
- Create a virtual environment
- Install all dependencies from `pyproject.toml`
- Create a `uv.lock` file for reproducible installs

### 4. Run Jupyter Notebooks

Start the Jupyter environment:

```bash
uv run jupyter notebook
```

Or with JupyterLab (if preferred):

```bash
uv run jupyter lab
```

Then open the `.ipynb` files in your browser.

## Dependencies

All dependencies are specified in `pyproject.toml`:

- **ipykernel** (≥7.2.0) - Jupyter kernel for Python
- **matplotlib** (≥3.10.8) - Data visualization
- **numpy** (≥2.4.3) - Numerical computing
- **pandas** (≥3.0.1) - Data manipulation and analysis

## Project Structure

```
final-project/
├── README.md                                          # This file
├── pyproject.toml                                     # Project dependencies
├── main.py                                            # Main Python script
├── prime_37_job_search_37percentage_rule.ipynb        # Main analysis notebook
```

## Workflow

1. **Initial Setup**: Run `uv sync` to install dependencies
2. **Development**: Open notebooks with `uv run jupyter notebook`
3. **Reproducibility**: UV automatically manages versions and creates `uv.lock` file
4. **Sharing**: Just clone, run `uv sync`, and you're ready to go!

