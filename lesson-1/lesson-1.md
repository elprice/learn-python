## Tools
Get setup for python development

### Requirements:
* Install [pyenv](https://github.com/pyenv/pyenv)
    * Install python 3.12
* Install [virtualenv](https://virtualenv.pypa.io/en/latest/)
* Create a git repo
* Create a python script that prints "Hello World"
* Commit the script to github

#### Recommended
* [VSCode](https://code.visualstudio.com/)
    * [Ruff extension](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff) (replaces flake8, black, and isort) 
        * With settings: 
        ```
        "[python]": {
            "editor.formatOnSave": true,
            "editor.codeActionsOnSave": {
                "source.fixAll": "explicit",
                "source.organizeImports": "explicit"
            },
            "editor.defaultFormatter": "charliermarsh.ruff"
        }
        ```
* [oh-my-zsh](https://ohmyz.sh/)
    * Plugins: [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
    * Theme: [powerlevel10k](https://github.com/romkatv/powerlevel10k)
