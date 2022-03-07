.. _quick_guide_3.1:

Quick User Guide for EzBlock 3.1
=====================================

About EzBlock 3.1
----------------------

The update of Ezblock version 3.1 is mainly to optimize the connection at the bottom layer. Solved the problem that the Bluetooth of the Raspberry Pi could not be successfully paired when the peripheral was used in the past. This means that the Ezblock can directly pair with the Raspberry Pi's Bluetooth without the need for an external Bluetooth expansion board.
Note: The old version of the robot can also be used normally after burning the new image. The bluetooth module on the original robot hat will not conflict with the new system.

1. Compatible with the built-in Bluetooth of Raspberry Pi, no need to use an expansion board with Bluetooth. 
2. A custom Bluetooth name function has been added to the app to avoid the problem that multiple devices are indistinguishable. (Reboot to take effect.)
3. Added three sound effects for boot, successful connection, and disconnection, which gives more feedback.
4. The LED next to the power indicator will be used as a bluetooth indicator, which is always on when connected and flashes slowly when not connected.
5. (Android) Add a full-screen input box to prevent the input box from being blocked.
6. Optimize the battery display, now you can see more accurate information on the APP.
7. Optimized the usage details of some connection functions.


.. note::
    The EzBlock Studio 3.1 version should be used with the Ezblock 3.1 image (https://ezblock.cc/download/v3.1.html).


.. _ezblock_os_3.1:

Install EzBlock OS(3.1)
------------------------------------

#. Download the **Raspberry Pi OS with EzBlock Pre-installed** image file here: http://ezblock.cc/download/v3.1.html.

#. Unzip the package downloaded and you will see the ``.img`` file inside.

    .. note::
        Do not extract the .img file.


#. Downlaod the tool - **Raspberry Pi Imager** from https://www.raspberrypi.org/software/. Click on the link for the Raspberry Pi Imager that matches your operating system, when the download finishes, click it to launch the installer.

    .. image:: img/image11.png
        :align: center

#. When you launch the installer, your operating system may try to block you from running it. For example, on Windows I receive the following message. If this pops up, click on **More info** and then **Run anyway**, then follow the instructions to install the Raspberry Pi Imager.
    
    .. image:: img/image12.png
        :align: center

#. Insert your SD card into the computer or laptop SD card slot. Then open Raspberry Pi Imager and click **CHOOSE OS**.

    .. image:: img/choose_os.png
        :align: center

#. Scroll down to the bottom and select **Use Custom**. On the pop-up page, select the image you downloaded from `EzBlock Studio Download Center <http://ezblock.cc/download/v3.html>`_ and click **Open**.
        
    .. image:: img/use_custom.png
        :align: center

#. Select the SD card you are using.
        
    .. image:: img/image14.png
            :align: center

#. Press **Ctrl+Shift+X** to open the **Advanced options** page to set hostname and enable SSH. You can choose to always use this image customization options.

    .. note::
        The hostname is set so that when you `use Ezblock Studio in a browser <https://docs.sunfounder.com/projects/ezblock3/en/latest/use_on_the_web.html>`_, you can use the hostname to connect to your product. You can also leave it unset.


    .. image:: img/configure.png
        :align: center

#. Then scroll down to complete the wifi configuration and click **SAVE**.

    .. note::

        **wifi country** should be set the two-letter `ISO/IEC alpha2 code <https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements>`_ for the country in which you are using your Raspberry Pi.
        
        This step is optional, if you do not configure WIFI in this step, you can also use the app to configure it directly later.

    .. image:: img/image16.png
        :align: center

#. Click the **WRITE** button.

    .. image:: img/image17.png
        :align: center


#. After waiting for a while, you will be prompted to tell you that the image has been written to your Micro SD card and you can remove it. Then you can insert it into the Raspberry Pi.

    .. image:: img/burning2.png
        :align: center

Install EzBlock Studio
-------------------------------

**EzBlock Studio** is an App for programming and controlling SunFounder Raspberry Pi robots, which allows beginners (students) to quickly get started with Raspberry Pi robot programming. It has built-in TTS, camera recognition, remote control, music/sound effects, and sensor control functions.

Open App Store (iOS) or Play Store (Android), then search and download **EzBlock Studio**.

Linux/Mac OS X system/Windows users can use EzBlock Studio in a browser. For a detailed tutorial, please refer to: https://docs.sunfounder.com/projects/ezblock3/en/latest/use_on_the_web.html.

.. image:: img/IMG_0407.PNG
    :align: center


How to Connect the Product and EzBlock Studio?
------------------------------------------------------

1. Toggle the power switch of the Robot HAT to the ON position. After a while, you will hear a power-on sound, which means the Raspberry Pi has been successfully started.

#. Connect your mobile device (phone/tablet) to WiFi and turn on Bluetooth.

    .. image:: img/ezblock3.1/open_wif_bluetooth.jpg
        :align: center

#. Now open the APP-EzBlock Studio, you will be prompted to allow EzBlock Studio access to the following 2 permissions.
    
    * Access photos, media and files on your device: If you are logged in and need to change your avatar, the APP needs access to your device's photos; when you use the product's photo feature, the APP needs this permission to save the photos.
    * Access your device's location: This permission must be selected as **Allow**, otherwise APP will not be able to connect to the product via Bluetooth.


    .. image:: img/ezblock3.1/allow_access.jpg
        :align: center

#. Click the Connect icon in the upper left corner.

    .. image:: img/ezblock3.1/connect_icon.jpg
        :align: center

#. On the pop-up page, click Connect.

    .. image:: img/ezblock3.1/click_connect.jpg
        :align: center



#. Now enter the Bluetooth connection page, it will automatically search for the corresponding Bluetooth, usually the product name is ezb-Raspberry, but the MAC address is different for different products. If you have more than one product, you can identify it by MAC address. Also this Bluetooth name can be changed in the next steps.

    .. image:: img/ezblock3.1/connect_bluetooth.jpg
        :align: center


#. When the connection is successful, your product will make a "ding dong" sound and the app will prompt that the connection is successful.

    .. image:: img/ezblock3.1/connect_success.jpg
        :align: center


#. If this is your first time using this product, you will be prompted for a quick configuration of it.

    .. image:: img/ezblock3.1/config.jpg
        :align: center

#. Enter your Wi-Fi account and password.

    .. Note::

        * If you have already configured Wi-Fi on the **Raspberry Pi Imager**, then this step will not appear and you will go directly to the next step.
        * This step is to configure WiFi for the Raspberry Pi, which needs to be the same WiFi network as your mobile device (phone/tablet).


    .. image:: img/ezblock3.1/connect_wifi.jpg
        :align: center


#. Select the matching product.

    .. image:: img/ezblock3.1/select_product.jpg
        :align: center


#. Give your product a unique name, which will be your Bluetooth name ( takes effect after restarting the product and app) and can also be used as hostname when you `use Ezblock Studio in a browser <https://docs.sunfounder.com/projects/ezblock3/en/latest/use_on_the_web.html>`_.

    .. image:: img/ezblock3.1/set_name.jpg
        :align: center


#. If your product needs to be calibrated, there will be a prompt telling you that you can enter the calibration page by clicking **Calibration Now**. If it is not needed, the pop-up window disappears and returns to the home page.

    .. image:: img/ezblock3.1/calibration.jpg
        :align: center

#. The calibration page of each product is different, but there is a reminder which part needs to be calibrated. You can click the corresponding part, and then refer to the **Calibration Help** to calibrate. After the calibration is completed, click **Comfirm**.

    .. image:: img/ezblock3.1/cali_page.jpg
        :align: center

How to Open and Run examples?
-----------------------------------
1. On the homepage, click **Examples** to enter the Examples page. If you just need to simply test these examples, you only need to click **Run** to make your product work.

    .. image:: img/imgIMG_0392.PNG
        :align: center

#. If you want to view and modify the code inside, then you need to click **Edit**. The following picture is the programming page.

    .. image:: img/imgIMG_0393.PNG
        :align: center
