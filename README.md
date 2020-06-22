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

## Change owner
```
chown -R user directory/
```
-R: includes all files underthis directory

## chmod
[https://ss64.com/bash/chmod.html](https://ss64.com/bash/chmod.html)

## Mark Down
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Hardware Info
Get Kernel and version
```
uname -v
```
* -a: all
* -n: Network Node Hostname
* -m: Machine Hardware Architecture (i386, x86_64, etc.)

Specifically for Mac:
```
sysctl machdep.cpu.brand_string
```

```
document.querySelectorAll('style,link[rel="stylesheet"]').forEach(item => item.remove())
```
