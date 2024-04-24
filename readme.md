# For dev.container install

# Container Feature
- Python3
- [POETRY](https://python-poetry.org/docs/master/#installing-with-the-official-installer).

# how does it work?
Ref : 
- [dev-container](https://code.visualstudio.com/docs/devcontainers/containers)
- use devcontainer.json , docker-compose.yml > Dockerfile.dev
- For Poetry . we focus on pyproject.toml and poetry.lock [more-info](https://python-poetry.org/docs/basic-usage/)
- For pyproject.toml > focus on lib python you want to install


# How to use
### clone repo and delete .git & change repo folder
- git clone https://github.com/newkung6/mydev-container.git
- rm mydev-container/.git
- change folder name to new name,project,or repository

### open new workspace on mydev-container(or folder you rename)directory
- using vscode with extension 'dev container'
- ctrl + shift + p 
- "dev container: reopen in container"

