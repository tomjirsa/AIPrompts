# Project Setup Prompt for Cursor

Create a Python project with the following specifications:

## Project Requirements

### 1. Python Project with Poetry
- Initialize a Python project using Poetry for dependency management
- Create a proper `pyproject.toml` with project metadata
- Configure Python version (3.11 or higher)
- Set up proper package structure with `__init__.py` files

### 2. Streamlit UI
- Add Streamlit as a dependency
- Create a main Streamlit application file (`app.py` or `main.py`)
- Include a basic Streamlit UI with:
  - A title and description
  - At least one interactive component (e.g., slider, text input, button)
  - Some data visualization (e.g., chart, table)

### 3. Pytest Testing Framework
- Add pytest as a dev dependency
- Create a `tests/` directory with proper structure
- Include at least one example test file
- Configure pytest in `pyproject.toml` with appropriate settings
- Add test coverage configuration

### 4. Makefile
- Create a Makefile with the following targets:
  - `lint`: Run linters (Ruff and Mypy)
  - `format`: Format code with Ruff
  - `type-check`: Run Mypy type checking
  - `test`: Run pytest tests
  - `test-coverage`: Run tests with coverage report
  - `commit-test`: Pre-commit check that runs linters and tests
  - `install`: Install dependencies with Poetry
  - `run`: Run the Streamlit application
  - `clean`: Clean up temporary files and caches

### 5. Documentation
- Create a `docs/` folder
- Include a comprehensive `README.md` in the docs folder with:
  - Project overview
  - Installation instructions
  - Usage guide
  - Development setup
  - Testing instructions
  - Contributing guidelines
- Also create a main `README.md` in the root directory

### 6. Ruff and Mypy Configuration
- Add Ruff as a dev dependency for linting and formatting
- Add Mypy as a dev dependency for type checking
- Configure Ruff in `pyproject.toml`:
  - Set line length
  - Configure select rules
  - Set up ignore patterns if needed
- Configure Mypy in `pyproject.toml`:
  - Enable strict mode or appropriate strictness level
  - Configure paths to check
  - Set up ignore patterns for test files if needed

## Additional Requirements

- Include a `.gitignore` file appropriate for Python projects
- Create a proper project structure with separate directories for:
  - Source code (e.g., `src/` or package name)
  - Tests (`tests/`)
  - Documentation (`docs/`)
- Ensure all Python files have proper type hints
- Include docstrings for functions and classes
- Make the code pass all linters and type checkers

## Expected Project Structure

```
project_root/
├── .gitignore
├── README.md
├── Makefile
├── pyproject.toml
├── poetry.lock
├── docs/
│   └── README.md
├── src/ or package_name/
│   ├── __init__.py
│   └── app.py (Streamlit app)
├── tests/
│   ├── __init__.py
│   └── test_*.py
```

Please create a complete, production-ready project structure with all the above components properly configured and integrated.

