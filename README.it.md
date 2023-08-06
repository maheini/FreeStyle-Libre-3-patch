
# patch FreeStyle Libre 3

Questo testo è tradotto automaticamente. Si consiglia di leggere la versione inglese o tedesca per gli ultimi aggiornamenti.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Readme in Inglese</a>

Repo pubblico per guidare lo sviluppo di interfacce Libre 3 per app come xDrip+ o AndroidAPS. Questo repository è destinato allo scambio di informazioni sulle soluzioni attuali e su Libre 3.

## Disclaimer

L'uso delle informazioni e dell'app da github.com è a proprio rischio e senza alcun tipo di garanzia o supporto. Questo progetto non è affiliato e non è approvato da Abbott.

## Soluzione Juggluco

Un grande grazie a [jkaltes](https://www.juggluco.nl/) per tutto il lavoro. Con l'app Juggluco è possibile inviare le letture della glicemia dal sensore Libre 3 a xDrip+, AndroidAPS ecc. offline e senza root. Puoi trovare istruzioni dettagliate qui: [Istruzioni Libre 3 connessione con Juggluco](./Juggluco-solution/juggluco-direct-instructions/en/instructions.md). Oppure puoi utilizzare il [link per il download](./Juggluco-solution/versions/latest/Juggluco.apk?raw=1). Nota: questo progetto è a tuo rischio e pericolo e senza alcun tipo di garanzia o supporto. Questo progetto non è affiliato e non è approvato da Abbott.

## Altre soluzioni per FSL 3 (richiede root o connessione internet)

- Free Three: una soluzione offline -> richiede root e un po' di know-how, ed è supportata solo l'app Libre 3 fino alla versione 3.3.1 [Link (tedesco)](https://insulinclub.de/index.php?thread /33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
       ->Ultimo download: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink al sideload di Nightscout: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) per scaricare i dati di collegamento e condividerli con Xdrip (fonte glicemia: Libre 2): [Link (tedesco)](https://insulinclub.de/index.php?thread/33987-llu- cliente/&postID=654144 #post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): un'alternativa per il client ULL, che è in grado di mostrare la glicemia come notifica (senza Xdrip+).
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): funzione nella build notturna di Xdrip+ (le calibrazioni non sono possibili)
- In sviluppo per iOS: DiaBLE -> Cerca di espandere le possibilità di FSTL3. [Repository Github](https://github.com/gui-dos/DiaBLE)

## Stato attuale

La decrittazione è stata violata con successo :smiley:. Ora esiste una soluzione finale per i dispositivi senza root che funzionano con Android e Xdrip.

## Come contribuire

Se disponi di informazioni utili su Libre 3, condividile nella [scheda Discussioni](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

### #WeAreNotWaiting