#### Build Pipeline status
- ![Linting](https://github.com/mmclane/actions-experiment/actions/workflows/linting.yaml/badge.svg)
- ![Precommit Checks](https://github.com/mmclane/actions-experiment/actions/workflows/precommit-checks.yaml/badge.svg)
- ![Build](https://github.com/mmclane/actions-experiment/actions/workflows/build.yaml/badge.svg)


Things I wanna figure out:
- [ ] Running a workflow on a subfolder but only when changes are in that subfolder
- [x] Status flags in the readme?
- [ ] Should we use Make??



refs:
- https://github.com/dorny/paths-filter
- https://www.datacamp.com/tutorial/makefile-github-actions-tutorial
- https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge 
 

## Status badges
You can build the URL for a workflow status badge using the name of the workflow file:

https://github.com/OWNER/REPOSITORY/actions/workflows/WORKFLOW-FILE/badge.svg
