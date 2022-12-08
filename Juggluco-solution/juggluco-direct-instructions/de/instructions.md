# Freestyle Libre 3 Anleitung

Das Freestyle Libre 3 System kann automatisch gefährliche Blutzuckerwerte melden. Der Libre3 Sensor sendet jede Minute den aktuellen Blutzuckerwert an einen Empfänger (Lesegerät oder Smartphone). Der Empfänger löst bei Bedarf einen Alarm aus. Mit Hilfe der Juggluco App kann der Sensor nach derm Start übernommen werden und mit Xdrip+ oder AndroidAPS verbunden werden. So können die Blutzuckerwerte direkt übertragen werden. Es ist sogar möglich, ältere Daten aus dem Speicher des Sensors zu empfangen (zwei Stunden minütliche Glukose und zwei Wochen einmal pro 5 Minuten Verlaufsdaten), die an Juggluco gesendet werden.

Der Sensor kann im Bereich von -40 mg/dl bis +20 mg/dl (-2,2 mmol/l bis +1,1 mmol/l) kalibriert werden, um Unterschiede zwischen der blutigen Messung und den Sensormessungen auszugleichen.

### Derzeitige Einschränkungen

- Diese Variante funktioniert aktuell nicht mit der US-Variante vom Libre3
- Wenn du ein gerootetes System hast, musst du diesen verstecken. Hier findest du eine Anleitung: [Link](https://www.reddit.com/r/Freestylelibre/comments/s22vlr/comment/hw2p4th/?utm_source=share\&utm_medium=web2x\&context=3).
  (Um herauszufinden, ob das Smartphone gerootet ist, gibt es mehrere Apps, eine davon ist z.B. [root-checker.org](https://root-checker.org/))
- Die Juggluco App unterstützt nur die Sprachen Englisch, Niederländisch und Italienisch.

## Schritt 1: Herunterladen und Einrichten der Libre3 App

Installiere die Libre 3 App aus dem Playstore und öffne diese. Auf dem Startbildschirm klickst du auf "Anmelden". Die Anmeldung mit deinem LibreLink Account ist zwingend notwendig - solltest du keinen haben, kannst du dir einen erstellen.

![Libre3 Startbildschirm](../images/1.jpg) ![LibreLink Anmeldung](../images/2.jpg)

Anschliessend musst du die Nutzerbedingungen von Abbott akzeptieren. Die letzte ist dabei Optional und kann auch abgelehnt werden.

![Libre 3 Term](../images/4.jpg) ![Libre 3 Term](../images/5.jpg) ![Libre 3 Term](../images/6.jpg)

Stelle die App nun Schritt für Schritt nach deinen Bedürfnissen ein. Falls diese Meldung zur Akku-optimierung auftauchen, dann klicke auf "Erlauben".

![Libre 3 Akkuoptimierung](../images/10.jpg)

Nachdem du die Libre 3 App eingerichtet hast, darfst du bereits deinen ersten Sensor aktivieren. Scanne dazu wie gezeigt den Sensor und warte die 60 Minuten aufwärmphase vom Sensor ab.

![Libre 3 Sensor aktivieren](../images/12.jpg)

## Schritt 2: Libre 3 App beenden

Nachdem der Sensor erfolgreich gestartet ist und der erste Sensorwert sichtbar ist, kann es weitergehen. Öffne nun die Einstellungen und öffne die Einstellungen für "Apps".

![Einstellungen Apps](../images/13.jpg)

Anschliessend suchst du nach der Libre 3 App. Hast du diese gefunden, klickst du diese an.

![Libre 3 App Einstellungen](../images/14.jpg)

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
