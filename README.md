# ci-smoke-lab-7
Throwaway sandbox for release-readiness CI smoke test

## Build artifact

This repo runs a GitHub Actions workflow on demand. The workflow writes commit
metadata to a short text file (`artifact.txt`) and uploads it as a build
artifact named **demo-build**.
