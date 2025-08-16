# Tooling

Keep it simple. Use the minimum tools needed to make steady progress.

## Python libraries (used in this course)

- Numerical/Algebra: `numpy`, `scipy`, `sympy`
- Data/Plotting: `pandas`, `matplotlib`, `seaborn`
- Notebooks: `jupyterlab`

Install via the provided requirements file:

```bash
pip install -r root_files/requirements.txt
```

## Formatting & linting (optional)

- Formatter: `black`
- Linting: `flake8`
- Imports: `isort`

Example (optional):

```bash
pip install black flake8 isort
black .
flake8 .
isort .
```

## Git workflow (suggested)

- Small, frequent commits with clear messages
- One folder per exercise under `submissions/<your-name>/...`
- Keep notebooks/scripts reproducible (record assumptions and steps)

## Tips

- Prefer clarity over cleverness in your code
- Write down formulas and insights next to code cells
- Use plots to build intuition where possible
