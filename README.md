setup
```sh
mkvirtualenv --python $(which python3) $(basename $(pwd))
pre-commit install
pre-commit install-hooks

pip install ipython  # everybody <3 REPL
```

run
```sh
F="main.py" air
```

optional/run all pre-commit hooks
```sh
pre-commit run -a # --all-files
```
