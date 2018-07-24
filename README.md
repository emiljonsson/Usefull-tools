# Usefull-tools
Repository with small and useful scripts and tools


## Usefull commands

### Get number of lines in git repository (ignoreing lines from files in git ignore)

```
git ls-files | xargs wc -l
```

### Nicer looking git log (tip: u can make an alias for the git command by pasteing the second line into the terminal)

```
git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
```
Make alias:
```
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
```
If you want to see changed lines:

```
git lg -p
```
