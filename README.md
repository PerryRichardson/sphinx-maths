# Sphinx Maths

A Python maths package with professional documentation generated using Sphinx.

## Project Structure
```
sphinx_maths/
    maths/
        __init__.py
        add.py
        divide.py
        multiply.py
        subtract.py
    docs/
        conf.py
        index.rst
```

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/PerryRichardson/sphinx-maths.git
cd sphinx-maths
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Sphinx
```bash
pip install -U sphinx
pip install sphinx-rtd-theme
```

### 4. Generate the documentation
```bash
cd docs
.\make.bat html
```

### 5. View the documentation
Open `docs/_build/html/index.html` in your browser.