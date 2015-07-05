# Hardcode-Tray
Fixes Hardcoded tray icons in Linux

### How to use
  1. Install python3-cairosvg (used in case the original icons are .svg and the hardcoded icons are .png)
  ```bash
    sudo apt-get install python3-cairosvg
  ```

  2. Install the patched version of ```sni-qt``` if you use any QT applications
  ```bash
  sudo add-apt-repository ppa:cybre/sni-qt-eplus
  sudo apt-get update && sudo apt-get dist-upgrade
  sudo apt-get install sni-qt

  ```
  3. Install ```nodejs``` if you use Google Chrome
  ```bash
  sudo apt-get install nodejs nodejs-legacy
  ``` 

  4. Open the script.py using this command (root privileges needed because hardcoded icons are usually in `/opt` or `/usr`)
  ```bash
    sudo python3 script.py
  ```
  
  5. Enjoy!

### Supported applications
We now support:
* [Calendar-indicator](https://bugs.launchpad.net/calendar-indicator)
* [Catch-indicator](https://launchpad.net/~atareao)
* [Cryptfolder-indicator](https://launchpad.net/~atareao)
* [Dropbox](https://www.dropbox.com/)
* [Google Chrome](http://www.google.com/chrome/)
* [Google Music Manager](https://play.google.com/intl/ALL_fr/about/music/)
* [Google-tasks-indicator](https://launchpad.net/~atareao)
* [Grive-tools](https://launchpad.net/~thefanclub/+archive/ubuntu/grive-tools)
* [Keepassx](https://www.keepassx.org/)
* [Megasync](https://mega.co.nz/)
* [My-Weather-Indicator](https://launchpad.net/my-weather-indicator)
* [OwnCloud](https://owncloud.org/)
* [Pomodoro-indicator](https://github.com/malev/pomodoro-indicator)
* [Pushbullet-indicator](https://launchpad.net/~atareao)
* [Prime-indicator](https://github.com/beidl/prime-indicator)
* [Radiotray](http://radiotray.sourceforge.net/)
* [Skype](http://www.skype.com/)
* [Spotify](https://www.spotify.com)
* [Telegram](https://desktop.telegram.org/)
* [Touchpad-indicator](https://launchpad.net/touchpad-indicator)
* [Twitch-indicator](https://github.com/rbrs/twitch-indicator)
* [Variety](http://peterlevi.com/variety/)
* [Xkbmod-indicator](https://github.com/sneetsher/indicator-xkbmod)
* [Yd-tools](https://github.com/slytomcat/yandex-disk-indicator)
* [Youtube-indicator](https://github.com/slytomcat/yandex-disk-indicator)

You can fix [Viber](https://www.viber.com/) using [Viberwrapper-indicator](https://github.com/karas84/viberwrapper-indicator)

If you use an other applications and it's not supported yet? [Report an issue](https://github.com/bil-elmoussaoui/Hardcode-Tray/issues)
