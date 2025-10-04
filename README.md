# NumPy & Pandas Assignment

This folder contains the final IPython notebook for a short NumPy and Pandas assignment, plus a minimal `requirements.txt` to reproduce the environment.

The notebook demonstrates the following small exercises:

- Create and reshape a NumPy array containing numbers 1 through 50 and show its transpose.
- Generate 100 random integers (1–1000) and compute mean, median, and standard deviation.
- Build a Pandas Series from a list of fruits and show value counts and unique values.
- Create a sample Pandas DataFrame (Name, Age, Gender, Score), display the top rows, filter rows where Score > 80, and add a derived `Grade` column based on the score.

Files included
- `numpy_pandas_assignment.ipynb` — The final notebook you can open and run in Jupyter.
- `requirements.txt` — Python package list needed to run the notebook (keep this with the notebook).
- `backup/solution.py` — A backup copy of the script version (moved to `backup` for safety).

Which file to submit
- If the grader requests a notebook: submit `numpy_pandas_assignment.ipynb` and `requirements.txt`.

Run the notebook locally (PowerShell)
1. Make sure you have Python 3.8+ installed.
2. From this folder, create and activate a virtual environment and install dependencies:

```powershell
python -m venv .venv
# Activate the venv (PowerShell)
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

3. Start Jupyter Notebook and open the notebook file:

```powershell
jupyter notebook numpy_pandas_assignment.ipynb
```

Notes and tips
- The random numbers are generated with a fixed seed in the notebook to make outputs reproducible.
- The notebook includes printed outputs and short comments so a grader can follow the answers quickly.
- If you want, I can produce a zip containing just the notebook and `requirements.txt` for a neat submission package.

Contact / support
- If anything should be changed in the notebook (more comments, extra tests, or different sample data), I will update it.
