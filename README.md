# git-aliases
My git aliases

```
[alias]
  co = checkout
  purr = pull --rebase
  ready = rebase -i @{u}    # for pure git repos with remotes
  ready = !sh git-ready     # for git to svn, will rebase to most recent svn commit
  st = status -sb
  po = push origin
  lg = log --pretty=format:'%Cred%h%Creset -%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'
  ai = add -i
  logg = log --pretty=format:'%h - %s %b - %an - %cd'
  
```
