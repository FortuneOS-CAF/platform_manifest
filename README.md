# FortuneOS

### Getting Started:
To get started with FortuneOS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:
```bash
repo init -u https://github.com/FortuneOS-CAF/platform_manifest.git -b udc
```

Then to sync up:
```bash
 repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --retry-fetches=5 -j$(nproc --all)
```
---------------------------------------------------------------------------------------
### Compilation:
```bash
getfortune device-userdebug
```
---------------------------------------------------------------------------------------
## Credits:
* [AOSPA](https://github.com/AOSPA)
* [CodeLinaro](https://git.codelinaro.org/clo)
* [ConquerOS](https://github.com/ConquerOS)
* [LineageOS](https://github.com/LineageOS)
* [Project-404](https://github.com/p404)
* [ReloadedOS](https://github.com/ReloadedOS)
* [xdroidOS](https://github.com/xdroid-oss)
* [ManyMore from where cherry-picked from](https://github.com)
---------------------------------------------------------------------------------------
