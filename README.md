# Sound Trimmer

## Description

sound-trimmer is a command-line program to trim video and audio. It runs on Bash interpreter. It should work on your Linux Debian based distros. You can modify it, redistribute it or use it however you like.

## Installation

To install it right away for all Debian based LINUX users type:

    git clone https://github.com/nazmulchowdhury/sound-trimmer.git
    sudo mv sound-trimmer/sound-trimmer /usr/bin
    sudo chown root:root /usr/bin/sound-trimmer
    sudo chmod 755 /usr/bin/sound-trimmer
    sudo rm -fr sound-trimmer
    
## Usage

    sound-trimmer <file-name> <hh:mm:ss> <hh:mm:ss>
