.. _quick_guide_3.0:

Quick User Guide for EzBlock 3.0
=====================================

About EzBlock 3.0
----------------------

Compared with the Bluetooth communication of EzBlock 2, EzBlock 3 uses Websocket to communicate, which is much faster.

To make it faster and easier to use, we have optimized the connection and usage process so that you can learn programming quickly with Ezblock Studio.

The EzBlock Studio 3 version should be used with the Ezblock 3 image (`Ezblock Studio Download Center <http://ezblock.cc/download/v3.html>`_).

.. note::
    EzBlock Studio has been updated to version 3.1, it is recommended to update to the new version, for a detailed tutorial please refer to: :ref:`quick_guide_3.1`.

.. _ezblock_os_3.0:

Install EzBlock OS(3.0)
-----------------------------------------

#. Download the **Raspberry Pi OS with EzBlock Pre-installed** image file here: https://ezblock.cc/download/v3.html.

#. Unzip the package downloaded and you will see the .img file inside.

    .. note::
        Do not extract the .img file.


#. Downlaod the tool - Raspberry Pi Imager from https://www.raspberrypi.org/software/. Click on the link for the Raspberry Pi Imager that matches your operating system, when the download finishes, click it to launch the installer.

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


How to connect the product and EzBlock Studio?
------------------------------------------------------
1. Open the Ezblock Studio, a window with an empty device list will pop-up. You need to power on your product and turn on the Bluetooth of your mobile device at the same time, then the product number will appear.

    .. image:: img/imgIMG_0388.PNG
        :align: center

#. Click **Done** in the upper right corner, and after a while, **Connection Successful** will appear.

    .. image:: img/imgIMG_0391.PNG
        :align: center

#. At this point you need to click **OK** to quickly configure your product.

    .. image:: img/imgIMG_0395.PNG
        :align: center

#. Enter your Wi-Fi account and password.

    .. note::

        If you have already configured Wi-Fi on the Raspberry Pi Imager, then this step will not appear and you will go directly to the next step.

    .. image:: img/imgIMG_0396.PNG
        :align: center

#. Select the product that matches yours.

    .. image:: img/imgIMG_0398.PNG
        :align: center

#. Enter a name for your product.

    .. image:: img/imgIMG_0399.PNG
        :align: center

#. If your product needs to be calibrated, there will be a prompt telling you that you can enter the calibration page by clicking **Calibrate Now**. If it is not needed, the pop-up window disappears and returns to the home page.

    .. image:: img/imgIMG_0401.PNG
        :align: center

#. The calibration page of each product is different, but there is a reminder which part needs to be calibrated. You can click the corresponding part, and then refer to the **Calibration Help** to calibrate. After the calibration is completed, click **Comfirm**.

    .. image:: img/imgIMG_0403.PNG
        :align: center

How to Open and Run examples?
-----------------------------------
1. On the homepage, click **Examples** to enter the Examples page. If you just need to simply test these examples, you only need to click **Run** to make your product work.

    .. image:: img/imgIMG_0392.PNG
        :align: center

#. If you want to view and modify the code inside, then you need to click **Edit**. The following picture is the programming page.

    .. image:: img/imgIMG_0393.PNG
        :align: center
