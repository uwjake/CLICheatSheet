# CLICheatSheet

## Count lines of code in a repo
```
git ls-files | grep ".swift" | xargs wc -l
```


## List Sizes of Items in Folder
```
du -sh */ | sort -rn
```
-s: one line per file/dir;
-h: human readable

For hidden items:
```
du -sh .[^.]*
```

## Change Owner
```
chown -R user directory/
```
-R: includes all files underthis directory

## Change Mode
https://ss64.com/bash/chmod.html[https://ss64.com/bash/chmod.html]

## Get IP Address
```
ifconfig | grep inet
```
