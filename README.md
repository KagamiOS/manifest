
AOSPOreo

Sync

# Initialize local repository
repo init -u https://github.com/AOSPOreo/manifest -b oreo

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
Preparing to Build

# set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_device-userdebug

# Build the code
$ repo sync -f --force-sync --no-clone-bundle
