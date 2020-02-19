# provisioning
Deployment system for dotfiles and software on my personal computers, based around ansible.
[![Build Status](https://travis-ci.org/JacksonCampolattaro/provisioning.svg?branch=master)](https://travis-ci.org/JacksonCampolattaro/provisioning)

### Invoked via:
```
ansible-pull -U <repository url> -K
              ^                   ^
           sets url         enables sudo
```
