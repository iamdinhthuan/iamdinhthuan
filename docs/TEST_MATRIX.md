# Test Matrix

| Area | Validation | Command |
| --- | --- | --- |
| README formatting | Check patch whitespace and conflict markers | `git diff --check` |
| README content | Inspect rendered-source structure and links | `sed -n '1,220p' README.md` |
| Task state | Confirm changed files before handoff | `git status --short` |
