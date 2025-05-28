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
ln -s ./zshenv ~/.zshenv

```

```zsh
ln -s ./zdotdir ~/.config/zdotdir

```

I using [KevinSilvester's config](https://github.com/KevinSilvester/wezterm-config).

```zsh
ln -s ./wezterm ~/.config/wezterm
```

Sheldon for zsh plugins.

```zsh
ln -s ./sheldon/plugins.toml ~/.config/sheldon/plugins.toml
```

Starship for prompt.

```zsh
ln -s ./starship/starship.toml ~/.config/starship.toml
```
