# SE-Git-hw
My Software Engineering Course Assignment - 01

The repository demonstrates basic Git and GitHub workflows: version control, branching, pull requests, merge conflict, and issue tracking.

## Files

|    File     | Description |
|-------------|-------------|
| `hello.py`  | Prints a "Hello, World!" greeting. Created for the initial commit. |
| `apple.py`  | Prints "I eat apple". Added on the `feature-1` branch. |

## Running the programs

```bash
python3 hello.py
python3 apple.py
```

## Branches

|    Branch    | Purpose |
|--------------|---------|
|    `main`    | Primary branch holding the merged work. |
| `feature-1`  | Added `apple.py`. Merged into `main` via pull request #1, then deleted. |
| `conflict-a` | Edits the greeting in `hello.py` one way. |
| `conflict-b` | Edits the same line differently, producing a conflict with `conflict-a`. |

## Pull requests

- **#1** — merged `feature-1` into `main` after review by two classmates.
- **#2** — merged `conflict-b` into `conflict-a`, resolving a deliberate merge conflict in `hello.py`.

## Issues
- **#3** — Expand README with project description and usage instructions (assigned to myself).
- **#4** — Confirm the repository is publicly accessible (assigned to a classmate).

## Author

Alvi Anowar
