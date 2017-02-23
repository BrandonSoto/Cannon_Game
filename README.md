# Cannon Chaos

[![Build Status](https://travis-ci.org/BrandonSoto/Cannon_Game.svg?branch=master)](https://travis-ci.org/BrandonSoto/Cannon_Game) [![Code Climate](https://codeclimate.com/github/BrandonSoto/Cannon_Game/badges/gpa.svg)](https://codeclimate.com/github/BrandonSoto/Cannon_Game) [![Issue Count](https://codeclimate.com/github/BrandonSoto/Cannon_Game/badges/issue_count.svg)](https://codeclimate.com/github/BrandonSoto/Cannon_Game) [![Known Vulnerabilities](https://snyk.io/test/github/brandonsoto/cannon_game/badge.svg)](https://snyk.io/test/github/brandonsoto/cannon_game) [![bitHound Dev Dependencies](https://www.bithound.io/github/BrandonSoto/Cannon_Game/badges/devDependencies.svg)](https://www.bithound.io/github/BrandonSoto/Cannon_Game/master/dependencies/npm)


A game where you shoot a canon and enjoy the ensuing chaos.

## How to Build Project

There are two options for building and developing the project. Feel free to use either approach. Please keep in mind that `browserSync` is pretty slow when running from the Vagrant VM.

#### Local Machine Setup

```bash
# install necessary packages (Ubuntu 16.04)
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
sudo apt-get install ruby-dev
sudo npm install -g gulp

cd project-directory

# install local project packages
npm install

# builds the project
# any changes to the code will now be automatically validated and reloaded in the browser
gulp dev
```

#### Vagrant

```bash
cd project-directory

# set up and connect to vagrant VM
vagrant up
vagrant ssh

# go to shared folder
cd /vagrant

# install local project packages
npm install

# builds the project
# any changes to the code will now be automatically validated and reloaded in the browser
gulp dev
```


## Authors
- Matt Moore
- Brandon Soto
- Josh Rueschenberg
