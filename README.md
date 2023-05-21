
# Debian packages for LXQt 1.3

## About

This is an **unofficial** repository containing LXQt `.deb` files for Debian unstable and testing.

Any packaging bugs can be reported here. Upstream bugs should be reported there: https://github.com/lxqt/.

## Installing

First you have to add the repository to /etc/apt/sources.list.d/. 

> sudo echo "deb [signed-by=/etc/apt/trusted.gpg.d/lxqt13.gpg.key] https://severusseptimius.github.io/lxqt13 ./" > /tmp/S7.list
> 
> sudo cp /tmp/S7.list /etc/apt/sources.list.d/

Than download the public key:

> sudo wget https://raw.githubusercontent.com/severusseptimius/severusseptimius.github.io/main/lxqt13/lxqt13.gpg.key -P /etc/apt/trusted.gpg.d/

And finally update and enjoy:

> sudo apt update && sudo apt full-upgrade

**NOTE**: In order for the update to be complete, you *must* use `apt full-upgrade` instead of `apt upgrade`.
