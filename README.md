# Example: Github Issues
This repo is meant showcase how to use github issues

Video: https://www.youtube.com/watch?v=TKJ4RdhyB5Y

Example Repo: https://github.com/kristianhalte/example-github-issues

## Getting Started: Github Issues
Use the `shoppinglist.txt` file as the shopping list that needs modifications

- [x] add item to shopping list
- [x] check default labels
- [x] raise 5 issues with request to add additional items to shopping list
- [x] `resolve` 1 issue with commit
- [x] `fix` 1 issue with commit
- [x] reopen 1 issue with comment
- [x] re-`fix` issue with commit
- [x] `close` 1 issue with commit
- [x] raise 1 issue to existing issue
- [x] `close` parent issue with commit
- [x] re-open parent issue and add child issue
- [x] `fix` child issue and `close` parent issue with commit
- [x] reference issue ID in issue comment
- [x] reference issue ID in commit comment
- [x] reference commit hash in issue comment
- [x] reference commit hash in commit comment

#### Learnings
- can close issues from commit using the following words `Close`, `Closes`, `Closed` ,`Fix`, `Fixes`, `Fixed`, `Resolve`, `Resolves`, `Resolved`
- checkboxes in issue becomes tasks
- can't open issues from tasks, but can reference issue in task
- can't open an issue from a comment

## Further Exploration: Issue Templates
- [x] create a bug template through github UI
- [x] update the bug template through the `.github/ISSUE_TEMPLATE/bug_report.md` file
- [x] raise 1 bug request
- [x] configure template chooser through the `.github/ISSUE_TEMPLATE/config.yml` file

#### Learnings
- only public repos can use `.yml` templates for richer forms for now, but might be coming https://github.com/github-community/community/discussions/4264