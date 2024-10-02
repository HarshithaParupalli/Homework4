Setup Instructions
Clone the repo
CD into the project folder
Create the virtual environment
Activate the virtual environment (VE)
Install Requirements
Test Commands
pytest run all tests
pytest tests/test_main.py <- Run just the tests in this file
pytest --pylint --cov <- Run Pylint and Coverage (Can be run independently)
Current Libraries Installed
Pytest - Testing Framework
Faker - Fake Data Creation
Pytest Coverage
Pytest Pylint
Adding Library
Make sure you are in the correct VE, if not sure run "deactivate"
Activate the VE
Run pip freeze > requirements.txt
