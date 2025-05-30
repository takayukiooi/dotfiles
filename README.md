# dotfiles

This is my dotfiles. I use the following development environment.

### Terminal
wezterm

### Shell
zsh

### Editer
neovim

## Useage

Change $ZDOTDIR using `.zshenv`. see [mastering-zsh](https://github.com/rothgar/mastering-zsh/blob/master/docs/config/general.md#files).

```zsh
ln -s ~/dotfiles/zshenv ~/.zshenv

```

```zsh
ln -s ~/dotfiles/zdotdir ~/.config/zdotdir

```

I using [KevinSilvester's config](https://github.com/KevinSilvester/wezterm-config).

```zsh
cd wezterm-config
git submodule update --init
ln -s ~/dotfiles/wezterm-config ~/.config/wezterm
```

Sheldon for zsh plugins.

```zsh
ln -s ~/dotfiles/sheldon/plugins.toml ~/.config/sheldon/plugins.toml
```

Starship for prompt.

```zsh
ln -s ~/dotfiles/starship/starship.toml ~/.config/starship.toml
```
