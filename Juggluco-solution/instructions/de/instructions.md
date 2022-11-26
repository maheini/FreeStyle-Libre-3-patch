# Freestyle Libre 3 Anleitung

Das Freestyle Libre 3 System kann automatisch gefährliche Blutzuckerwerte melden. Der Libre3 Sensor sendet jede Minute den aktuellen Blutzuckerwert an einen Empfänger (Lesegerät oder Smartphone). Der Empfänger löst bei Bedarf einen Alarm aus. Mit einer modifizierten LibreLink-App, der Juggluco-App und der xDrip+-App kann deinen Blutzuckerwert kontinuierlich auf dem Smartphone empfangen und anzeigen lassen. Es ist sogar möglich, ältere Daten aus dem Speicher des Sensors zu empfangen (zwei Stunden minütliche Glukose und zwei Wochen einmal pro 5 Minuten Verlaufsdaten), die an Juggluco gesendet werden.

Der Sensor kann im Bereich von -40 mg/dl bis +20 mg/dl (-2,2 mmol/l bis +1,1 mmol/l) kalibriert werden, um Unterschiede zwischen der blutigen Messung und den Sensormessungen auszugleichen.

### Derzeitige Einschränkungen

- Es ist derzeit nicht bestätigt, ob diese Lösung mit der US-Version der Freestyle Libre 3 Sensoren funktioniert!
- Die App funktioniert nur auf arm64 Systemen (64 Bit Systeme). Die meisten modernen Handys werden unterstützt. Wenn du unsicher bist, installiere einfach den Patch und versuche, die App zu starten.
- Wenn du ein gerootetes System hast, musst du diesen verstecken. Hier findest du eine Anleitung: [Link](https://www.reddit.com/r/Freestylelibre/comments/s22vlr/comment/hw2p4th/?utm_source=share\&utm_medium=web2x\&context=3).
  (Um herauszufinden, ob das Smartphone gerootet ist, gibt es mehrere Apps, eine davon ist z.B. https://root-checker.org/)
- Juggluco (erforderliche App zum Empfang der Libre3-Messwerte) unterstützt nur die Sprachen Englisch, Niederländisch und Italienisch. Die gepatchte Libre3-App unterstützt: ar, de, es, fr, hi, in, it, ja, ko, my, nl, pt, ru, th, tr und vi.

## Schritt 1: Herunterladen und Einrichten der gepatchten LibreLink-App

Lade die gepatchte .apk-Datei [hier](../../versions/latest/Libre-3-patch.apk?raw=1) oder [hier](https://apkfab.com/libre-3/com.freestylelibre3.app.de/apk?h=142cfbb2e0b1f10cd280408b10c5a5127e46e00e78d7775dae382529921487e9) herunter und installiere sie auf deinem Handy.

Nachdem du die App erfolgreich auf deinem Handy installiert haben, öffne die App. Wenn du eine Warnung wie die unten stehende siehst, kannst du diese ignorieren. (Die App funktioniert mit jedem EU-Sensor).

![LibreLink-Warnung](../images/step\_1.jpg)

Wenn du auf dem Bildschirm "Create an Account" bist, hast du die Möglichkeit, ein LibreView-Konto zu erstellen. Dies kann eine gute Option sein, da du so die Möglichkeit hast, einen Sensor mit einer anderen App erneut zu aktivieren. Außerdem können damit die BZ-Daten an LibreView weitergegeben werden. Wenn du das nicht möchtest, klicke einfach oben rechts auf "Überspringen".

![LibreView-Konto](../images/step\_2.jpg)

Bitte wähle auf diesem Bildschirm deine Messeinheit aus. Das kann auch später noch geändert werden.

![Auswahl der Maßeinheit](../images/step\_3.jpg)

Wenn du ein Popup mit der Frage "Batterieoptimierung ignorieren?" erhältst, klicke auf "ERLAUBEN". Dadurch wird die Libre3-App im Hintergrund weiterlaufen.

![Akku-Optimierung deaktivieren](../images/step\_4.jpg)

Nun sollte die Libre3-App eingerichtet sein. Fahren wir nun mit der Verbindung zu Juggluco fort

## Schritt 2: Erstelle eine Verbindung von Libre 3 zu Juggluco

Die Grafik unten ist hilfreich beim Verständnis wie die IP und Ports eingestellt werden müssen in den nächsten Schritten.

![Libre Juggluco setup](../images/juggluco-schema.jpg)

Öffne das Libre 3 Seitenmenu und wähle Juggluco aus. Hier werden bestehende Verbindungen angezeigt.

![Juggluco-Menü](../images/step\_5.jpg)

Stelle im Juggluco-Menü sicher, dass "Port" auf 7117 eingestellt ist und klicke unten auf "Verbindung hinzufügen".

![Juggluco-Übersicht](../images/step\_6.jpg)

Fülle nun alles aus, wie in der Abbildung unten gezeigt:

![Libre Juggluco-Einrichtung](../images/step\_7.jpg)

Wenn du fertig bist, klicke auf "Speichern", um deine Einstellungen zu bestätigen. Toll, jetzt kannst du die Libre3-App schließen!

## Schritt 3: Juggluco einrichten

Lade die Juggluco App [hier](../../versions/latest/Juggluco.apk?raw=1) oder [hier](https://apkfab.com/juggluco/tk.glucodata/apk?h=1fc401ff9fbe7f56e6a0a7068fed6da96592b13757c3b05cddff893d813e18fd) herunter und installiere sie.

Nun öffnen wir die App. Du wirst mit diesem Bildschirm unten begrüßt werden. Klicke einfach auf die Schaltfläche "Without Sensor".

![Juggluco Willkommensbildschirm](../images/step\_8.jpg)

Danach erhalten wir einen kurzen Einführungstext. Klicke auf "OK".

![Juggluco-Installationsbildschirm](../images/step\_9.jpg)

Ok, lass uns Juggluco einrichten! Die App selbst hat nicht die beste Oberfläche, aber sie ist sehr nützlich. Um die Einstellungen zu öffnen, klicke auf eine beliebige Stelle auf dem Bildschirm oben links. Nun solltest du das folgende Menü sehen. Wähle "Settings".

![Juggluco-Einstellungen-Menü](../images/step\_10.jpg)

In den Einstellungen kannst du die Datenverbindung zu xDrip konfigurieren. Klicke auf "Send to xDrip" und drücke "OK".

![Juggluco-Einstellungen](../images/step\_11.jpg)

Drücke in der Juggluco-App auf die obere linke Mitte. Es sollte sich ein neues Menü öffnen. Bitte wähle "Mirror".

![Juggluco-Verbindungsmenü](../images/step\_12.jpg)

Du solltest diesen Bildschirm sehen. Überprüfe die Port-Einstellungen in der oberen rechten Ecke, die auf "8795" eingestellt sein sollten, und tippe anschließend auf "Verbindung hinzufügen". (Beachte, dass innerhalb der Juggluco-App die Ports umgekehrt sind.)

![Juggluco-Verbindungsbildschirm](../images/step\_13.jpg)

Gib nun alle Einstellungen wie unten gezeigt sowie das Passwort entsprechend dem Libre3-Passwort ein. Wenn du das getan hast, drücke "Speichern", um zu bestätigen.

![Juggluco-Verbindungseinstellungen](../images/step\_14.jpg)

Gut gemacht!

Notwendige Einstellungen für einen erfolgreichen Sensorstart:

- NFC aktiviert / BT aktiviert
- Speicher- und Standortberechtigung aktiviert
- Ortungsdienst aktiviert
- automatische Zeit- und Zeitzoneneinstellung
- Mindestens einen Alarm in der gepatchten App einstellen

Bitte beachte, dass der Ortungsdienst eine zentrale Einstellung ist. Es handelt sich nicht um die Standortberechtigung der App, die ebenfalls eingestellt werden muss!

Starte nun den Libre3-Sensor mit der gepatchten App, indem du den Sensor einfach scannst. Stelle  sicher, dass alle Einstellungen richtig sind. Du kannst einen Sensor verwenden, der bereits mit der ursprünglichen Libre3-App verwendet wurde, wenn du denselben LibreView-Kontonamen verwendest. Drücke auf "Neuen Sensor starten" und scanne den Sensor. Wenn du zur ungepatchten Libre3-App zurückkehren möchtest, musst du dasselbe tun.

Du kannst nun versuchen, die Schaltfläche "Sync" im vorherigen Menü zu drücken. Nach einiger Zeit (bis zu 15-20 Minuten) sollte Juggluco die Blutzuckerwerte automatisch von der Libre3-App erhalten. Wenn dies nicht der Fall ist, dann versuch das Smartphone neu zu starten und Juggluco zu öffnen. Wische auf der Grafik nach link und rechts um zu prüfen ob ein Wert empfangen wird. Stelle sicher dass Juggluco die Werte empfängt, bevor du mit dem nächsten Schritt weiterfährst.

## Schritt 4 (optional): xDrip einrichten

Die Blutzuckerwerte werden von der xDrip+ App auf dem Smartphone empfangen.

- Falls noch nicht eingerichtet, lade die xDrip+ App herunter und installiere einen der neuesten Nightly Builds von [hier](https://github.com/NightscoutFoundation/xDrip/releases).
- In xDrip+ wähle "Libre2 (gepatchte App)" als Datenquelle
- Batterieoptimierung deaktivieren und Hintergrundaktivität für die xDrip+ App zulassen
- Falls nötig, gib unter Less Common Settings->Extra Logging Settings->Extra tags for logging "BgReading:d,xdrip libre_receiver:v" ein. Dadurch werden zusätzliche Fehlermeldungen für die Fehlersuche protokolliert.
- Geh in xDrip+ auf Einstellungen -> Interapp-Kompatibilität -> Daten lokal übertragen und wähle EIN.
- Geh in xDrip+ zu Einstellungen -> Interapp-Kompatibilität -> Behandlungen akzeptieren und wähle AUS.
- Damit AAPS Blutzuckerwerte (ab Version 2.5.x) von xDrip+ empfangen kann, aktiviere bitte Einstellungen -> Interapp Einstellungen -> Empfänger identifizieren "info.nightscout.androidaps".
- Wenn du AndroidAPS zur Kalibrierung verwenden möchten, geh in xDrip+ zu Einstellungen -> Interapp-Kompatibilität -> Kalibrierungen akzeptieren und wähle EIN. Am besten prüfst du auch die Optionen unter Einstellungen -> Weniger allgemeine Einstellungen -> Erweiterte Kalibrierungseinstellungen überprüfen.

## Schritt 5 (optional): Sensor in xDrip starten

Starte den Sensor in xDrip+ mit „Sensor starten“ und „nicht heute“. Es ist nicht notwendig, das Smartphone an den Sensor zu halten. Tatsächlich wird „Sensor starten“ den Libre 3-Sensor nicht physisch starten oder mit ihm interagieren. Dies dient lediglich dazu, xDrip+ zu signalisieren, dass ein neuer Sensor Blutzuckerwerte liefert. Gib, falls vorhanden, zwei blutige Messwerte für die Erstkalibrierung ein. Jetzt sollten die Blutzuckerwerte alle 5 Minuten in xDrip+ angezeigt werden. Verpasste Werte, z. B. weil du zu weit von deinem Telefon entfernt warst, werden nicht nachgefüllt.

Warte mindestens 15-20 Minuten, wenn keine Daten empfangen werden.

Nach einem Sensorwechsel wird xDrip+ den neuen Sensor automatisch erkennen und alle Kalibrierungsdaten löschen. Du kannst deine blutig gemessenen Werte nach der Aktivierung überprüfen und eine neue Erstkalibrierung vornehmen.

## Schritt 6 (nur für Looper): AndroidAPS konfigurieren

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

Originalanleitung: [jkaltes-Website](http://jkaltes.byethost16.com/Juggluco/libre3/)

Zusätzliches Github-Repo: [Github-Link](https://github.com/maheini/FreeStyle-Libre-3-patch)
