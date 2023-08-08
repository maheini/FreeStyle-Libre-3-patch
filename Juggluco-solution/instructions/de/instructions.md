# Freestyle Libre 3 Anleitung

Das Freestyle Libre 3 System kann automatisch gefährliche Blutzuckerwerte melden. Der Libre3 Sensor sendet jede Minute den aktuellen Blutzuckerwert an einen Empfänger (Lesegerät oder Smartphone). Der Empfänger löst bei Bedarf einen Alarm aus. Mit einer modifizierten LibreLink-App, der Juggluco-App und der xDrip+-App kann deinen Blutzuckerwert kontinuierlich auf dem Smartphone empfangen und anzeigen lassen. Es ist sogar möglich, ältere Daten aus dem Speicher des Sensors zu empfangen (zwei Stunden minütliche Glukose und zwei Wochen einmal pro 5 Minuten Verlaufsdaten), die an Juggluco gesendet werden.

Der Sensor kann im Bereich von -40 mg/dl bis +20 mg/dl (-2,2 mmol/l bis +1,1 mmol/l) kalibriert werden, um Unterschiede zwischen der blutigen Messung und den Sensormessungen auszugleichen.

### Derzeitige Einschränkungen

- Es ist derzeit nicht bestätigt, ob diese Lösung mit der US-Version der Freestyle Libre 3 Sensoren funktioniert!
- Wenn du ein gerootetes System hast, musst du diesen verstecken. Hier findest du eine Anleitung: [Link](https://www.reddit.com/r/Freestylelibre/comments/s22vlr/comment/hw2p4th/?utm_source=share\&utm_medium=web2x\&context=3).
  (Um herauszufinden, ob das Smartphone gerootet ist, gibt es mehrere Apps, eine davon ist z.B. https://root-checker.org/)
- Juggluco (erforderliche App zum Empfang der Libre3-Messwerte) unterstützt nur die Sprachen Englisch, Niederländisch und Italienisch. Die gepatchte Libre3-App unterstützt: ar, de, es, fr, hi, in, it, ja, ko, my, nl, pt, ru, th, tr und vi.




## Schritt 1: Juggluco einrichten

Lade die Juggluco App von [hier](https://github.com/maheini/FreeStyle-Libre-3-patch/raw/main/Juggluco-solution/versions/latest/Juggluco.apk) oder [hier](https://www.juggluco.nl/Juggluco/download.html) herunter und installiere sie.

Nun öffnen wir die App. Du wirst mit diesem Bildschirm unten begrüßt werden. Klicke einfach auf die Schaltfläche "Without Sensor".

![Juggluco Willkommensbildschirm](../images/step\_8.jpg)

Danach erhalten wir einen kurzen Einführungstext. Klicke auf "OK".

![Juggluco-Installationsbildschirm](../images/step\_9.jpg)

Ok, lass uns Juggluco einrichten! Die App selbst hat nicht die beste Oberfläche, aber sie ist sehr nützlich. Um die Einstellungen zu öffnen, klicke auf eine beliebige Stelle auf dem Bildschirm oben links. Nun solltest du das folgende Menü sehen. Wähle "Settings".

![Juggluco-Einstellungen-Menü](../images/step\_10.jpg)

In den Einstellungen kannst du die Datenverbindung zu xDrip konfigurieren. Klicke auf "Patched Libre Broadcast" und drücke "OK".

![Juggluco-Einstellungen](../images/step\_11.jpg)


Gut gemacht!

Notwendige Einstellungen für einen erfolgreichen Sensorstart:

- NFC aktiviert / BT aktiviert
- Speicher- und Standortberechtigung aktiviert
- Ortungsdienst aktiviert
- automatische Zeit- und Zeitzoneneinstellung

Bitte beachte, dass der Ortungsdienst eine zentrale Einstellung ist. Es handelt sich nicht um die Standortberechtigung der App, die ebenfalls eingestellt werden muss!

Starte nun den Libre3-Sensor mit der Juggluco App, indem du den Sensor einfach scannst. Stelle  sicher, dass alle Einstellungen richtig sind. 

## Schritt 2 (optional): Libreview einrichten

Du kannst einen Sensor verwenden, der bereits mit der ursprünglichen Libre3-App verwendet wurde, wenn du denselben LibreView-Kontonamen verwendest. Drücke auf "Neuen Sensor starten" und scanne den Sensor. Wenn du zur Juggluco-App zurückkehren möchtest, stoppe die Libre3-App und scanne den Sensor mit geöffneter Juggluco App.

Außerdem kannst du beispielsweise deine Daten deinem Arzt zur verfügung stellen oder die Berichte aus Libreview vor deinem Besuch ausdrucken. Die Grafiken und Blutzuckerberichte in Libreview sind meist besser als die von xDrip oder Juggluco.

1. Navigiere in Juggluco zu Settings
2. Wähle "Liebreview"
![Liebreview](../images/step\_12.jpg)
 
3. Gib die Daten deines Libreview Accounts an (solltest du noch keinen habe erstelle diesen im Vorhinein)
4. Fertig!

## Schritt 3 (optional): xDrip einrichten

Die Blutzuckerwerte werden von der xDrip+ App auf dem Smartphone empfangen.

- Falls noch nicht eingerichtet, lade die xDrip+ App herunter und installiere einen der neuesten Nightly Builds von [hier](https://github.com/NightscoutFoundation/xDrip/releases).
- In xDrip+ wähle "Libre2 (gepatchte App)" als Datenquelle
- Batterieoptimierung deaktivieren und Hintergrundaktivität für die xDrip+ App zulassen
- Falls nötig, gib unter Less Common Settings->Extra Logging Settings->Extra tags for logging "BgReading:d,xdrip libre_receiver:v" ein. Dadurch werden zusätzliche Fehlermeldungen für die Fehlersuche protokolliert.
- Geh in xDrip+ auf Einstellungen -> Interapp-Kompatibilität -> Daten lokal übertragen und wähle EIN.
- Geh in xDrip+ zu Einstellungen -> Interapp-Kompatibilität -> Behandlungen akzeptieren und wähle AUS.
- Damit AAPS Blutzuckerwerte (ab Version 2.5.x) von xDrip+ empfangen kann, aktiviere bitte Einstellungen -> Interapp Einstellungen -> Empfänger identifizieren "info.nightscout.androidaps".
- Wenn du AndroidAPS zur Kalibrierung verwenden möchten, geh in xDrip+ zu Einstellungen -> Interapp-Kompatibilität -> Kalibrierungen akzeptieren und wähle EIN. Am besten prüfst du auch die Optionen unter Einstellungen -> Weniger allgemeine Einstellungen -> Erweiterte Kalibrierungseinstellungen überprüfen.

## Schritt 4 (optional): Sensor in xDrip starten

Starte den Sensor in xDrip+ mit „Sensor starten“ und „nicht heute“. Es ist nicht notwendig, das Smartphone an den Sensor zu halten. Tatsächlich wird „Sensor starten“ den Libre 3-Sensor nicht physisch starten oder mit ihm interagieren. Dies dient lediglich dazu, xDrip+ zu signalisieren, dass ein neuer Sensor Blutzuckerwerte liefert. Gib, falls vorhanden, zwei blutige Messwerte für die Erstkalibrierung ein. Jetzt sollten die Blutzuckerwerte alle 5 Minuten in xDrip+ angezeigt werden. Verpasste Werte, z. B. weil du zu weit von deinem Telefon entfernt warst, werden nicht nachgefüllt.

Warte mindestens 15-20 Minuten, wenn keine Daten empfangen werden.

Nach einem Sensorwechsel wird xDrip+ den neuen Sensor automatisch erkennen und alle Kalibrierungsdaten löschen. Du kannst deine blutig gemessenen Werte nach der Aktivierung überprüfen und eine neue Erstkalibrierung vornehmen.

## Schritt 5 (nur für Looper): AndroidAPS konfigurieren

- In AndroidAPS gehe zu Config Builder -> BG Source und wählen "xDrip+".
- Wenn AndroidAPS keine Werte empfängt, wenn sich das Telefon im Flugmodus befindet, verwende "Identify receiver".

## Erfahrungen und Fehlerbehebung

### Fehlerbehebung Libre3 keine Messwerte

- Der Android-Ortungsdienst wird nicht erlaubt - bitte aktiviere ihn in den Systemeinstellungen
- automatische Uhrzeit und Zeitzone nicht eingestellt - bitte ändere die Einstellungen entsprechend
- Bluetooth ist ausgeschaltet - bitte einschalten

### Fehlerbehebung Libre3 -> Juggluco-Verbindung

- Stelle sicher, dass Libre3 die Messwerte empfängt
- Überprüfe deine Einstellungen und das Passwort erneut
- Klick im Mene Libre3->Juggluco auf „Sync“ und in Juggluco->Mirror auf die Schaltflächen „Sync“ und „Reinit“.
- Es ist möglich, dass du manchmal, nachdem du alles konfiguriert hast, das Stoppen vom Libre3 erzwingen und neu starten musst.
- Warte einige Zeit oder versuche, Juggluco zu schließen
- Ältere Versionen von Juggluco (unter 2.9.6) senden keine nachträglichen Daten vom Libre3-Sensor an verbundene Geräte (z. B. Juggluco auf WearOS). Es ist möglich, dass du in der gepatchten Libre3 app auf „Resend data“ klicken musst (Juggluco Menü).

### Weitere Hilfe

Originalanleitung: [jkaltes-Website](https://www.juggluco.nl/Juggluco/libre3/)

Zusätzliches Github-Repo: [Github-Link](https://github.com/maheini/FreeStyle-Libre-3-patch)
