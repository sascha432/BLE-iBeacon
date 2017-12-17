# BLE-iBeacon

## What is it?

A Bluetooth LE iBeacon service for systemd (Debian and CentOS tested)

## Requirements

- Bluetooth LE v4.0 device
- bluez (tested with 5.43 / yum install bluez / apt-get install bluez)

## How to install

```./install UUID=generate DEVICE=hci0 MAJOR=300 MINOR=1```

## Install script usage

``install [UUID=<UUID|generate>] [DEVICE=<device(hci0)>] [NOSCAN=<yes|no(no)>] [MAJOR=<major version(0)>] [MINOR=<minor version(0)>] [CONNECTABLE=<yes/no(no)>] [INTERVAL_MIN=<min. interval in ms(500)>] [<INTERVAL_MAX=<max. interval in ms(1000)>]``

## More about iBeacons

https://en.wikipedia.org/wiki/IBeacon

