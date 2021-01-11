<h1><img height="24" src="https://cdn.technicpack.net/platform2/pack-icons/1540036.png"/> EV.COMBAT</h1>

[![](https://img.shields.io/badge/ON-TECHNICPACK.NET-cyan?style=for-the-badge)](https://www.technicpack.net/modpack/evcomb)

## General Information

Evolved Combat is a Minecraft modpack based on Minecraft 1.12.2. It is our humble recreation of the famous Hexxit modpack but on a newer version of Minecraft. It ensures to deliver the same style of gameplay by implementing a collection of unique combat and battle modifications into the game. Alongside with some well known mods for adventure and discovery fun, it creates a challenging roleplaying modpack.

## What is this Repository for?

This repository has two main purposes:

First of all, this repository holds all binary files, configurations and assets of the modpack. This makes it way easier to maintain the modpack, pushing new versions and backuping old versions of the modpack.

Also, we are using [GitHub Actions](https://github.com/evolvedpacks/pack-client-evolved-combat/actions) to build and deploy releases of the modpack. Everytime a new version is created by setting a new [tag](https://github.com/evolvedpacks/pack-client-evolved-combat/tags), a CD *([Continous Deployment](https://en.wikipedia.org/wiki/Continuous_deployment))* process is started which creates a release zip bundle of the modpack, creates a [Release](https://github.com/evolvedpacks/pack-client-evolved-combat/releases) in this repository where the zip bundle can then be downloaded from, and pushes the latest bundle to a CDN file server which then is utilized by technicpack.net to download the modpack bundle via the technic launcher. And all of this happens fully automatically without having to lift a finger.

If you are interested in how all of this is configured, take a look in the [workflow configuration file](https://github.com/evolvedpacks/pack-client-evolved-combat/blob/master/.github/workflows/cd-tags.yml) where all job steps are specified in.

