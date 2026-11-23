
## Description
This skill is for application/library code, as opposed to test code, both are .py files, so the description can't rely on file extension. Name concrete triggers instead: any Python file that is not under tests/ and not named test_*.py/_test.py

## Body
At least three rules covering naming (snakecase functions/variables, PascalCase classes, `is/has/can boolean prefixes), type hints and docstrings on public functions/classes, and error handling (no bare except:`, no mutable default arguments)

## Template
One compliant and one non-compliant snippet