# FreeStyle Libre 3 patch

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Readme in English</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.de.md"><img  alt="DE" src="https://user-images.githubusercontent.com/65506676/190851702-b2699677-462a-4a5a-b23e-efb1cad56890.png" width="18px" /> Readme auf Deutsch</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.es.md"><img alt="ES" src="https://user-images.githubusercontent.com/65506676/194781638-ef763678-e823-4e1d-a5c6-8f616c7a8cdb.jpg" width="18px" /> Léame en alemán</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.fr.md"><img alt="FR" src="https://user-images.githubusercontent.com/65506676/194781642-27c4505f-fc0d-4ddf-a886-21104cdd034f.png" width="18px" /> Lisez-moi en français</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.it.md"><img alt="IT" src="https://user-images.githubusercontent.com/65506676/194781648-31d459f3-4471-403d-b6ae-0e3c8535d2ab.svg" width="18px" /> Leggimi in tedesco</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.tr.md"><img alt="TR" src="https://user-images.githubusercontent.com/65506676/194781679-b757eafc-fac5-4d34-be78-624e3725cecd.png" width="18px" /> Beni Almanca oku</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.ru.md"><img alt="RU" src="https://user-images.githubusercontent.com/65506676/194781655-fcdbba1e-ee4a-4e15-9da6-f7474128a60a.png" width="18px" /> Читайте меня на немецком языке</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.ja.md"><img alt="JA" src="https://user-images.githubusercontent.com/65506676/194781651-fdb00a1b-cc5c-42b4-b4ac-86c816d62251.png" width="18px" /> ドイツ語で読む</a>
&nbsp;&nbsp;&nbsp;&nbsp;

Public repo to drive Libre 3 development. This repo should be used to exchange informations about Libre 3. Possible goals are the decryption and the creation of an interface for Xdrip.

## Disclaimer

Usage of the informations and app from github.com is at your own risk and without warranty or formal support of any kind. This project has no association with and is not endorsed by Abbott.

## Juggluco solution

A huge thanks to [jkaltes](http://jkaltes.byethost16.com/) for all the work. With The [new FSTL3 patch](http://jkaltes.byethost16.com/Juggluco/libre3/), there's finally an offline solution which doesn't requires root access and is fully integrated with Xdrip. You can find instructions here: [Instructions for Libre3 patch with Juggluco](./Juggluco-solution/instructions/en/instructions.md). Or you can use the [download link](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1).Please note: This solution is at your own risk and without warranty or formal support of any kind. This project has no association with and is not endorsed by Abbott.

Please note: I wasn't involved into the development of Juggluco and the final Libre 3 patch, but I love to share all the development work which is going on.

## Other solutions for FSL 3 (requiring root or online connection)

- Free Three: An offline solution -> requires root and some knowhow, also only supports libre 3 app upp to version 3.3.1. [Link (German)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Latest download: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink to Nightscout sideloading: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) for downloading Linkup data and sharing with Xdrip (source: Libre 2): [Link (German)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): an alternative for LLU Client which is able to show BG as notifications withoud Xdrip+
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): feature in Nightly build of Xdrip+ (calibration is not possible)
- In development for iOS: DiaBLE -> trying to leverage the FSTL3 capabilities. [Github repo](https://github.com/gui-dos/DiaBLE)

## Current state

The decryption just got broken :smiley:. There's finally a solution for non-rooted phones, working with Android & Xdrip.

## How to contribute

If you got any useful informations about Libre 3, share those within the [discussions tab](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Encryption infos

The following things are known about the libre 3 app: After startup, the app gets checked if there are any modifications. WhiteCryption code protection is used there.

### #WeAreNotWaiting
