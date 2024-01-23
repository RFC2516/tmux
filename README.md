# Setting up tmux

## Install tmux

apt install tmux

## Install TPM

git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

## Retrieve tmux config file

cd $HOME/.config/
git clone git@github.com:RFC2516/tmux.git

## Start a tmux session

tmux

## Allow TPM to download packages

ctrl-B I

## Source the tmux config

tmux source $HOME/.config/tmux/tmux.conf


