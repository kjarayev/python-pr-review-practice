
## Description
Name concrete triggers, files under tests/, files matching test_*.py/_test.py, or files that import pytest.

## Body
At least three rules covering naming (test_* function names that describe the behavior under test), fixtures (prefer fixtures over duplicated setup code), and isolation (mock external calls, network, DB, filesystem, instead of hitting real services; no test depends on another test's side effects).

## Template
One compliant and one non-compliant test snippet
