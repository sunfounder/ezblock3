.. _connect_product_ezblock_latest:

製品とEzBlockを接続する
=====================================================

#. ロボットHATの電源スイッチをONの位置に切り替えます。しばらくすると電源が入った音が聞こえ、Raspberry Piが正常に起動したことを意味します。

    .. image:: img/slide_to_power.png
            :align: center

#. お使いのモバイルデバイス（携帯/タブレット）のWiFiに接続し、Bluetoothをオンにします。

    .. image:: img/open_wif_bluetooth.jpg
        :align: center

#. APP-EzBlock Studioを開くと、EzBlock Studioが以下の2つの許可にアクセスすることを求められます。

    * デバイスの写真、メディア、ファイルへのアクセス：ログインしていてアバターを変更する必要がある場合、APPはデバイスの写真にアクセスする必要があります。製品の写真機能を使用する場合、写真を保存するためにこの許可が必要です。
    * デバイスの位置へのアクセス：この許可は **Allow** として選択する必要があり、そうしないとAPPはBluetooth経由で製品に接続できません。

    .. image:: img/allow_access.jpg
        :align: center

#. 左上隅のConnectアイコンをクリックします。

    .. image:: img/sp221115_143525.png
        :align: center

#. ポップアップページで、Connectをクリックします。

    .. image:: img/click_connect.jpg
        :align: center

#. Bluetooth接続ページに移動すると、対応するBluetoothを自動的に検索します。通常、製品名はezb-Raspberryですが、異なる製品ではMACアドレスが異なります。複数の製品をお持ちの場合、MACアドレスで識別できます。また、このBluetooth名は次の手順で変更できます。

    .. image:: img/connect_bluetooth.jpg
        :align: center

#. 接続が成功すると、製品から「ディンドン」という音が鳴り、アプリが接続に成功したことをお知らせします。

    .. image:: img/connect_success.jpg
        :align: center

#. この製品を初めて使用する場合、その製品の簡単な設定を促すプロンプトが表示されます。

    .. image:: img/config.jpg
        :align: center

#. Wi-Fiのアカウントとパスワードを入力します。

    .. Note::

        * **Raspberry Pi Imager** でWi-Fiを既に設定している場合、この手順は表示されず、次の手順に直接進むことができます。
        * この手順は、Raspberry PiのWiFiを設定するためのもので、お使いのモバイルデバイス（携帯/タブレット）と同じWiFiネットワークである必要があります。

    .. image:: img/connect_wifi.jpg
        :align: center

#. 対応する製品を選択します。

    .. image:: img/select_product.jpg
        :align: center

#. 製品に一意の名前を付けます。これはBluetooth名として使用され（製品とアプリの再起動後に有効）、EzBlockをブラウザで使用する場合のホスト名としても使用できます。詳細については、 :ref:`use_on_web_latest` を参照してください。

    .. image:: img/set_name.jpg
        :align: center


#. 製品がキャリブレーションが必要な場合、 **Calibration Now** をクリックするとキャリブレーションページにアクセスできる旨のプロンプトが表示されます。キャリブレーションの必要がない場合、ポップアップウィンドウは消えてホームページに戻ります。

    .. image:: img/calibration.jpg
        :align: center

#. 各製品のキャリブレーションページは異なりますが、キャリブレーションが必要な部分にはリマインダーが表示されます。対応する部分をクリックし、 **Calibration Help** を参照してキャリブレーションを行ってください。キャリブレーションが完了したら、 **Comfirm** をクリックします。

    .. image:: img/cali_page.jpg
        :align: center

.. note::
    使用中にロボットのキャリブレーションを再度行いたい場合、以下の手順に従ってください。

    左上の接続アイコンをクリックして製品の詳細ページを開きます。

    .. image:: img/calibrate0.png

    **Settings** ボタンをクリックします。

    .. image:: img/calibrate1.png

    このページで、製品名や製品タイプの変更、アプリのバージョンの確認、またはロボットのキャリブレーションができます。 **Calibrate** をクリックするとキャリブレーションページに進むことができます。

    .. image:: img/calibrate2.png
