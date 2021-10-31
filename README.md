## Efihelper
Efihelper program, works as boot manager assistant on Debian and Ubuntu based systems.

## Dependencies
- Systemd (optional (if systemdboot method selected))
- Lsb-release
- Efibootmgr

## Install
git clone (this repo)

cd debianefistubhelper

sudo install -Dm755 ./efihelper /usr/local/bin/efihelper

## Changelog
v1.1 : Added systemdboot support
     : Some variables fixed
     : Script cleaned
