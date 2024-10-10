# Python Unit Tests

## Creates a folder python_calc_unittests and subfolder mycalc

```
poetry new --name mycalc python_calc_unittests
```

## Run the app 

```
cd python_calc_unittests

poetry run python mcalc/main.py
```

## Run UnitTests

```
cd python_calc_unittests
poetry run python -m unittest -v
```

## Creates a wheel file

```
cd python_calc_unittests
poetry build 
```

