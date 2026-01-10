# Simple Python Project Template

I made this so I can just reuse this template for any simple python projects

## Project Structure

```
project-root/
 ├── src/
 │ ├── __init__.py
 │ ├── main.py
 │ └── utils.py
 ├── test/
 │ ├── __init__.py
 │ └── test_utils.py
 ├── requirement.txt
 ├── .gitignore
 └── README.md
```

## Setup Instructions

### 1. Copy project folder

### 2. Delete `venv/` folder

### 3. Create a virtual environment

```
    python -m venv venv
```

### 4. Activate virtual environment

**Windows**

```
venv/Scripts/activate
```

**Mac/Linux**

```
source venv/bin/activate
```

### 5. Install dependencies

```
pip install -r requirements.txt
```

## Running the project & test

```
python src/main.py
pytest
```

- pytest should automatically search for tests in the `tests/` folder
- Test files/functions must start with `test_`

## Adding new dependencies

Install through pip and add it to `requirements.txt`
