# Reference sheet
[vim](#vim)

### git
| ACTION | COMMAND |
|--------|---------|
|Rename any branch|`git branch -m [old name] [new name]`|
|Rename current branch|`git branch -m [new name]`|
|Prune branches|`git remote prune origin`|
|Squash commits|`git rebase -i master`|
|Stash changes|`git stash`|
|View list of stashed changes|`git stash list`|
|Restore stashed change|`git stash apply [the thing from list]`|

### vim<a name="vim"></a>
| ACTION | COMMAND |
|--------|---------|
|Replace column of text|`Ctrl+V`<br>_Select text_<br>`c`<br>_Type your changes_<br>`Esc`|
Insert line above|`O`|
Insert line below|`o`|
Go to beginning of line|`^` or `0`|
Go to beginning of line and edit|`I`|
Go to end of line|`$`|
Go to end of line and edit|`A`|
