A minimalist Vim plugin manager.

## Installation

### Vim

#### Unix

```sh
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Usage

Add a vim-plug section to your `~/.vimrc`

## Commands

| Command                             | Description                                                       |
| ----------------------------------- | ----------------------------------------------------------------- |
| `PlugInstall [name ...] [#threads]` | Install plugins                                                   |
| `PlugUpdate [name ...] [#threads]`  | Install or update plugins                                         |
| `PlugClean[!]`                      | Remove unlisted plugins (bang version will clean without prompt)  |
| `PlugUpgrade`                       | Upgrade vim-plug itself                                           |
| `PlugStatus`                        | Check the status of plugins                                       |
| `PlugDiff`                          | Examine changes from the previous update and the pending changes  |
| `PlugSnapshot[!] [output path]`     | Generate script for restoring the current snapshot of the plugins |
