# gh fzf-run GitHub CLI extension
[GitHub CLI](https://cli.github.com/) extension to manage (view, cancel, watch, ...) workflows using fuzzy finding.

## Installation
```
gh extension install nicovince/gh-fzf-run
```
This extension depends on [fzf](https://github.com/junegunn/fzf#readme)

## Usage
```
gh fzf-run
```
Commands available:
- `ctrl-a`: Abort workflow
- `ctrl-w`: watch workflow
- `ctrl-v`: View workflow
- `ctrl-j`: Show jobs of workflow
