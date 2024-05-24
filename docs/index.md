# Workspace

Set of configurations and useful scripts to use anywhere.

## Dotfiles

### Symlink of dotfiles in $HOME

```bash
# Does not work
# ln -sf $(pwd)/dotfiles $HOME/dotfiles

cp ./dotfiles/zsh/.zshrc $HOME/
```