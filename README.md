# Mac Development Ansible Playbook

This playbook installs and configures most of the software I use on my Mac for web and software development.

This playbook will be updated throughout my life with various features, functions and roles - but they will always convey the same purpose.

## Installation

  0. Run the following from the command line
  1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  2. `git clone https://github.com/fubarhouse/mac-dev-playbook ~/.setup`
  3. `cd ~/.setup && ./install.sh`
  4. Enter your administrative password when requested.

## Included Applications / Configuration

Applications (installed with Homebrew Cask):

  - adobe-creative-cloud
  - ccleaner
  - dropbox
  - filezilla
  - firefoxdeveloperedition
  - gitkraken
  - google-chrome
  - google-drive
  - google-hangouts
  - iterm2
  - jetbrains-toolbox
  - kodi
  - steam
  - sublime-text
  - teamviewer
  - tower
  - vagrant
  - virtualbox
  - vlc

Packages (installed with Homebrew):

  - ansible
  - dockutil
  - git
  - go
  - gpg
  - python
  - sqlite
  - mcrypt
  - mysql
  - npm
  - nvm
  - php56
  - php56-mcrypt
  - php56-xdebug
  - ssh-copy-id
  - cowsay
  - ios-sim
  - readline
  - subversion
  - openssl
  - drush
  - wget

My [dotfiles](https://github.com/fubarhouse/mac-dev-playbook-dotfiles) are also installed into the current user's home directory.

## Ansible for DevOps

Check out [Ansible for DevOps](http://www.ansiblefordevops.com/), which will teach you how to do some other amazing things with Ansible.

## Special thanks

[Jeff Geerling](http://jeffgeerling.com/) for creating the amazing [mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook).

## Authors/Contributors

[Karl Hepworth](http://twitter.com/fubarhouse), Making this fork more personalized.

[Jeff Geerling](http://jeffgeerling.com/), 2014 (originally inspired by [MWGriffin/ansible-playbooks](https://github.com/MWGriffin/ansible-playbooks)).
