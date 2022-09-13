# FreeStyle-Libre-3-patch

Public repo to drive Libre 3 development. This repo should be used to exchange informations about Libre 3. Possible goals are the decryption and the creation of an interface for Xdrip.

## Juggluco solution

A huge thanks to [jkaltes](http://jkaltes.byethost16.com/) for all the work. With The [new FSTL3 patch](http://jkaltes.byethost16.com/Juggluco/libre3/), there's finally an offline solution which doesn't requires root access and is fully integrated with Xdrip. Just download & install the [patched apk file](https://github.com/maheini/FreeStyle-Libre-3-patch/raw/main/Patched%20Apk/Libre%203_v3.3.0_apkfab.com.apk) and afterwards [get Juggluco from Google Play](https://play.google.com/store/apps/details?id=tk.glucodata&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1) and set everything up. For more informations, please visit jkaltes website: [link](http://jkaltes.byethost16.com/Juggluco/libre3/)

Please note: I wasn't involved into the development of Juggluco and the final Libre 3 patch, but I love to share all the development work which is going on.

## Other solutions for FSL 3 (requiring root or online connection)

- Free Three: An offline solution -> requires root and some knowhow, also only supports libre 3 app upp to version 3.3.1. [Link (German)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Latest download: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink to Nightscout sideloading: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) for downloading Linkup data and sharing with Xdrip (source: Libre 2) : [Link (German)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- [*LinkUpConnect*](https://github.com/cmtjk/LinkUpConnect) and alternative for *LLC Clinet* which is able to show BG as notifications withoud Xdrip+
- [*Web Follower*](https://xdrip.readthedocs.io/en/latest/install/webfollower/) feature in Nightly build of Xdrip+ (calibration is not possible)    
- In development for iOS: DiaBLE -> trying to leverage the FSTL3 capabilities. [Github repo](https://github.com/gui-dos/DiaBLE)

## Current state

The decryption just got broken :smiley:. There's finally a solution for non-rooted phones, working with Android & Xdrip.

## How to contribute

If you got any useful informations about Libre 3, share those within the [discussions tab](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Encryption infos

The following things are known about the libre 3 app: After startup, the app gets checked if there are any modifications. WhiteCryption code protection is used there.

### #WeAreNotWaiting
