# FreeStyle-Libre-3-patch

Public repo to drive Libre 3 development. This repo should be used to exchange informations about Libre 3. Possible goals are the decryption and the creation of an interface for Xdrip.

## Current solutions for FSL 3

- Free Three: An offline solution -> requires root and some knowhow, also only supports libre 3 app upp to version 3.3.1. [Link (German)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Latest download: https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk 
- Librelink to Nightscout sideloading: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App for downloading Linkup data and sharing with Xdrip (source: Libre 2) : [Link (German)](https://insulinclub.de/index.php?thread/32517-freestyle-libre-3/&postID=650302#post650302)
- In development for iOS: DiaBLE -> trying to leverage the FSTL3 capabilities. [Github repo](https://github.com/gui-dos/DiaBLE)

## Current state

The decryption itselfe seems hard to break. However, there are already some solutions, as described above. The Libre 3 apk file if available for download [here](https://apkpure.com/search?q=libre+3&t=app) in most languages.

## How to contribute

If you got any useful informations about Libre 3, share those within the [discussions tab](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions). Also, feel free to work on any of the todos listed below. 

## Todo

1. Extract all data in a useful format
2. Find a way to fetch the BG values (the easiest way might be between Libre LinkUp and Libre3 App)
3. Development of Xdrip Plugin
4. Optional, but good to have: Keep Libre3 App in foreground while closed.

## Encryption infos

The following things are known about the libre 3 app: After startup, the app gets checked if there are any modifications. WhiteCryption code protection is used.

#### #WeAreNotWaiting
