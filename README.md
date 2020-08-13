🌟🌟🌟 = You **gotta** do this

# Your Zsh Is Showing

## Installation

### Install iTerm2
- https://www.iterm2.com/

#### 🌟🌟🌟 Enable word jumps and word deletion, aka natural text selection

By default, word jumps (option + → or ←) and word deletions (option + backspace) do not work. To enable these, go to "iTerm → Preferences → Profiles → Keys → Load Preset... → Natural Text Editing"

### Install `zsh`:

- Mac: `brew install zsh`
- Linux: `sudo apt-get install zsh`

### Install `oh-my-zsh`:
- https://github.com/ohmyzsh/ohmyzsh

## What does zsh do?

- https://github.com/hmml/awesome-zsh

Since `zsh` is not `bash`, it doesn't use your `~/.bashrc` file anymore.

[Instead](https://unix.stackexchange.com/a/487889), it loads the file `~/.zshrc`. All of your zsh configuration should go in here.

Other, non-zsh-related configuration can be placed in a `~/.zprofile` file, things like:
- Exporting environment variables
- Configuring aliases
- Etc...

If you have any environment setup already in an existing `.bashrc` or `.bash_profile`, you may want to move it into `~/.zprofile`


## Configuration & THEMING!!!!

**Plugins** improve the *behaviour* of `zsh`:
- https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins
  - https://github.com/zsh-users/zsh-syntax-highlighting
  - https://github.com/zsh-users/zsh-completions
  - 🌟🌟🌟 https://github.com/zsh-users/zsh-autosuggestions

**THEMES** improve the LOOKS of `zsh` 🤩:
- Regular ol' zsh themes: https://github.com/ohmyzsh/ohmyzsh/wiki/Themes


- THEMES THAT ARE OVER 9000: https://github.com/Powerlevel9k/powerlevel9k

  - Install a patched [Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts)
    - Set this font in iTerm2 (iTerm → Preferences → Profiles → Text → Change Font) for "Font" and for "Non-ASCII Font". Restart iTerm2.
  - https://github.com/Powerlevel9k/powerlevel9k/wiki/Show-Off-Your-Config
  - https://github.com/Powerlevel9k/powerlevel9k/wiki/stylizing-your-prompt


## More Goodies

- 🌟🌟🌟 https://www.spectacleapp.com/
- https://github.com/wtfutil/wtf
- https://github.com/yaronn/blessed-contrib
  - https://github.com/aksakalli/gtop
  - https://github.com/ampersandre/blessed-contrib-iss-map
