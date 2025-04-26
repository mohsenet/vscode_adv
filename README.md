# vscode_adv

#### vscode extention
`ms-python.python`<br>
`Django`<br>
`ms-toolsai.datawrangler`<br>

#### Show hiden file and folder 
`Ctrl + h`

#### Python: Select Interpreter
#### brings up the Command Palette
`Ctrl + Shift + p`

#### uv
```bash
uv init
    # .python-version
    # main.py
    # pyproject.toml
    # uv.lock
uv add numpy pandas
uv pip list
uv pip freeze > requirements.txt
# For unistall
uv pip uninstall numpy pandas

# Other way to uninstall
# On Linux
rm -rf venv/lib/python*/site-packages/numpy
# On Windows
del /s /q venv\Lib\site-packages\numpy
```

#### Update vscode
```bash
sudo apt update
sudo apt upgrade code
```
