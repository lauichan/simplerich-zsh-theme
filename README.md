# simplerich-zsh-theme

## Overview

This is an oh-my-zsh theme with informative git status, venv/Anaconda environment info and command execution time.

![demo.png](./readme/demo.png)

The git status is updated immediately after a command is finished or every 10 seconds after the terminal is started.

| Symbol        | Meaning                                                                                                                     |
| ------------- | --------------------------------------------------------------------------------------------------------------------------- |
| `[main]`      | The repository is clean.                                                                                                    |
| `[main +n]`   | There are n staged files.                                                                                                   |
| `[main ●n]`   | There are n changed but unstaged files.                                                                                     |
| `[main …n]`   | There are n untracked files.                                                                                                |
| `[main xn]`   | There are n conflicting files.                                                                                              |
| `[main n\|m]` | The local branch is m commits ahead and n commits behind the remote branch.                                                 |
| `[main *]`    | This will be displayed instead of the informative symbols<br />when python cannot be executed and the repository not clean. |

## Install

```shell
cp ./simplerich.zsh-theme ~/.oh-my-zsh/themes/

nano ~/.zshrc

ZSH_THEME="simplerich"

source ~/.zshrc
```