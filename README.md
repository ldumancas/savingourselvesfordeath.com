# Introduction

This repository contains the source code for the Saving Ourselves for Death Masters Ultimate Team website.

# Building
## Manual
In a Debian Linux environment ensure that `git`, `hugo` are installed.
```
# Install Git
sudo apt-get update \
sudo apt-get install git-all

# Install Hugo
sudo snap install hugo \
sudo snap connect hugo:removable-media \
sudo snap connect hugo:ssh-keys
```
Clone the project and then run the command `hugo` from the `./static-site` directory to build the site. To test the site locally use the command `hugo server`.

# Dependencies
- Hugo: https://gohugo.io/installation/
    - Installed via `snap` in WSL Ubuntu 22.04 environment - https://gohugo.io/installation/linux/#snap
- Blowfish: https://blowfish.page/docs/installation/
    - Installed as a `git` submodule - https://blowfish.page/docs/installation/#install-using-git
