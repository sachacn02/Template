# Project Name

## 1. Initial Setup
Run these commands immediately after creating a new repository from this template:

```bash
# 1. Create and activate a virtual environment (Conda recommended for data science)
conda create -n my_project python=3.12
conda activate my_project

# 2. Rename your package directory (if desired)
mv src/my_package src/your_actual_project_name
# Note: If you rename the folder, you must also update `name = "..."` in pyproject.toml

# 3. Install the project and development dependencies
pip install -e ".[dev]"

# 4. Activate Git hooks for automatic formatting
pre-commit install

## 2. Adding new packages

Add your packages to pyproject
dependencies = [
    "pandas>=2.0.0",
    "scikit-learn",
]

Sync your environnement

pip install -e ".[dev]"
