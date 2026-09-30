# README is added

How to create virtual environment

```bash
conda create -n red_wine python=3.9 -y
conda activate red_wine
```

```bash
python -m pip install -r requirements.txt
```

````bash
python -m pip freeze > requirements.txt

# Re-install my requirements for building a package to be reused. This is possible due to setup.py

``` bash
python -m pip install -e .
python -c "import mlProject; print('OK')"
````
