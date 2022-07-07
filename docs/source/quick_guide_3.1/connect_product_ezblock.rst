.. _connect_product_ezblock_3.1:

Connect the Product and EzBlock(3.1)
=====================================================

#. Toggle the power switch of the Robot HAT to the ON position. After a while, you will hear a power-on sound, which means the Raspberry Pi has been successfully started.

    .. image:: ../img/slide_to_power.png
            :align: center

#. Connect your mobile device (phone/tablet) to WiFi and turn on Bluetooth.

    .. image:: ../img/ezblock3.1/open_wif_bluetooth.jpg
        :align: center

#. Now open the APP-EzBlock Studio, you will be prompted to allow EzBlock Studio access to the following 2 permissions.
    
    * Access photos, media and files on your device: If you are logged in and need to change your avatar, the APP needs access to your device's photos; when you use the product's photo feature, the APP needs this permission to save the photos.
    * Access your device's location: This permission must be selected as **Allow**, otherwise APP will not be able to connect to the product via Bluetooth.


    .. image:: ../img/ezblock3.1/allow_access.jpg
        :align: center

#. Click the Connect icon in the upper left corner.

    .. image:: ../img/ezblock3.1/connect_icon.jpg
        :align: center

#. On the pop-up page, click Connect.

    .. image:: ../img/ezblock3.1/click_connect.jpg
        :align: center



#. Now enter the Bluetooth connection page, it will automatically search for the corresponding Bluetooth, usually the product name is ezb-Raspberry, but the MAC address is different for different products. If you have more than one product, you can identify it by MAC address. Also this Bluetooth name can be changed in the next steps.

    .. image:: ../img/ezblock3.1/connect_bluetooth.jpg
        :align: center


#. When the connection is successful, your product will make a "ding dong" sound and the app will prompt that the connection is successful.

    .. image:: ../img/ezblock3.1/connect_success.jpg
        :align: center


#. If this is your first time using this product, you will be prompted for a quick configuration of it.

    .. image:: ../img/ezblock3.1/config.jpg
        :align: center

#. Enter your Wi-Fi account and password.

    .. Note::

        * If you have already configured Wi-Fi on the **Raspberry Pi Imager**, then this step will not appear and you will go directly to the next step.
        * This step is to configure WiFi for the Raspberry Pi, which needs to be the same WiFi network as your mobile device (phone/tablet).


    .. image:: ../img/ezblock3.1/connect_wifi.jpg
        :align: center


#. Select the matching product.

    .. image:: ../img/ezblock3.1/select_product.jpg
        :align: center


#. Give your product a unique name, which will be your Bluetooth name ( takes effect after restarting the product and app) and can also be used as hostname when you use EzBlock on a browser, see :ref:`use_on_web_3.1` for more details.

    .. image:: ../img/ezblock3.1/set_name.jpg
        :align: center


#. If your product needs to be calibrated, there will be a prompt telling you that you can enter the calibration page by clicking **Calibration Now**. If it is not needed, the pop-up window disappears and returns to the home page.

    .. image:: ../img/ezblock3.1/calibration.jpg
        :align: center

#. The calibration page of each product is different, but there is a reminder which part needs to be calibrated. You can click the corresponding part, and then refer to the **Calibration Help** to calibrate. After the calibration is completed, click **Comfirm**.

    .. image:: ../img/ezblock3.1/cali_page.jpg
        :align: center