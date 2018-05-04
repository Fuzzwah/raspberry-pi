## Things I do on my raspberry pi's right after a fresh raspbian flash.

* touch an `ssh` file
* boot the rpi
* `sudo apt-get update; sudo apt-get upgrade -y`
* `sudo raspi-config`
  * update raspi-config
  * change hostname
  * set locale (`en_AU.UTF-8 UTF-8`)
  * set timezone
  * set keyboard
* `sudo apt-get install vim-nox git fish python3 python3-pip python3-virtualenv -y`
* `curl -L https://get.oh-my.fish | fish`
* `omf install bobthefish`
* `set -U theme_color_scheme gruvbox`
