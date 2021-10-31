## Efihelper
Efihelper program, works as boot manager assistant on Debian and Ubuntu based systems.
<p>&nbsp;</p>

## Dependencies
- Systemd (optional (if systemdboot method selected))
- Lsb-release
- Efibootmgr
<p>&nbsp;</p>

## Install
git clone (this repo)

cd debianefistubhelper

sudo install -Dm755 ./efihelper /usr/local/bin/efihelper
<p>&nbsp;</p>

## Usage
#### Initial setup:
sudo efihelper first 
<p>&nbsp;</p>

#### Install new kernel entry:
```sudo efihelper install $(uname -r)```
or
```sudo efihelper install 5.14.15-xanmod1```
<p>&nbsp;</p>

#### Remove kernel entry:
```sudo efihelper remove $(uname -r)```
or
```sudo efihelper remove 5.14.15-xanmod1```
<p>&nbsp;</p>

## Changelog
v1.1 : Added systemdboot support
     : Some variables fixed
     : Script cleaned
