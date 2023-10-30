.. _connect_product_ezblock_latest:

连接产品和EzBlock
=====================================================

#. 将Robot HAT的电源开关切换到ON位置。片刻之后，您将听到开机的声音，这意味着树莓派已成功启动。

    .. image:: img/slide_to_power.png
            :align: center

#. 连接您的移动设备（手机/平板）到WiFi，并打开蓝牙。

    .. image:: img/open_wif_bluetooth.jpg
        :align: center

#. 现在打开APP-EzBlock Studio，系统会提示您允许EzBlock Studio访问以下2个权限。

    * 访问您设备上的照片、媒体和文件：如果您已登录并需要更改头像，APP需要访问您设备的照片；当您使用产品的拍照功能时，APP需要此权限来保存照片。
    * 访问您设备的位置：此权限必须选择为 **Allow** ，否则APP将无法通过蓝牙连接到产品。

    .. image:: img/allow_access.jpg
        :align: center

#. 点击左上角的连接图标。

    .. image:: img/sp221115_143525.png
        :align: center

#. 在弹出的页面上，点击连接。

    .. image:: img/click_connect.jpg
        :align: center

#. 现在进入蓝牙连接页面，它将自动搜索对应的蓝牙，通常产品名称为ezb-Raspberry，但不同产品的MAC地址各不相同。如果您有多个产品，可以通过MAC地址来识别。另外，此蓝牙名称在后续步骤中可以更改。

    .. image:: img/connect_bluetooth.jpg
        :align: center

#. 当连接成功时，您的产品会发出“叮咚”的声音，而应用会提示连接成功。

    .. image:: img/connect_success.jpg
        :align: center

#. 如果这是您第一次使用此产品，系统将提示您对其进行快速配置。

    .. image:: img/config.jpg
        :align: center

#. 输入您的Wi-Fi帐号和密码。

    .. Note::

        * 如果您已在 **Raspberry Pi Imager** 上配置过Wi-Fi，则此步骤不会出现，您将直接进入下一步。
        * 此步骤是为树莓派配置WiFi，需要与您的移动设备（手机/平板）处于同一WiFi网络中。

    .. image:: img/connect_wifi.jpg
        :align: center

#. 选择匹配的产品。

    .. image:: img/select_product.jpg
        :align: center

#. 为您的产品取一个独特的名字，这将是您的蓝牙名称（在重启产品和应用后生效），当您在浏览器上使用EzBlock时，也可以用作主机名，有关更多详细信息，请参见 :ref:`use_on_web_latest`。

    .. image:: img/set_name.jpg
        :align: center

#. 如果您的产品需要进行校准，将会有提示告诉您可以通过点击 **Calibration Now** 进入校准页面。如果不需要，则弹窗消失并返回主页。

    .. image:: img/calibration.jpg
        :align: center

#. 每个产品的校准页面都不同，但有提示需要校准哪个部分。您可以点击相应的部分，然后参照 **Calibration Help** 进行校准。校准完成后，点击 **Comfirm** 。

    .. image:: img/cali_page.jpg
        :align: center

.. note::
    如果您在使用过程中想要重新校准机器人，请按照以下步骤操作。

    您可以通过点击左上角的连接图标打开产品详情页面。

    .. image:: img/calibrate0.png

    点击 **Settings** 按钮。

    .. image:: img/calibrate1.png

    在此页面，您可以更改产品名称、产品类型、查看应用版本或校准机器人。一旦您点击 **Calibrate** ，您可以进入校准页面。

    .. image:: img/calibrate2.png

