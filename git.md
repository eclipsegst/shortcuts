# Shortcuts for Git
Put the lines below at the end of `~/.bash_profile` or `~/.bashrc`.

```
#Git

alias g='git'
alias gs='git status'
alias gp='git pull'
alias gb='git branch'

alias ga='git add'
alias gc='git commit'
alias gca='git commit --amend'
alias gcm='git commit -m'

alias gco='git checkout'
alias gcom='git checkout master'
alias gcb='git checkout -b'
alias grh='git reset --hard'

alias gr='git rebase'
alias grm='git rebase master'
alias grc='git rebase --continue'
alias grs='git rebase --skip'

alias gcp='git cherry-pick'
alias gdi='git diff'
alias gdiff='git diff'
```