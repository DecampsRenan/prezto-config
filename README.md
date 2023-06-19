# Personnal config forked from prezto

Prezto is the configuration framework for [Zsh][1]; it enriches the command line
interface environment with sane defaults, aliases, functions, auto completion,
and prompt themes.

```sh

# First, clone the repo into a .zprezto/ folder at $HOME
git clone --recursive git@github.com:DecampsRenan/prezto-config.git "${ZDOTDIR:-$HOME}/.zprezto"

# .zshrc file should only link to the custom config files, nothing more
echo 'source "${ZDOTDIR:-$HOME}/.zprezto/init.zsh"' > .zshrc
```
