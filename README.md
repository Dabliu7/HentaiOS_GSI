# HentaiOS GSI

## Build
To get started with building HenteiOS GSI, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo.html) as well as [How to build a GSI](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F).
- Create a new working directory for your AOSP build and navigate to it:
    ```
    mkdir HentaiOS; cd HentaiOS
    ```
- Initialize local repository:
    ```
    repo init -u https://github.com/hentaiOS/platform_manifest -b Ursamoon
    ```
- Clone this repo:
    ```
    git clone https://github.com/Dabliu7/HentaiOS_GSI -b android-14.0
    ```
- Sync:
    ```
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
    ```

## Credits
These people have helped this project in some way or another, so they should be the ones who receive all the credit:
- [ponces](https://github.com/ponces)
- [phhusson](https://github.com/phhusson)
- [AndyYan](https://github.com/AndyCGYan)
- [eremitein](https://github.com/eremitein)
- [kdrag0n](https://github.com/kdrag0n)
- [Peter Cai](https://github.com/PeterCxy)
- [haridhayal11](https://github.com/haridhayal11)
- [sooti](https://github.com/sooti)
- [Iceows](https://github.com/Iceows)
- [ChonDoit](https://github.com/ChonDoit)
