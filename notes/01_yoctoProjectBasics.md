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
> 2. run $ bitbake dropbear

### List the three main layers that should be existed to have an image?
> meta  
> meta-poky  
> meta-yocto-bsp  

### List the bold stages of the image generation process?
> 1. Download the sources (i.e. openssl, qt5)  
> 2. each package has its recipe to depict the steps of the (configuration, compilation, installation, archive)  
> 3. then the package output would be created  
> 4. to create an image, it would be composed of some/all generated packages based upon the image recipe
> 5. image file is generated


### List the important files in the generated build/conf directory?
> After running the script oe-init-buil-env the follwoing files gets generated  
> bblayers.conf: contains the essintial layers for an image  
> local.conf: contains some important global variables for the board configuration (i.e. MACHINE)

@@@ TODO @@@
Editor setup install packges:
code runner extension
open in default browser
yocto project bitbake (cpu consuming)!