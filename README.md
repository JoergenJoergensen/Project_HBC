# Project HomeBatteryController

This bachelor project was done by AU Engineering students:
Rasmus Hyldgaard & Jørgen Moesgaard Jørgensen

System that plans use of battery power in the house and when to charge battery from solar cells or from the grid. Using electricity price, expected consumption, expected solar cell power and expected battery level to plan.

Moved from repo: https://github.com/rasmushyldgaard/Project_HBC
Original repo with development and branches deleted to protect user account information.

### Setup development environment
---
Create virtualenv for project: <br>
`python -m venv venv`

Activate virtualenv before installing requirements. <br>
`source venv/Scripts/activate`

Upgrade pip with this cmd <br>
`python.exe -m pip install --upgrade pip`

Install requirements into venv after activating. <br>
`pip install -r requirements.txt` <br>
`pip install -r requirements_dev.txt`

Run this pip cmd to install source code into venv. <br>
`pip install -e .`

Project should be setup locally now for development.

### Testing
---
Make sure to always run `tox` locally and see that it succeeds before pushing and creating pull request on GitHub. Tox will automatically run Pylint, MyPy and Pytests for the entire project.

Run `pytest` to run ALL pytests for the project. To run pytest for a single file use: <br>
`pytest "file_path"`

Be aware that coverage will still cover for all the other source files, so only look at the coverage for the source file being tested.
<br>

Use  `pylint src` to run Pylint on all the source files. <br>
Use  `mypy src` to run MyPy on all the source files.




