# dotfiles

My personal configuration files and scripts.

I use [yadm](https://github.com/TheLocehiliosan/yadm) to manage the dotfiles.

## Installation

On a fresh OS

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" &&
brew install yadm &&
yadm clone --bootstrap git@github.com:Mellbourn/dotfiles.git &&
sudo .yadm/bootstrap-sudo &&
yadm decrypt
```
