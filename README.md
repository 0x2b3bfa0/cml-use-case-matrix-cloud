# Matrix use case

See [`cml.yml`](https://github.com/0x2b3bfa0/cml-use-case-matrix-cloud/blob/e8a01424cec9f4bb2100041db0f7698e58484ae0/.github/workflows/cml.yml) for more information.

## Secrets

### GitHub

- [`REPO_TOKEN` — personal access token](https://cml.dev/doc/self-hosted-runners?tab=GitHub#pat)

### Amazon Web Services

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`
- `AWS_SESSION_TOKEN` (optional)

See [the documentation](https://cml.dev/doc/self-hosted-runners?tab=AWS#cloud-compute-resource-credentials) for more information.

##  Matrix

See [`matrix.json`](https://github.com/0x2b3bfa0/cml-use-case-matrix-cloud/blob/e8a01424cec9f4bb2100041db0f7698e58484ae0/matrix.json) for more information.

## Issues

### Name collisions with `cml pr`

```
git push --set-upstream origin main-cml-pr-c6c7c776

To https://github.com/0x2b3bfa0/test

! [remote rejected] main-cml-pr-c6c7c776 -> main-cml-pr-c6c7c776 (cannot lock ref 'refs/heads/main-cml-pr-c6c7c776': reference already exists)

error: failed to push some refs to 'https://github.com/0x2b3bfa0/test'
```
