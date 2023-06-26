### python_pre-commit-yaml.config

## Requirement
1.[**pre-commit framework**](https://pre-commit.com/)
```sh
pip install pre-commit
```
2.Git init in the project
## Usage
1.**Create pre-commint config file** - Use [this](configs/.pre-commit-config.yaml) already created config
    - This  Configuration set [MyPY](https://www.mypy-lang.org/) and [Ruff](https://beta.ruff.rs/docs/) the check of pre commit


2.**Create a ruff .toml config fil** - Use [this](configs/ruff.toml)

3.**Install the git hook scripts**
```sh
pre-commit install
```

4.**(optional) Run against all the files**
```sh
pre-commit run --all-files
```