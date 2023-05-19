# gh fzf-run GitHub CLI extension
[GitHub CLI](https://cli.github.com/) extension to manage (view, cancel, watch, ...) workflows using fuzzy finding.

## Installation
```
gh extension install nicovince/gh-fzf-run
```
This extension depends on [fzf](https://github.com/junegunn/fzf#readme)

## Usage
```
gh fzf-run watch
```
After you have selected the workflow(s) you are interested in (use tab and shift+tab to select multiple entries), the requested action is passed to `gh run` with the id of the selected workflow.
