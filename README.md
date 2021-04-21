# dotfiles

These are my dotfiles for settings up my macOS from scratch.

## Requirements

- Clean install of macOS Big Sur
- Logged in with Apple ID

## Setting up your Mac

### Oneliner

```
$ sh -c "$(curl -fsSL https://git.io/JOr9h)"
```

Source: https://raw.githubusercontent.com/salvitas/dotfiles/master/install.sh

### Manually

Clone this repository to `~/dotfiles`:

```
$ git clone https://github.com/salvitas/dotfiles.git ~/dotfiles
```

Start the setup:

```
$ cd ~/dotfiles && source install.sh
```

## Fonts

Install Meslo Nerd Font from https://github.com/romkatv/powerlevel10k#manual-font-installation

## Secrets

To add any secrets like `AWS_ACCESS_KEY` or `DIGITALOCEAN_TOKEN` add `~/dotfiles/secrets.zsh` and export your
variables there. This file is NOT added to version control.

Alternatively you could utilize encryption: https://abdullah.today/encrypted-dotfiles/

## Included

- Homebrew
- Oh My Zsh
- Brewfile

## Thanks to...

- https://dotfiles.github.io/
- https://github.com/driesvints/dotfiles
- https://github.com/kevinSuttle/macOS-Defaults
- https://github.com/mathiasbynens/dotfiles
