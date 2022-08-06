# Instructions:

1. Use Python 3.9 or higher (avoid Microsoft Store version).
2. Install YAPF
    `pip install -U yapf`
3. Add the following lines to your workspace (or user) vscode JSON file:
    ```
    "python.formatting.provider": "yapf",
    "editor.formatOnSave": true,
    ```
4. Install pytest
    `pip install -U pytest`

Keep all code within the `src` folder.
The `test` folder will be used for unit testing. Try to not modify anything inside it.
