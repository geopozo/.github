# GeoPozo

## Spanish

Hay tres checkeos en cualquier pull request:

1. ruff-lint
2. pytest
3. Que la salida de los notebooks está borrada

1 y 2 son tareas para ustedes (pista: ejecuta `pytest` para ejecutar pytest=.

De 3, se puede installar [este hook (guancho)](../pre-commit):

```bash
cp /directorio/a/descargas/pre-commit /directorio/a/repo/.git/hooks/
chmod +x /directorio/a/repo/.git/hooks/pre-commit
```

## English

There are three checks on any pull request:

1. ruff-lint
2. pytest
3. verification that notebook output is cleared

Number 1 and 2 are left as an exercise to you (hint: run `pytest` to run pytest).

For number 3, feel free to install [this hook](../pre-commit):

```bash
cp /path/to/downloads/pre-commit /path/to/repo/.git/hooks/
chmod +x /path/to/repo/.git/hooks/pre-commit
```
