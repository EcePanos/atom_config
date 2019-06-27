# atom_config
My configuration and packages for the Atom editor.
## Export:

1. Copy from `${user}/.atom`:
 - config.cson
 - keymap.cson
 - snippets.cson
 - styles.less
2. Save installed packages list `apm list --installed --bare > packages.list`


## Import:

Restore packages from `packages.list` mentioned in Backup.2 by:
```
apm install --packages-file packages.list
```
or 
```
apm install 'cat packages.list'
```
