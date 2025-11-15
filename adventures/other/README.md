
#### vscode extention
`ms-python.python`<br>
`Pylance`<br>
`Django`<br>
`ms-toolsai.datawrangler` and `ms-toolsai.jupyter`<br>
`ms-azuretools.vscode-docker`<br>
`ms-kubernetes-tools.vscode-kubernetes-tools`<br>
`eamodio.gitlens`<br>

```text
Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.
ext install ms-python.python
ext install ms-python.vscode-pylance
```

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
#### Find the Python Interpreter Path:
```bash
# This will show you the Python executable path
uv run which python  # On Linux/Mac
uv run where python  # On Windows
```
#### Select Interpreter in VSCode: 
```latex
- Press Ctrl+Shift+P
- Type "Python: Select Interpreter"
- Choose the command from the dropdown
- Select the Python interpreter from your uv environment
```
#### How can I access to Vscode settings:
##### Step 1
```latex
"Ctrl+,"
```
##### Step 2
search parameter (For example, enable typeCheckingMode)
```latex
python.analysis.typeCheckingMode
```

#### Update vscode
```bash
sudo apt update
sudo apt upgrade code
```
