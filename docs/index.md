# Workspace

Set of configurations and useful scripts to use anywhere.

## Dotfiles

## Change Shell to zsh

```bash
chsh $(echo $USER)
# change to: /bin/zsh
# Check - Should be /bin/zsh
echo $SHELL
```

### Symlink of dotfiles in $HOME

```bash
# Does not work
# ln -sf $(pwd)/dotfiles $HOME/dotfiles

cp ./dotfiles/zsh/.zshrc $HOME/
```