
# patch FreeStyle Libre 3

Questo testo è tradotto automaticamente. Si consiglia di leggere la versione inglese o tedesca per gli ultimi aggiornamenti.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Readme in Inglese</a>

Repository pubblica per guidare lo sviluppo di Libre 3. Questa repo dovrebbe essere usata per scambiare informazioni su Libre 3. Possibili obiettivi sono la decrittazione e la creazione di un'interfaccia per Xdrip.

## Disclaimer

L'uso delle informazioni e dell'applicazione di github.com è a proprio rischio e pericolo e senza garanzia o supporto formale di alcun tipo. Questo progetto non è associato e non è approvato da Abbott.

## Soluzione Juggluco

Un enorme ringraziamento a [jkaltes](http://jkaltes.byethost16.com/) per tutto il lavoro svolto. Con la [nuova patch FSTL3](http://jkaltes.byethost16.com/Juggluco/libre3/), c'è finalmente una soluzione offline che non richiede l'accesso root ed è completamente integrata con Xdrip. Le istruzioni sono disponibili qui: [Istruzioni per la patch Libre3 con Juggluco](./Juggluco-solution/instructions/en/instructions.md). Oppure potete usare il [link per il download](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1).Nota bene: questa soluzione è a vostro rischio e pericolo e senza garanzia o supporto formale di alcun tipo. Questo progetto non è associato e non è approvato da Abbott.

Nota bene: non sono stato coinvolto nello sviluppo di Juggluco e della patch finale di Libre 3, ma mi piace condividere tutto il lavoro di sviluppo in corso.

## Altre soluzioni per FSL 3 (che richiedono root o connessione online)

- Free Three: Una soluzione offline -> richiede il root e qualche conoscenza, inoltre supporta solo le applicazioni Libre 3 fino alla versione 3.3.1. [Link (tedesco)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Scaricamento più recente: [Link](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink per il sideloading di Nightscout: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- App (LLU Client) per scaricare i dati Linkup e condividerli con Xdrip (fonte: Libre 2): [Link (tedesco)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): un'alternativa a LLU Client che è in grado di mostrare BG come notifiche con Xdrip+.
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): funzione presente nella versione Nightly di Xdrip+ (la calibrazione non è possibile).
- In sviluppo per iOS: DiaBLE -> cerca di sfruttare le capacità di FSTL3. [repo Github](https://github.com/gui-dos/DiaBLE)

## Stato attuale

La decrittazione si è appena rotta :smiley:. C'è finalmente una soluzione per i telefoni non rootati, che funziona con Android e Xdrip.

## Come contribuire

Se hai informazioni utili su Libre 3, condividile nella scheda [discussioni](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Informazioni sulla crittografia

Sono note le seguenti informazioni sull'applicazione Libre 3: Dopo l'avvio, l'applicazione viene controllata se ci sono modifiche. Viene utilizzata la protezione del codice WhiteCryption.

### #WeAreNotWaiting
