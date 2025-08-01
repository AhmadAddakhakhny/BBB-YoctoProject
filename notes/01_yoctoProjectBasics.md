### Terminology in Yocto Project
> Yocto Project: Name of whole yocto project initiative
> Poky: Reference distro
> Bitbake: Build engine
> OpenEmbedded: Poky + Bitbake
> Metadata: Files to construct a linux system
> 1. Recipe (.bb): A file that describes how how to handle a software package.
> 2. Class: (.bbclass): Generalization of actions taken in recipes
> 3. Append file (.bbappend): File that overwrites a recipe
> 4. Include file (.inc): Recipe include file
> 5. Configuration (.conf): System, layer, machine configuration file
> Layer: Collection of metadata

### How to setup your yocto build project?
> 1. clone poky: git:/git.yoctoproject.org/poky 


### How to build a minimal image for Qemu?
> 1. go to poky and run: $ . oe-init-build-env
> 2. run $ bitbake nano


@@@ TODO @@@
Editor setup install packges:
code runner extension
open in default browser
yocto project bitbake (cpu consuming)!

