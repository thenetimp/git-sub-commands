This project contains a series of bash scripts that are executed through GIT.  To use these scripts clone or download this repo and add the path to it to your shell's $PATH.  Then you can call it like

```
git [script shortcut]
```

for exampe the "git-rtag" script would be 

```
git rtag [script options]
```


## List of scripts and their functions
git-rtag - this script is used to version releases.

git-cbrtag - this script is used to help manage chef cookbook versions.  It keeps the 
             GIT repository version in sync with the chef cookbook version in metadata.rb