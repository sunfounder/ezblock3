.. note::

    Hallo und willkommen in der SunFounder Raspberry Pi & Arduino & ESP32 Enthusiasten-Gemeinschaft auf Facebook! Tauchen Sie tiefer ein in die Welt von Raspberry Pi, Arduino und ESP32 mit anderen Enthusiasten.

    **Warum beitreten?**

    - **Expertenunterstützung**: Lösen Sie Nachverkaufsprobleme und technische Herausforderungen mit Hilfe unserer Gemeinschaft und unseres Teams.
    - **Lernen & Teilen**: Tauschen Sie Tipps und Anleitungen aus, um Ihre Fähigkeiten zu verbessern.
    - **Exklusive Vorschauen**: Erhalten Sie frühzeitigen Zugang zu neuen Produktankündigungen und exklusiven Einblicken.
    - **Spezialrabatte**: Genießen Sie exklusive Rabatte auf unsere neuesten Produkte.
    - **Festliche Aktionen und Gewinnspiele**: Nehmen Sie an Gewinnspielen und Feiertagsaktionen teil.

    👉 Sind Sie bereit, mit uns zu erkunden und zu erschaffen? Klicken Sie auf [|link_sf_facebook|] und treten Sie heute bei!

.. _install_ezblock_os_latest:

EzBlock OS installieren
===========================

#. Laden Sie die Datei **Raspberry Pi OS mit vorinstalliertem EzBlock** hier herunter:

    https://ezblock.cc/download/v31.html

#. Entpacken Sie das heruntergeladene Paket und Sie werden die ``.img`` Datei darin finden.

    .. note::
        Extrahieren Sie die .img Datei nicht.

#. Laden Sie das Tool - **Raspberry Pi Imager** von https://www.raspberrypi.org/software/ herunter. Klicken Sie auf den Link zum Raspberry Pi Imager, der zu Ihrem Betriebssystem passt. Nach dem Herunterladen klicken Sie darauf, um den Installer zu starten.

    .. image:: img/image11.png
        :align: center

#. Wenn Sie den Installer starten, versucht Ihr Betriebssystem möglicherweise, Sie am Ausführen zu hindern. Zum Beispiel erhalte ich unter Windows folgende Nachricht. Wenn dieses Fenster erscheint, klicken Sie auf **More info** und dann auf **Run anyway** und folgen Sie den Anweisungen, um den Raspberry Pi Imager zu installieren.

    .. image:: img/image12.png
        :align: center

#. Legen Sie Ihre SD-Karte in den SD-Karten-Slot Ihres Computers oder Laptops. Dann öffnen Sie den Raspberry Pi Imager und klicken Sie auf **CHOOSE OS**.

    .. image:: img/choose_os.png
        :align: center

#. Gehen Sie zum Ende der Seite und wählen Sie **Use Custom**. Im Popup-Fenster wählen Sie **RaspiOS-xxx_EzBlockOS-xxx.img**, die Sie im **Schritt 1** heruntergeladen haben, und klicken Sie auf **Open**.

    .. image:: img/use_custom.png
        :align: center

#. Wählen Sie die SD-Karte aus, die Sie verwenden.

    .. image:: img/image14.png
        :align: center

#. Drücken Sie **Ctrl+Shift+X** oder klicken Sie auf das **settings** Symbol, um die **Advanced options** Seite zu öffnen, um den Hostnamen festzulegen, SSH zu aktivieren und Benutzernamen und Passwort festzulegen. Sie können wählen, diese Bildanpassungsoptionen immer zu verwenden.

    .. note::
        Der Hostname wird festgelegt, damit Sie :ref:`use_on_web_latest` nutzen können, um mit Ihrem Gerät über den Hostnamen zu verbinden. Sie können es auch unbelegt lassen.

    .. image:: img/configure.png
        :align: center

#. Scrollen Sie dann nach unten, um die WLAN-Konfiguration abzuschließen und klicken Sie auf **SAVE**.

    .. note::

        Das **wifi country** sollte mit dem zweibuchstabigen `ISO/IEC alpha2 code <https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements>`_ des Landes festgelegt werden, in dem Sie Ihren Raspberry Pi verwenden.
        
        Dieser Schritt ist optional, wenn Sie in diesem Schritt WIFI nicht konfigurieren, können Sie es später direkt über die App konfigurieren.

    .. image:: img/image16.png
        :align: center

#. Klicken Sie auf die Schaltfläche **WRITE**.

    .. image:: img/image17.png
        :align: center

#. Nach einer Weile erhalten Sie eine Meldung, die besagt, dass das Image auf Ihre Micro SD-Karte geschrieben wurde und Sie sie entfernen können. Dann können Sie sie in den Raspberry Pi einlegen.

    .. image:: img/burning2.png
        :align: center

