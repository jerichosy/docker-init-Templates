# Notes

### `.dockerignore`

- Wildcards (`*`) mean zero-to-many.
  Example:
  - `venv*` will ignore files and dirs whose names start with `venv` like `venv` and `venv2`.
  - `*.out` will ignore `.out` and `a.out`.
- https://stackoverflow.com/questions/59413516/what-do-two-asterisks-mean-in-a-dockerignore-file
