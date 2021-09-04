# Set Up
### Windows
```shell
python -m venv venv
call venv/Scripts/activate.bat
pip install -r requirements.txt
```

### Unix/Linux
```shell
python -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
```


# Testing
### Unit Tests
```shell
tox -e unit
```