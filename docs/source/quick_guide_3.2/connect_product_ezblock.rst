.. _connect_product_ezblock_latest:

Produkt und EzBlock verbinden
=====================================================

#. Schalten Sie den Stromschalter des Robot HAT in die ON-Position. Nach einer Weile hören Sie ein Einschaltgeräusch, was bedeutet, dass der Raspberry Pi erfolgreich gestartet wurde.

    .. image:: img/slide_to_power.png
            :align: center

#. Verbinden Sie Ihr mobiles Gerät (Handy/Tablet) mit dem WLAN und schalten Sie Bluetooth ein.

    .. image:: img/open_wif_bluetooth.jpg
        :align: center

#. Öffnen Sie nun die APP-EzBlock Studio. Es wird Sie aufgefordert, dem EzBlock Studio den Zugriff auf die folgenden 2 Berechtigungen zu gewähren.
    
    * Zugriff auf Fotos, Medien und Dateien auf Ihrem Gerät: Wenn Sie angemeldet sind und Ihr Avatar ändern möchten, benötigt die APP Zugriff auf Ihre Gerätefotos. Wenn Sie die Fotofunktion des Produkts verwenden, benötigt die APP diese Berechtigung, um die Fotos zu speichern.
    * Zugriff auf den Standort Ihres Geräts: Diese Berechtigung muss als **Allow** ausgewählt werden, sonst kann die APP nicht über Bluetooth mit dem Produkt verbinden.

    .. image:: img/allow_access.jpg
        :align: center

#. Klicken Sie auf das Verbindungssymbol in der oberen linken Ecke.

    .. image:: img/sp221115_143525.png
        :align: center

#. Auf der aufklappenden Seite klicken Sie auf Verbinden.

    .. image:: img/click_connect.jpg
        :align: center

#. Nun gelangen Sie auf die Bluetooth-Verbindungsseite. Es wird automatisch nach dem entsprechenden Bluetooth gesucht, normalerweise ist der Produktname ezb-Raspberry, aber die MAC-Adresse ist für verschiedene Produkte unterschiedlich. Wenn Sie mehr als ein Produkt haben, können Sie es anhand der MAC-Adresse identifizieren. Auch dieser Bluetooth-Name kann in den nächsten Schritten geändert werden.

    .. image:: img/connect_bluetooth.jpg
        :align: center

#. Wenn die Verbindung erfolgreich ist, gibt Ihr Produkt ein "Ding-Dong" Geräusch von sich und die App wird anzeigen, dass die Verbindung erfolgreich war.

    .. image:: img/connect_success.jpg
        :align: center

#. Wenn Sie dieses Produkt zum ersten Mal verwenden, werden Sie zur schnellen Konfiguration desselben aufgefordert.

    .. image:: img/config.jpg
        :align: center


#. Geben Sie Ihr WLAN-Konto und Passwort ein.

    .. Note::

        * Wenn Sie bereits das WLAN im **Raspberry Pi Imager** konfiguriert haben, erscheint dieser Schritt nicht und Sie gehen direkt zum nächsten Schritt.
        * Dieser Schritt dient zur Konfiguration des WLANs für den Raspberry Pi. Dies sollte dasselbe WLAN-Netzwerk sein, mit dem auch Ihr mobiles Gerät (Handy/Tablet) verbunden ist.

    .. image:: img/connect_wifi.jpg
        :align: center

#. Wählen Sie das passende Produkt aus.

    .. image:: img/select_product.jpg
        :align: center

#. Geben Sie Ihrem Produkt einen einzigartigen Namen. Dieser wird Ihr Bluetooth-Name sein (wird wirksam nach Neustart des Produkts und der App) und kann auch als Hostname verwendet werden, wenn Sie EzBlock in einem Browser nutzen. Siehe :ref:`use_on_web_latest` für weitere Informationen.

    .. image:: img/set_name.jpg
        :align: center

#. Falls Ihr Produkt kalibriert werden muss, erhalten Sie eine Aufforderung, dass Sie durch Klicken auf **Calibration Now** zur Kalibrierungsseite gelangen können. Wenn keine Kalibrierung notwendig ist, verschwindet das Pop-up-Fenster und Sie gelangen zurück zur Startseite.

    .. image:: img/calibration.jpg
        :align: center

#. Die Kalibrierungsseite jedes Produkts ist unterschiedlich, jedoch gibt es eine Erinnerung, welcher Teil kalibriert werden muss. Sie können den entsprechenden Teil anklicken und sich dann an die **Calibration Help** halten. Nach Abschluss der Kalibrierung klicken Sie auf **Comfirm**.

    .. image:: img/cali_page.jpg
        :align: center

.. note::
    Wenn Sie den Roboter während der Nutzung erneut kalibrieren möchten, folgen Sie bitte den unten stehenden Schritten.
    
    Sie können die Produktdetailseite öffnen, indem Sie das Verbindungssymbol in der oberen linken Ecke anklicken.

    .. image:: img/calibrate0.png

    Klicken Sie auf den Button **Settings**.

    .. image:: img/calibrate1.png

    Auf dieser Seite können Sie den Produktnamen ändern, den Produkttyp auswählen, die App-Version ansehen oder den Roboter kalibrieren. Wenn Sie auf **Calibrate** klicken, gelangen Sie zur Kalibrierungsseite.

    .. image:: img/calibrate2.png
