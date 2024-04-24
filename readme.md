# For dev.container install

# Container Feature
- Python3
- [POETRY](https://python-poetry.org/docs/master/#installing-with-the-official-installer).



## Setup
1. Install `poetry`. Read [Installing Poetry with official installer](https://python-poetry.org/docs/master/#installing-with-the-official-installer).

2. Install dependencies.

    ```sh
    poetry install
    ```

3. Activate `virtualenv` with `poetry shell`

    ```sh
    poetry shell
    ```

---

## Build

**Development**:

```sh
docker build -t tks:dev --target development --file docker/Dockerfile .
```

**Production**:

```sh
docker build -t tks --target production --file docker/Dockerfile .

# Or run with script
./scripts/build.sh
```

### How to open dev Container
