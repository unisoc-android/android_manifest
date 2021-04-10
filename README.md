# unisoc-android #

### Setup build enviroment ###
https://source.android.com/setup/build/initializing#installing-required-packages-ubuntu-1804

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/unisoc-android/android_manifest -b W20.13.3

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

$ echo "TO DO!"

```
