# Data Science Stuff

This project is configured for Jupyter notebook development in Cursor.

## Setup Instructions

1. Create a virtual environment (recommended):
```bash
python -m venv venv
```

2. Activate the virtual environment:
- Windows:
```bash
.\venv\Scripts\activate
```
- Unix/MacOS:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Register the IPython kernel:
```bash
python -m ipykernel install --user --name=venv
```

## Using Jupyter Notebooks in Cursor

1. Create new notebooks with the `.ipynb` extension
2. Select the appropriate kernel (venv) when running notebooks
3. Use the integrated terminal for running Jupyter commands

## Project Structure

- `notebooks/`: Directory for your Jupyter notebooks
- `data/`: Directory for your datasets
- `src/`: Directory for Python source code
