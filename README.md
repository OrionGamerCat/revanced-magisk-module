#### ⚠️ This is my personal repo, forked from [here](https://github.com/j-hc/revanced-magisk-module). I won't provide support of any kind, please don't file issues here or upstream for my personalized changes.

# ReVanced Magisk Module
[![Build Modules](https://github.com/OrionGamerCat/revanced-magisk-module/actions/workflows/build.yml/badge.svg)](https://github.com/OrionGamerCat/revanced-magisk-module/actions/workflows/build.yml)
[![CI](https://github.com/OrionGamerCat/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/OrionGamerCat/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/OrionGamerCat/revanced-magisk-module/releases).

## Features
 * Support all present and future ReVanced and [ReVanced Extended](https://github.com/inotia00/revanced-patches) apps
 * Can build Magisk modules and non-root APKs
 * Updated daily with the latest versions of apps and patches
 * Optimize APKs and modules for size
 * Modules
     * recompile invalidated odex for faster usage
     * receive updates from Magisk app
     * do not break safetynet or trigger root detections
     * handle installation of the correct version of the stock app and all that
     * support Magisk and KernelSU

#### **Note that the [CI workflow](../../actions/workflows/ci.yml) is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.**

## To include/exclude patches or patch more ReVanced Apps
[**See the list of patches**](https://github.com/revanced/revanced-patches#-patches)

 * Star the repo :eyes:
 * [Fork the repo](https://github.com/j-hc/revanced-magisk-module/fork) or use it as a template
 * Customize [`config.toml`](./config.toml)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

# Building Locally
## On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

## On Desktop
```console
$ git clone --recurse https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
