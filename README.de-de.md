# FreeStyle Libre 3 patch

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Readme in English</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="README.de-de.md"><img  alt="DE" src="https://user-images.githubusercontent.com/65506676/190851702-b2699677-462a-4a5a-b23e-efb1cad56890.png" width="18px" /> Readme auf Deutsch</a>

Öffentliche Repo um Entwicklungen vom Libre 3 voranzutreiben. Diese Repo ist für den Informationsaustausch über den Libre 3 gedacht. Mögliche Ziele sind die Entschlüsselung und die Erstellung einer Schnittstelle für Xdrip.

## Juggluco Lösung

Ein grosses Dankeschön an [jkaltes](http://jkaltes.byethost16.com/) für all die Arbeit. Mit dem [neuen FSTL3 patch](http://jkaltes.byethost16.com/Juggluco/libre3/) gibt es endlich eine finale offline Möglichkeit, die keinen Root-Zugriff erfordert und vollständig in Xdrip integriert ist. Einfach nur die [gepatchte apk Datei](https://github.com/maheini/FreeStyle-Libre-3-patch/raw/main/Patched%20Apk/Libre%203_v3.3.0_apkfab.com.apk) herunterladen & installieren, anschliessend [Juggluco vom Google Play installieren](https://play.google.com/store/apps/details?id=tk.glucodata&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1) und alles aufsetzen. Eine Umfassende Anleitung ist hier auf Deutsch erhältlich: [Link](https://insulinclub.de/core/index.php?attachment/17545-anleitung-2-mit-links-freestyle-libre-3-und-juggluco-pdf/), mehr Informationen sind zudem auf jkaltes Website verfügbar: [Link (englisch)](http://jkaltes.byethost16.com/Juggluco/libre3/)

Info: Ich war nicht persönlich beteiligt bei der Entwicklung von Juggluco und dem finalen Libre 3 Patch, aber ich liebe es, all diese Entwicklungsarbeiten zu teilen.

## Andere Lösungen für FSL 3 (benötigen Root oder Internetverbindung)

- Free Three: Eine offline-Lösung -> benötigt Root und etwas Knowhow, zudem wird nur Libre 3 App bis version 3.3.1 unterstützt [Link](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Neuster Download: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink zu Nightscout sideloading: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) um die Linkup Daten herunterzuladen und mit Xdrip zu teilen (Blutzuckerquelle: Libre 2): [Link](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): eine Alternative für LLU Client, welche in der Lange ist, den Blutzucker als Benachrichtigung anzuzeigen (ohne Xdrip+).
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): Funktion im Nightly build von Xdrip+ (Kalibrierungen sind nicht möglich)
- In Entwicklung für iOS: DiaBLE -> Versucht die Möglichkeiten vom FSTL3 zu erweitern. [Github repo](https://github.com/gui-dos/DiaBLE)

## Aktueller Stand

Die Entschlüsselung wurde soeben geknackt :smiley:. Es gibt nun eine finale Lösung für un-gerootete Geräte, funktionierend mit Android & Xdrip.

## So kannst du mithelfen

Wenn du irgendeine nützliche Information hast über den Libre 3, dann teile diese im [Diskussions-tab](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Verschlüsselungs-Infos

Die folgenden Dinge sind über die Libre 3 App bekannt: Nach dem Start prüft die App, ob irgendwelche Änderungen vorgenommen wurden. WhiteCryption code protection wird hier benutzt.

### #WeAreNotWaiting
