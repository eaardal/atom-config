# atom-config

```
$ git clone https://github.com/eaardal/atom-config.git
```

## Windows symlink

```
$ mklink /J {this-git-repo-path}\.atom C:\Users\{username}\.atom
```

## Linux symlink

```
$ sudo ln -s {this-git-repo-path}/.atom /home/{username}/.atom
```

## Synchronize packages

1. `apm install package-sync`
2. In Atom: `ctrl+shift+p` `"Package Sync: Sync"`
