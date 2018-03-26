# Usefull-tools
Repository with small and useful scripts and tools


## Usefull commands

### Get number of lines in gut repository (ignoreing lines from files in git ignore)

```
git ls-files | xargs wc -l
```

### Nicer looking git log (tip make it into a alias like git lg)

```
git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
```
