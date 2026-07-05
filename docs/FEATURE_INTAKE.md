# Feature Intake

## Current Request

- Request: Refresh the GitHub profile README and embed a generated CV infographic.
- Classification: Tiny.
- Affected contract: `README.md` renders as the public GitHub profile and references repository-local assets.
- Expected proof: Markdown structure is valid, profile content is internally consistent, the CV infographic asset exists, and `git diff --check` passes.

## Notes

- Keep profile content professional and minimal.
- Avoid extra visual noise, large animated sections, or redundant stats.
- Store generated profile imagery under `assets/` so GitHub can render it from the repository.
