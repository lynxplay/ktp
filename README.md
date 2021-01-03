KTP ![Java CI](https://github.com/lynxplay/knockturn-paper/workflows/Java%20CI/badge.svg)
==

Fork of [Paper](https://github.com/PaperMC/Paper) aimed at improving server performance at high playercounts.

## Building

Requirements:
- You need `git` installed, with a configured user name and email. 
   On windows you need to run from git bash.
- You need `maven` installed
- You need `jdk` 8+ installed to compile (and `jre` 8+ to run)
- Anything else that `paper` requires to build

If all you want is a paperclip server jar, just run `./tuinity jar`

Otherwise, to setup the `KTP-API` and `KTP-Server` repo, just run the following command
in your project root `./ktp patch` additionally, after you run `./ktp patch` you can run `./ktp build` to build the 
respective api and server jars.

`./ktp patch` should initialize the repo such that you can now start modifying and creating
patches. The folder `KTP-API` is the api repo and the `KTP-Server` folder
is the server repo and will contain the source files you will modify.

## License
The PATCHES-LICENSE file describes the license for api & server patches,
found in `./patches` and its subdirectories except when noted otherwise.

Everything else is licensed under the MIT license, except when note otherwise.
See https://github.com/starlis/empirecraft, https://github.com/Spottedleaf/Tuinity
and https://github.com/electronicboy/byof for the license of material used/modified by this project.


### Note

The fork is based off of Spottedleaf's Tuinity found [here](https://github.com/Spottedleaf/Tuinity)
