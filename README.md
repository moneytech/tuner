# ![icon](docs/logo_01.png) Tuner

## Minimalist radio station player
Discover and Listen to random radio stations while you work.

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
![Screenshot 01](docs/screen_dark_1.2.4.png?raw=true)

## Installation

### elementary OS
[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.louis77.tuner)

### Arch Linux
Arch-based Linux users can find `Tuner` under the name [tuner-git](https://aur.archlinux.org/packages/tuner-git/) in the **AUR**:

```sh
$ yay -S tuner-git`
```
Thanks to [@btd1377](https://github.com/btd1337) for supporting Tuner on Arch Linux!


## Motivation

I love listening to radio while I work. There are tens of tousands of cool internet radio stations available, however I find it hard to "find" new stations by using filters and genres. As of now, this little app takes away all the filtering and just presents me with new radio stations every time I use it.

While I hacked on this App, I discovered so many cool and new stations, which makes it even more enjoyable. I hope you enjoy it too.

## Features

- Uses radio-browser.info catalog
- Presets various selection of stations (random, top, trending, genres)
- Save favourite stations 
- Sends a click count to radio-browser.info on station click
- Sends a vote count to radio-browser.info when you star a station
- DBus integration to pause/resume playing and show station info in Wingpanel

## Upcoming

- More selection screens (Popular networks, Country-specific)
- More filter options (country)
- Community-listening: see what other users are listening to right now
- Other ideas? Create an issue!

## Dependencies

```bash
granite
gtk+-3.0
gstreamer-1.0
gstreamer-player-1.0
libsoup-2.4
json-glib-1.0
libgee-0.8
meson
vala
```

## Building

Simply clone this repo, then:

```bash
meson build && cd build
meson configure -Dprefix=/usr
sudo ninja install
```

## Credits

- [faleksandar.com](https://faleksandar.com/) for icons and colors
- [radio-browser.info](http://www.radio-browser.info) for providing a free radio station directory
- [elementary.io](https://elementary.io) for making Linux enjoyable on the desktop
- [Vala](https://wiki.gnome.org/Projects/Vala) - a great programming language
- [Vala Language Server](https://github.com/benwaffle/vala-language-server) - makes Vala even better
- [@NathanBnm](https://github.com/NathanBnm) - provided French translations
- [@btd1337](https://github.com/btd1337) - supports Tuner on Arch Linux / AUR

### Free Software Foundation

![FSF Member badge](https://static.fsf.org/nosvn/associate/crm/4989673.png)

I'm a member of the Free Software Foundation. Without GNU/Linux and all the great
work from people all over the world producing free software, this project would 
not have been possible.

Consider joining the FSF, [here is why](https://my.fsf.org/join?referrer=4989673).

## Disclaimer

Tuner uses the community-drive radio station catalog radio-browser.info. Tuner
is not responsible for the stations shown or the actual streaming audio content.

