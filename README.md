# 🚀 Paranoid Android (AOSPA) for asteroids #

### 📥 Initialize Paranoid Android ###
```
repo init -u https://github.com/aospa-asteroids/manifest -b beryl --depth 1
```

### 🔄 Sync Sauce ###
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

### 🍳 Cook AOSPA ###
```
./rom-build.sh asteroids
```

## 🎉 Now Build and Enjoy! ##
