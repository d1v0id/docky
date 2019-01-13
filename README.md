This is fork of https://launchpad.net/docky

Docky is a full fledged dock application that makes opening common applications and managing windows easier and quicker. Docky is fully integrated into the GNOME Desktop and features a no non-sense approach to configuration and usage. It just works.

### How to build deb package:
```shell
$ sudo apt build-dep docky
$ dpkg-buildpackage -rfakeroot -uc -b
$ sudo dpkg -i ../docky_X.X.X.X-X_all.deb
```
