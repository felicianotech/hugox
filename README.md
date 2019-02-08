# hugoX [![CircleCI Build Status](https://circleci.com/gh/felicianotech/hugox.svg?style=shield)](https://circleci.com/gh/felicianotech/hugox) [![Software License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://raw.githubusercontent.com/circleci/circleci-docs/master/LICENSE) [![Upstream](https://img.shields.io/badge/upstream-hugo-lightgrey.svg)](https://github.com/gohugoio/hugo)

hugoX is a build of Hugo (the static site generator) with additional/experimental features.
It stands for "Hugo eXtra".

hugoX isn't a hard fork of Hugo.
Instead, it's what I'm calling a "parallel fork".
Each release of Hugo will be incorporated back into hugoX.
You can learn much more about Hugo and contribute that beaufitul from by visiting [the Hugo Readme](https://github.com/gohugoio/hugo/README.md).

With hugoX, you'll always be able to do everything that you can do with Hugo, plus a little bit eXtra.


## Installation

Hugo can be installed on the three major OSs as well as compiled from source.

### Linux

hugoX can be installed via Snap on Ubuntu 16.04, Ubuntu 18.04+, elementary 5+, Debian 9, Fedora 29+, and many other Linux distros with `snapd` installed by running:

```
sudo snap install hugox
```

### macOS

Builds for macOS are coming soon.

### Windows

Builds for Windows 10+ are coming soon.

### Compile from source

hugoX can also be compiled from source.
With a working installation of Go v1.11 or later:

```
cd <to-where-you-store-repos>
git clone github.com/felicianotech/hugox
cd hugox
git checkout <hugox-version>
go install
```


## Usage

hugoX can be used the same way you use Hugo.
You can run `hugox help` to available commands and options.
See [Extra Features](#extra-features) below to see what's been add specifically to hugoX.


## eXtra Features


## License & Copyright

Hugo is licensed under the Apache 2.0 license thus so is hugoX.
Steve Francia (spf13) holds the copyright for the Hugo logos.
Bjørn Erik Pedersen (bep), Steve, and many others in the Hugo community wrote 99.9999% of the code within hugoX.
If the project ever opens up for donations, I suggest you give them one.
I know I will.

This repo's license can be found [here](./LICENSE).
