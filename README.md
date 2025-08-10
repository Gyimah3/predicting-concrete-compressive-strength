## Concrete Compressive Strength - Phase 1 (EDA)

This project performs comprehensive exploratory data analysis for predicting concrete compressive strength using the dataset `DATA 3 - concrete_data.csv` (provided in this folder).

### Setup
1. Ensure Python 3.9+ is installed.
2. Create and activate a virtual environment (recommended):
   - macOS/Linux:
     ```bash
     python3 -m venv .venv && source .venv/bin/activate
     ```
   - Windows (PowerShell):
     ```powershell
     python -m venv .venv; .venv\\Scripts\\Activate.ps1
     ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Run the notebook
```bash
jupyter notebook eda_concrete_strength.ipynb
```

The notebook will:
- Load and validate the dataset
- Assess data quality (missing values, duplicates, types)
- Visualize distributions and correlations
- Provide advanced insights by cement type and age
- Save a cleaned dataset to `concrete_cleaned.csv`
