AOSPKAGAMI

Sync

# Initialize local repository
repo init -u https://github.com/AOSPOreo/manifest -b oreo

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags

Preparing to Build

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_device-userdebug

# Build the code
$ mka bacon -jX
