# Installation Guide

## 1) Create and activate a virtual environment

### Windows (PowerShell)
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### Linux/macOS
```bash
python -m venv .venv
source .venv/bin/activate
```

## 2) Install dependencies

```bash
pip install -r requirements.txt
```

## 3) Run the project

If your main script imports `torchvision` (for example `import torchvision.transforms.functional as TF`), the above install resolves the `ModuleNotFoundError: No module named 'torchvision'` issue.

Run your script with:

```bash
python "Hyperspectral Image Classification and Segmentation.py"
```

Or run the notebook:

```bash
jupyter notebook Assignment4.ipynb
```
