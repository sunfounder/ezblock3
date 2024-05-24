.. note::

    こんにちは、SunFounderのRaspberry Pi & Arduino & ESP32愛好家コミュニティへようこそ！Facebook上でRaspberry Pi、Arduino、ESP32についてもっと深く掘り下げ、他の愛好家と交流しましょう。

    **参加する理由は？**

    - **エキスパートサポート**：コミュニティやチームの助けを借りて、販売後の問題や技術的な課題を解決します。
    - **学び＆共有**：ヒントやチュートリアルを交換してスキルを向上させましょう。
    - **独占的なプレビュー**：新製品の発表や先行プレビューに早期アクセスしましょう。
    - **特別割引**：最新製品の独占割引をお楽しみください。
    - **祭りのプロモーションとギフト**：ギフトや祝日のプロモーションに参加しましょう。

    👉 私たちと一緒に探索し、創造する準備はできていますか？[|link_sf_facebook|]をクリックして今すぐ参加しましょう！

.. _install_ezblock_os_latest:

EzBlock OSのインストール
===========================

#. **EzBlock がプリインストールされた Raspberry Pi OS** イメージ ファイルをここからダウンロードします。

    https://ezblock.cc/download/v31.html

#. ダウンロードしたパッケージを解凍すると、中に ``.img`` ファイルが見えます。

    .. note::
        .imgファイルを解凍しないでください。

#. ツール - **Raspberry Pi Imager** を https://www.raspberrypi.org/software/ からダウンロードします。Raspberry Pi Imagerのリンクをクリックして、対応するオペレーティングシステムを選択してください。ダウンロードが完了したら、インストーラーを起動します。

    .. image:: img/image11.png
        :align: center

#. インストーラーを起動すると、オペレーティングシステムが実行をブロックしようとする場合があります。たとえば、Windowsでは次のようなメッセージが表示されます。このポップアップが表示された場合は、 **More info** をクリックし、次に **Run anyway** をクリックし、Raspberry Pi Imagerのインストール手順に従ってください。

    .. image:: img/image12.png
        :align: center

#. SDカードをコンピューターやラップトップのSDカードスロットに挿入します。次に、Raspberry Pi Imagerを開き、 **CHOOSE OS** をクリックします。

    .. image:: img/choose_os.png
        :align: center

#. ページの下部に移動して **Use Custom** を選択します。ポップアップウィンドウで、 **ステップ1** でダウンロードした **RaspiOS-xxx_EzBlockOS-xxx.img** を選択し、 **Open** をクリックします。

    .. image:: img/use_custom.png
        :align: center

#. 使用しているSDカードを選択します。

    .. image:: img/image14.png
            :align: center

#. **Ctrl+Shift+X** を押すか、 **settings** アイコンをクリックして、 **Advanced options** ページを開き、ホスト名を設定し、SSHを有効にし、ユーザー名とパスワードを設定します。この画像のカスタマイズオプションを常に使用することを選択できます。

    .. note::
        ホスト名は、あなたが :ref:`use_on_web_latest` を使用する際、ホスト名で製品に接続できるように設定されます。また、設定しなくてもかまいません。

    .. image:: img/configure.png
        :align: center

#. 次に、wifiの設定を完了して、 **SAVE** をクリックします。

    .. note::

        **wifi country** は、Raspberry Piを使用している国の二文字の `ISO/IEC alpha2コード <https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements>`_ に設定する必要があります。

        このステップはオプションです。このステップでWIFIを設定しない場合、後でアプリを使用して直接設定することもできます。

    .. image:: img/image16.png
        :align: center

#. **WRITE** ボタンをクリックします。

    .. image:: img/image17.png
        :align: center

#. しばらく待っていると、イメージがMicro SDカードに書き込まれたことを通知するプロンプトが表示され、それを取り外すことができます。次に、それをRaspberry Piに挿入します。

    .. image:: img/burning2.png
        :align: center

