<img src="https://github.com/GoldenCheetah/GoldenCheetah/raw/master/src/Resources/images/gc.png" height="25%" width="25%">

# GoldenCheetah

## About

GoldenCheetah is an open-source data analysis tool primarily written in C++
with Qt for cyclists and triathletes
with support for training as well.

GoldenCheetah can connect with indoor trainers and cycling equipment such
as cycling computers and power meters to import data.

In addition, GoldenCheetah can connect to cloud services.

It can then manipulate and view the data, as well as analyze it.

This repository contains the files to build GoldenCheetah as a [Snap](https://snapcraft.io/) package.

## Installing

On Ubuntu 16.04:

```
# install & init snapcraft
apt update
apt install -y snapcraft
snapcraft init

# clone this repo
git clone ...

# adjust snap/snapcraft.yaml to your needs

# build snap
snapcraft

# install & test snap
snap install --dangerous goldencheetah_3.4.0_amd64.snap
goldencheetah.GoldenCheetah

```

Some references on how to compile GoldenCheetah: http://gc.stand2surf.net/Ubuntu-14.04/qt551-sdk.html