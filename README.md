# API repository (created from template)

This repository was created by the API platform after an approved ServiceNow request. Dummy data only.

| File | Purpose |
|---|---|
| `openapi.yaml` | API definition – validated on every pull request by the central `validate / lint` check |
| `.github/workflows/ci.yml` | Calls the central reusable validation workflow (pinned by commit SHA) |

Changes go through pull requests. Stages are GitHub environments (`dev`, `prod`), not branches.
