# hezi-ci-demo

A tiny, self-contained demo for onboarding: it walks through the full loop of
making a commit, letting CI run automatically on push, and verifying the result.

## What it demonstrates

1. A commit lands on the default branch.
2. A GitHub Actions workflow (`.github/workflows/ci.yml`) triggers on every push.
3. The workflow runs on `ubuntu-latest` and echoes the marker `CI-DEMO-PIPELINE-OK`,
   which you can confirm in the job logs.

If you see the marker in the Actions job log, the pipeline is working.
