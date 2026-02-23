# go-example

Minimal Go repository used to validate Janitor behavior.

## Files

- `main.go`: small runnable program
- `go.mod`: module definition
- `.github/workflows/janitor.yml`: Janitor GitHub Actions workflow

## Run locally

```bash
go run .
```

## Validate Janitor locally

From this directory, run:

```bash
janitor --no-commit
```

## CI behavior

`janitor.yml` runs on pushes and pull requests to `main` and executes Janitor in `no_commit` mode.
