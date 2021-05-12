Steps:

- install venv
- Setup your Virtual Env (python -m venv venv)
- add to vscode settings to use the venv python ctrl+shift+p (select interpreter)
- install flake8, black, pylint
- activate the linter flake8/pylint with ctrl+shift+p (select linter)
- create .flake8 with your desired ignores
- install pre-commit
- run pre-commit install
- create .pre-commit-config.yaml with all hookers
    - black
    - flake8
    - requirements.txt