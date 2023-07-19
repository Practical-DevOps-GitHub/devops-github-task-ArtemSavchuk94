# Task on GitHub Topic

1. Add user `softservedata` to this repository.

2. Create branch `develop` as default branch.

3. Protect branches `main` and `develop` with these rules:
- user can't merge to both branches without pull request
- allowed to merge to `develop` branch only if we have 2 approvals
- merge to `main` branch allowed if only owner approved PR
- assign the user `softservedata` as the code owner for all the files in the `main` branch
4. Add template (pull_request_template.md) to `.github` directory for creating issue in format:

## Describe your changes

## Issue ticket number and link

## Checklist before requesting a review
- [ ] I have performed a self-review of my code
- [ ] If it is a core feature, I have added thorough tests
- [ ] Do we need to implement analytics?
- [ ] Will this be part of a product update? If yes, please write one phrase about this update
