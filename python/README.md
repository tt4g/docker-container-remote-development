# Python container

## Example 

* devcontainer.json

  ```json
  {
      "name": "Python 3.8",
      "dockerFile": "Dockerfile",
      "settings": {
          "terminal.integrated.shell.linux": "/bin/bash",
          "python.pythonPath": "/usr/local/bin/python",
          "python.linting.pylintPath": "/usr/local/bin/pylint",
          "python.linting.pylintEnabled": false,
          "python.linting.flake8Enabled": true,
          "python.linting.mypyEnabled": true,
          "editor.formatOnSave": true,
          "python.linting.lintOnSave": true
      },
      "extensions": [
          "ms-python.python"
      ]
  }
  ```
