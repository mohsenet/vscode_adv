
#### vscode extention
`ms-python.python`<br>
`Django`<br>
`ms-toolsai.datawrangler` and `ms-toolsai.jupyter`<br>
`ms-azuretools.vscode-docker`<br>
`ms-kubernetes-tools.vscode-kubernetes-tools`<br>
`eamodio.gitlens`<br>

---

#### brings up the Command Palette
`Ctrl + Shift + p`

#### Python: Select Interpreter

#### Show hiden file and folder 
`Ctrl + h`

---

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
