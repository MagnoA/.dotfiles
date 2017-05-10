# My Dotfiles

>Create a directory named workstation and clone this repository in there.

## Utilities to install with i3

* i3 -> The main window manager package

* i3status -> Generate a string with information to be displayed in the i3bar

* rofi -> Launch our apps in the i3 desktop

* i3lock -> Screen locker

* xbacklight -> Set laptop's screen brightness

* feh -> Set wallpapers

## Other Utilities

* Mackup

* Git -> Version control system

* zip unzip -> Deal with .zip files

* arandr -> Configuring multi-monitor and resolution

* inconsolata -> Font

* xorg-server

* nvidia - Video drivers

* npm

* gem

* conky -> Display computer information

* libreoffice

* networkmanager network-manager-applet - Network Manager

* Oh My Zsh (https://github.com/robbyrussell/oh-my-zsh) - Base configuration for Zsh

## Vim Plugins Requirements

>Do all of this before doing :PlugInstall

### Base16-vim

* Setting terminal to 256 colors scheme

* git clone https://github.com/chriskempson/base16-shell.git ~/.config/base16-shell

* In ~/.bashrc or ~/.zshrc place the following lines:

BASE16_SHELL=$HOME/.config/base16-shell/

[ -n "$PS1" ] && [ -s $BASE16_SHELL/profile_helper.sh ] && eval "$($BASE16_SHELL/profile_helper.sh)"

* Start a new shell and then type base16(*tab completion*) and
 select what you want (*Base16-vim Plugin uses Monokai*)

### Youcompleteme

* Install development tools ad CMAKE:
  * build-essential
  * cmake

* Install Python headers:
  * python-dev
  * python3-dev

### Syntastic

* Checkers:
  * C - gcc
  * C++ - gcc
  * html - tidy
  * python - flake8
  * markdown - mdl
