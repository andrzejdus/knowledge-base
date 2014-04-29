### Commands

Interactive stash
* stash -p 

Switch to previous branch
* git checkout -

Remove remote branch
* git push origin :the_remote_branch

Perserve merges on rebase
* git rebase --preserve-merges

Exclude commit from git log by regexp
* e.g. git log --color=always -z | awk -v RS=\\0 '!/Author:.*fugly.com>/ && /Date:.* Sun /'

### Links
[Difference between HEAD / Working Tree / Index in Git](http://stackoverflow.com/questions/3689838/difference-between-head-working-tree-index-in-git)
