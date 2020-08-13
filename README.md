# Your Zsh Is Showing

## Installation

### Install iTerm2
- https://www.iterm2.com/


#### Install a patched font
- [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts)

Set this font in iTerm2 (iTerm → Preferences → Profiles → Text → Change Font) for "Font" and for "Non-ASCII Font". Restart iTerm2.


#### Enable word jumps and word deletion, aka natural text selection

By default, word jumps (option + → or ←) and word deletions (option + backspace) do not work. To enable these, go to "iTerm → Preferences → Profiles → Keys → Load Preset... → Natural Text Editing"

### Install `zsh`:

- Mac: `brew install zsh`
- Linux: `sudo apt-get install zsh`

### Install `oh-my-zsh`:
- https://github.com/ohmyzsh/ohmyzsh

## What does zsh do?

- https://github.com/hmml/awesome-zsh

Since `zsh` is not `bash`, it doesn't use your `~/.bashrc` file anymore.

Instead, it loads the file `~/.zshrc`. All of your zsh configuration should go in here.

Other, non-zsh-related configuration can be placed in a `~/.profile` file, things like:
- Exporting environment variables
- Configuring aliases
- Etc...

Then, in your `~/.zshrc` file, you can include the `~/.profile` by placing the following at the bottom of your `~/.zshrc`:
```
if [ -f ~/.profile ]; then
  source ~/.profile
fi
```

## Configuration & THEMING!!!!

**Plugins** improve the *behaviour* of `zsh`:
- https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins
  - https://github.com/zsh-users/zsh-syntax-highlighting
  - https://github.com/zsh-users/zsh-completions
  - https://github.com/zsh-users/zsh-autosuggestions

**THEMES** improve the LOOKS of `zsh` 🤩:
- Regular ol' zsh themes: https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

- THEMES THAT ARE OVER 9000: https://github.com/Powerlevel9k/powerlevel9k
  - https://github.com/Powerlevel9k/powerlevel9k/wiki/Show-Off-Your-Config
  - https://github.com/Powerlevel9k/powerlevel9k/wiki/stylizing-your-prompt


## More Terminal Goodies

- https://github.com/yaronn/blessed-contrib
  - https://github.com/aksakalli/gtop
  - https://github.com/ampersandre/blessed-contrib-iss-map

- https://github.com/wtfutil/wtf
