# For dev.container install
Requirement
- Docker or Docker-Desktop
- Vscode : with dev-container Extension

Container Feature
- Python3
- [Poetry](https://python-poetry.org/docs/)

## How does it work?
Ref : 
- [Dev-Container](https://code.visualstudio.com/docs/devcontainers/containers)
- Use devcontainer.json , docker-compose.yml > Dockerfile.dev
- For Poetry . we focus on pyproject.toml and poetry.lock [more-info](https://python-poetry.org/docs/basic-usage/)
- pyproject.toml > focus on lib python you want to install


# How to use
### Clone repo and delete .git & change repo folder

``` sh
git clone https://github.com/newkung6/mydev-container.git
```
- remove <kbd>mydev-container/.git</kbd>
- change folder name to new name,project,or repository

### Open new workspace on mydev-container(or folder you rename)directory
- using vscode with extension 'dev container'
- <kbd>Ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd> to open vscode command 
- <kbd>dev container: reopen in container</kbd>

