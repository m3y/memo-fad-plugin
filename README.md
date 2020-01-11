# memo-fad-plugin

## Overview
filter and delete

## Install
```
$ cp fad $(memo config --cat | grep pluginsdir | awk -F\" '{print $2}')
```

## Depends on
- [peco](https://github.com/peco/peco)
