# zsh-environment
This repository contains useful zsh configuration files.
Feel free to customize the configuration files to suit your needs.

It is recommended to install this using [ubuntu-environment](https://github.com/conjikidow/ubuntu-environment.git).

## How to Use (without [ubuntu-environment](https://github.com/conjikidow/ubuntu-environment.git))

1. Clone this repository into your home directory ~/.zsh:
   ```zsh
   $ git clone git@github.com:conjikidow/zsh-environment.git ${HOME}/.zsh
   ```

2. Create .zshenv in your home directory:
   ```zsh
   $ echo "export ZDOTDIR=\"\${ENVDIR}/zsh\"\\nexport HISTFILE=\"\${ZDOTDIR}/.zsh_history\"" > ${HOME}/.zshenv
   ```
