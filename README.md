# Project Flare #

### Initialize Project Flare ###

**Initialize full repository (useful for developers)**
```
repo init -u https://github.com/Project-Flare-Staging/android_manifest -b 16.0 --git-lfs
```

**If you want to save space, use this instead**
```
repo init -u https://github.com/Project-Flare-Staging/android_manifest -b 16.0 --depth 1 --git-lfs
```

### Sync Sauce ###
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

### Ignite Flare ###
```
./rom-build.sh device
```

## Now Build and Enjoy! ##
