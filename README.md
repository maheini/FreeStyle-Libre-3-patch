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

Public repo to drive the development of Libre 3 interfaces for apps like xDrip+ or AndroidAPS. This repo is intended for information exchange about current solutions as well as the Libre 3.

## Disclaimer

The use of information and the app from github.com is at your own risk and without any kind of waranty or support. This project is not affiliated with and not endorsed by Abbott.

## Juggluco solution

A big thank you to [jkaltes](https://www.juggluco.nl/) for all the work. With the Juggluco app it is possible to send blood glucose values from the Libre 3 sensor offline and without root to xDrip+, AndroidAPS etc. You can find detailed instructions here: [Instructions Libre 3 connection with Juggluco](./Juggluco-solution/instructions/en/instructions.md). Click here to go directly [to download](https://www.juggluco.nl/Juggluco/download.html). Please note: The whole project is at your own risk and without any kind of warranty or support. This project has no collaboration and is not recommended by Abbott.

## Other solutions for FSL 3 (need root or internet connection)

- Free Three: An offline solution -> requires root and some know-how, and only Libre 3 app up to version 3.3.1 is supported [Link (German)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
     ->Latest Download: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink to Nightscout sideloading: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) to download the linkup data and share it with Xdrip (blood sugar source: Libre 2): [Link (German)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144 #post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): an alternative for LLU Client, which is able to show blood glucose as notification (without Xdrip+).
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): Function in the Nightly build of Xdrip+ (calibrations are not possible)
- In development for iOS: DiaBLE -> Tries to expand the possibilities of FSTL3. [Github repo](https://github.com/gui-dos/DiaBLE)

## Current status

The decryption was successfully cracked :smiley:. There is now a final solution for un-rooted devices working with Android & Xdrip.

## How to contribute

If you have any useful information about the Libre 3, please share it in the [discussions tab](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

### #WeAreNotWaiting