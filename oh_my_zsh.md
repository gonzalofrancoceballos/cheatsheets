# Install Oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

More info [here](https://ohmyz.sh/#install).


# `.zshrc` file

### To add:
```
source ~/.zshrc.pre-oh-my-zsh
ZSH_DISABLE_COMPFIX="true"
```

### To modify
```bash
ZSH_THEME="avit"
DISABLE_UNTRACKED_FILES_DIRTY="true"
```

# Plugins
Autosuggestions: https://github.com/zsh-users/zsh-autosuggestions

# iTerm2 colorthemes

1. Download theme or clone git repo
2. `iTerm2` -> `Preferences` -> `Profiles` -> `Colors` -> `Color Presets...` -> `import` 

### Cool repos
- Dracula: https://draculatheme.com/iterm
- Cobalt2: https://github.com/wesbos/Cobalt2-iterm