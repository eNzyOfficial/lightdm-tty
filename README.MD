# lightdm-tty

## About

A simple terminal style theme for lightdm-webkit2-greeter

[Live demo](https://enzyofficial.github.io/lightdm-tty/index.html)

## Screenshot

![Screenshot](https://github.com/eNzyOfficial/lightdm-tty/blob/master/screenshots/screenshot_1.gif)

## Installation

* `cd /usr/share/lightdm-webkit/themes/`
* `git clone https://github.com/eNzyOfficial/lightdm-tty.git tty`
* `vim /etc/lightdm/lightdm-webkit2-greeter.conf`
* Find `greeter` section and set `webkit-theme` to tty

You can run `./test.sh` to try it out if you like!

### Arch Linux
lightdm-tty is available from the [Arch User Repository (AUR)](https://aur.archlinux.org/packages/lightdm-webkit2-theme-tty-git/). Install it with your favourite AUR helper, for example:

`pacaur -S lightdm-webkit2-theme-tty-git`

If you don't want to use an AUR helper, you can always build the package manually from the PKGBUILD included in the repository.

## Features

* Command history using ↑ and ↓
* Clear input using `ctrl+c`
* Autocomplete using `TAB`

You can lock by using `dm-tool switch-to-greeter` or `dm-tool lock`

## Commands

* `login [user]` - Attempts to login as user
* `passwd` - Attempts to login to locked/current session
* `users` = Lists users
* `ls` - Lists available sessions eg. i3
* `poweroff` - Shuts down machine
* `reboot` - Restarts machine
* `suspend` - Suspends machine
* `clear` - Clears output
* `help` - Lists available commands
* `man [command]` - Shows manual for command
* `motd` - Shows MOTD

## TODO

* Make it more customizable
* Languages
* Layouts

## Contributions

Feel free to make contributions! Suggestions, bug reports and pull requests are welcome.

Thanks for [Tardog](https://github.com/Tardog) for adding it to the AUR

## License

This work is free. You can redistribute it and/or modify it under the terms of the WTFPL (Do What The Fuck You Want To Public License), Version 2, as published by Sam Hocevar. See http://www.wtfpl.net/ for more details.
