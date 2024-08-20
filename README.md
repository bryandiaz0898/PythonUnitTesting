git remote set-url origin git@github.com:bryandiaz0898/PythonUnitTesting.git

## PythonUnitTesting
This repo is created to learn and practice Unit Testing with Python (pytest, unittest)

# Pytest Video
https://www.youtube.com/watch?v=bbp_849-RZ4

# Creating a VENV (Vitual Environment) Use below link
https://docs.python.org/3/library/venv.html


python -m venv C://Users//bryan//PythonVenvs//UnitTest

C://Users//bryan//PythonVenvs//UnitTest

## UNIT TESTING

# -v (Verbose) -k (Keyword)
py.test -v -k "add"

pytest <file> -v -k "add or string"
pytest <file> -v -k "add and string"


# -m (mark expression)

pytest <file> -m string
@pytest.mark.string

pytest <file> -m number
@pytest.mark.number

# -x (exit when first failure occurs)
pytest -v -x

To remove text trace you can use the below command
pytest -v -x --tb=no