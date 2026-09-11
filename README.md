# RA-24-2: Test and Deploy an Application using GitHub Actions

This repository contains the GitHub Actions workflow for Required Assignment 24.2.

## Workflow

`.github/workflows/github-actions-demo.yml` runs on every push and:

1. Prints information about the triggering event, runner OS, branch, and repository.
2. Checks out the repository code (`actions/checkout@v4`).
3. Lists the files in the workspace.
4. Prints the final job status.
