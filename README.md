# ava-gen
A Raspberry Pi Image Creator

This is a work in-progress custom image creator inpired by openembedded-core bitbake and pi-gen. Though once i'm satisfied with this outcome, then i will also make a bitbake version(in-progress) which i currently put on-hold.

# Config
config file:
    BRANCH - required to set your desired repo branch. Pi Foundation Kernel

# Usage
1. Start by checking the dependencies and missing ones. Run the executable file 'dep_check'
2. Initialize the build environment by sourcing the 'init-build-env' file: ". ./init-build-env <image_name>" or "source ./init-build-env <image_name>".
3. Then run 'build pi3-arm-lite' to start the process of creating a lite version.

To Do:
- User desired filesystem. Currently using only ubuntu-base-18.04.1. (raspbian, debian, alpine)
