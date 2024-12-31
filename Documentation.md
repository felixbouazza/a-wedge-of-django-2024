# Install UV

[UV](https://docs.astral.sh/uv/)

### Linux / MACOS
```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Windows
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Init project

```
uv init -p 3.13 --name a-wedge-of-django --app --author-from git
```

### Install Django

```
uv add 'Django'
```

### Verify installation

```
uv run django-admin --version
```

### Lint

```
uv tool install ruff
```

```
uv tool run ruff check --fix
uv tool run ruff format
```

### Setup a django project

```bash
uv run django-admin startproject a_wedge_of_django .
```