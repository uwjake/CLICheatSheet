# CLICheatSheet

## Count lines of code in a repo
```
git ls-files | grep ".swift" | xargs wc -l
```

## Get IP Address
```
ifconfig | grep inet
```

## List Sizes of Items in Folder
```
du -sh */ | sort -rn
```
-s one line per file/dir; -h human readable

For hidden items:
```
du -sh .[^.]*
```
