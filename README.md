# Nvidia Install For Linux
Script that install nvidia driver for linux.
For now it is working with debian 10 and nvidia cards that is support by nvidia driver 450.xx

## Require
Need to install

    # apt-get install curl

## Install

    # curl -L https://github.com/Tirsvad/nvidia-driver-install-for-linux/tarball/master | tar xz -C /root/ --strip-components 2
    # bash nvidiaInstall/install\ nvidia\ driver.sh

### TODO

* More optional nvidia drivers
* Support more distobutions