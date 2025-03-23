# CHANGELOG

## Create a new version

```sh
python3 -m pip install --upgrade pip
python3 -m pip install --upgrade build
python3 -m pip install --upgrade twine
rm -rf dist/ build/
python3 -m build
# create egg-info folder
python3 -m twine upload dist/* --verbose
# use __token__ auth
# enter token
```

## 2025-03-23

- rewrite the lib with cleaner functions

## 2024-05-31

- add xml tag

## 2023-12-16

- create package
