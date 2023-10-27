Ezblock Studio Versionshinweise
=====================================

EzBlock Studio 3.2
-----------------------------------------------

Ab der Version 3.2 wird EzBlock Studio in den Offline-Modus wechseln und der Online-Service wird am 28.02.2023 aus Gründen der Benutzerfreundlichkeit eingestellt. Daher können Sie Ihre Projekte lokal speichern, ohne sich registrieren zu müssen und sie später auf verschiedenen Geräten importieren.

**Detaillierte Informationen**

* Nachdem EzBlock Studio in den Offline-Modus gewechselt hat, können alte Benutzer weiterhin anmelden und Cloud-Projekte lokal speichern. Alle neuen Projekte werden jedoch lokal gespeichert.
* Das Registrierungsportal ist geschlossen. Neue Benutzer müssen kein Konto mehr registrieren, um die Projektspeicherfunktion von EzBlock zu nutzen.
* Hinzufügung einer Import- und Exportfunktion im ``.ezbpro`` Format, mit dem Sie Projekte zwischen Geräten übertragen oder Projekte mit anderen teilen können.
* Bibliotheken können ebenfalls im ``.ezblib`` Format für Übertragung und Teilen importiert und exportiert werden.

**FAQ**

* Was passiert mit meinem Konto?

    Sie haben bis zum 28. Februar 2023 Zeit, alle Ihre Projekte aus der Cloud lokal zu speichern. So geht's: Melden Sie sich bei Ihrem Konto in EzBlock Studio an und wählen Sie "Alle Projekte lokal speichern" im Popup-Fenster, um alle Ihre Cloud-Projekte mit einem Klick auf der Seite "Meine Projekte" zu speichern. Danach können Sie sie in den Ordner Ihres Geräts exportieren oder sie über die Export-Schaltfläche in der App teilen.

    Danach wird EzBlock Studio den Online-Service schließen und alle Online-Daten löschen. Sie können auch alle Ihre Daten löschen, indem Sie nach dem Speichern aller Ihrer Projekte und Bibliotheken auf die Schaltfläche "Konto löschen und abmelden" klicken.

* Wie sieht es mit der Webversion von EzBlock Studio aus?

    Nach dem Upgrade auf Version 3.2 können Sie weiterhin über die Webseite http://ezblock.cc/ezblock-studio auf EzBlock Studio zugreifen.

    Daten werden in Ihrem Browser gespeichert, also vergewissern Sie sich, Ihre Browsersdaten zu löschen. Selbstverständlich können Sie Ihr Projekt oder Ihre Bibliothek auf Ihren Computer exportieren, um sie zu teilen.

* Wie übertrage ich Projekte und Bibliotheken zwischen Geräten?

    Nach dem Exportieren von Projekten im ``.ezbpro`` Format und von Bibliotheken im ``.ezblib`` Format können Sie diese auf andere Geräte übertragen und dort importieren.

* Wie exportiere ich Bibliotheken/Projekte?

    Für ein detailliertes Tutorial verweisen Sie bitte auf: :ref:`export_project_library`.

* Wie importiere ich Bibliotheken/Projekte?

    Für ein detailliertes Tutorial verweisen Sie bitte auf: :ref:`import_project_library`.

EzBlock Studio 3.1
-----------------------------------------------

**Hauptoptimierung**

Die Hauptoptimierung von EzBlock 3.1 ist die Kompatibilität mit dem eingebauten Bluetooth des Raspberry Pi. Es besteht keine Notwendigkeit mehr, eine Erweiterungsplatine mit Bluetooth-Modul zu verwenden.

.. note::
    * Die ältere Version des Roboters kann auch nach dem Brennen des neuen Images normal verwendet werden. Das Bluetooth-Modul auf dem ursprünglichen Roboter-Hut wird nicht mit dem neuen System in Konflikt stehen.

    * Die EzBlock Studio 3.1-Version sollte mit dem EBlock 3.1-Image (https://ezblock.cc/download/v31.html) verwendet werden.

**Hinzufügen**

* Eine Funktion zur individuellen Benennung von Bluetooth wurde zur App hinzugefügt, um das Problem zu vermeiden, dass mehrere Geräte nicht voneinander zu unterscheiden sind. (Neustart zur Aktivierung notwendig.)
* Drei Soundeffekte für den Start, erfolgreiche Verbindung und Trennung wurden hinzugefügt, um ein besseres Feedback zu geben.
* Die LED neben der Stromanzeige wird als Bluetooth-Indikator verwendet, die bei Verbindung dauerhaft leuchtet und bei keiner Verbindung langsam blinkt.
* (**Android**) Ein Vollbild-Eingabefeld wurde hinzugefügt, um zu verhindern, dass das Eingabefeld blockiert wird.

**Optimierung**

* Die Akkuanzeige wurde optimiert, sodass nun genauere Informationen in der APP angezeigt werden können.
* Die Darstellung von Beispielbildern des Produkts und Icons persönlicher Informationen wurde optimiert.

**Beheben**

* Eine Reihe von Problemen mit der Bluetooth-Suche und -Verbindung wurde behoben.
* Das Problem, dass der Produktname nach der Wifi-Konfiguration nicht angezeigt wird, wurde behoben.
* Das Problem, dass Produktinformationen nach Änderungen nicht gespeichert werden, wurde behoben.
* Das Problem, dass Bilder nach dem Fotografieren auf der Fernbedienungsseite nicht gespeichert werden können, wurde behoben.

EzBlock Studio 3 2021.06.08
-----------------------------

**Produktverbindung verbessern**

* Verbindungsmethode verbessern: Im Vergleich zur Bluetooth-Kommunikation von EzBlock 2 verwendet EzBlock 3 Websocket zur Kommunikation, was wesentlich schneller ist.
* Verbindungsprozess verbessern: EzBlock 3 nutzt Bluetooth, um die schnelle Wi-Fi-Verbindung des Produkts zu unterstützen.

**Startseite**

- Den Karussell entfernen.
- Die Produkt-Auswahlseite entfernen und in ein Pop-up-Fenster ändern.
- Die Notwendigkeit entfernen, sich anzumelden, um zur Startseite zu gelangen.

- Mein Projekt-Eingang hinzufügen.
- Schaltfläche für das Pop-up-Fenster mit Produktinformationen hinzufügen. Dieses Pop-up zeigt den Produktnamen, Produkttyp, IP, Version, Arbeitsspannung und Leistung.
- Online-Aktualisierungsfunktion des Produktbildes hinzufügen.
- Produkt-Kalibrierungsfunktion hinzufügen.
- Funktion zur Produktname-Änderung hinzufügen.
- Das Menü in der oberen linken Ecke hinzufügen.

- Das Pop-up-Fenster für die Schaltfläche Neues Projekt optimieren.

**Beispiele-Seite**

* Das UI verschönern.
* Schnellstart-/Bearbeitungsbutton hinzufügen.
* Fernbedienungs- oder IoT-Hinweis-Icon hinzufügen.

**Programmierseite**

* Die Anordnung der Schaltflächen Programmieren, IoT, Fernsteuerung und Debug Monitor optimieren.
* Produktverbindungsbutton in der oberen linken Ecke hinzufügen.
* Stop/Run-Programm-Schaltfläche hinzufügen.
* Um das Projekt zu speichern und die IoT-Seite zu betreten, stellen Sie sicher, dass Sie sich bei Ihrem Konto angemeldet haben.

**Persönliche Info-Seite**

* Die Einstellungsseite entfernen.
* Produktkategoriefunktion zur Meine Projekte-Seite hinzufügen.

**Andere**

* Die Schriftart aller Seiten ändern.
* Die Funktion hinzufügen, IP oder Hostname im Web einzugeben, um eine Verbindung zum Produkt herzustellen.
