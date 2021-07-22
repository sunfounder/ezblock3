Quick User Guide for Ezblock 3
=====================================

About Ezblock 3
----------------------

Compared with the Bluetooth communication of EzBlock 2, EzBlock 3 uses Websocket to communicate, which is much faster.

To make it faster and easier to use, we have optimized the connection and usage process so that you can learn programming quickly with Ezblock Studio.

The Ezblock 3 version should be used with the Ezblock 3 image (`Ezblock Studio Download Center <https://ezblock.cc/download/index.html>`_). The v3.0 version is currently in the public test stage. 

Ezblock 3 is still in public beta. Please do not hesitate to point out any inconveniences or errors, and any suggestions are welcome.

Here is the Email: cs@sunfounder.com.

Download and Install Ezblock OS
------------------------------------

#. Download the **Raspberry Pi OS with Ezblock Pre-installed** image file here: http://ezblock.cc/download/v3.html.

#. Unzip the package downloaded and you will see the .img file inside.

    .. note::
        Do not extract the .img file.


#. Downlaod the tool - Raspberry Pi Imager from https://www.raspberrypi.org/software/. Click on the link for the Raspberry Pi Imager that matches your operating system, when the download finishes, click it to launch the installer.

    .. image:: img/image11.png
        :align: center

#. When you launch the installer, your operating system may try to block you from running it. For example, on Windows I receive the followingmessage. If this pops up, click on **More info** and then **Run anyway**, then follow the instructions to install the Raspberry Pi Imager.
    
    .. image:: img/image12.png
        :align: center

#. Insert your SD card into the computer or laptop SD card slot. Then open Raspberry Pi Imager and click **CHOOSE OS**.

    .. image:: img/choose_os.png
        :align: center
#. Scroll down to the bottom and select **Use Custom**. On the pop-up page, select the image you downloaded from `Ezblock Studio Download Center <http://ezblock.cc/download/v3.html>`_ and click **Open**.
        
    .. image:: img/use_custom.png
        :align: center

#. Select the SD card you are using.
        
    .. image:: img/image14.png
            :align: center

#. Press **Ctrl+Shift+X** to open the **Advanced options** page to set hostname and enable SSH. You can choose to always use this image customization options.

    .. note::
        The hostname is set so that when you use Ezblock Studio on the web, you can use the hostname to connect to your product. You can also leave it unset.

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

Install Ezblock Studio
-------------------------------

**Ezblock Studio** is a development platform developed by SunFounder designed for beginners to lower the barriers to getting started with Raspberry Pi. 

It has two programming languages: Graphical and Python, and available on almost all different types of devices.

With Bluetooth and Wi-Fi support, you can download code, remote control a Raspberry Pi, on Ezblock Studio.

Open App Store (iOS/Mac OS X system) or Play Store (Android/Windows/Linux system), then search and download Ezblock Studio.

.. image:: img/IMG_0407.PNG
    :align: center

How to enter Ezblock Studio 3?
------------------------------------------------------

1. Open Ezblock Studio and log in to your account.
#. Go to your account page by clicking on your avatar in the upper right corner of the home page.
#. Go to the **Setting** page, and then click **About Version**.

    .. image:: img/imgIMG_0381.PNG
        :width: 600
        :align: center

#. Click **Enter a new version** in the pop-up window.

    .. image:: img/imgIMG_0382.PNG
            :align: center

#. A new pop-up window will appear, select **Enter a new version** again.

    .. image:: img/imgIMG_0383.PNG
        :align: center

#. After a few minutes of loading, you will enter the Ezblock 3.

How to connect the product and Ezblock Studio?
------------------------------------------------------

1. At this time, there is a pop-up window with an empty device list. You need to power on your product and turn on the Bluetooth of your mobile device at the same time, then the product number will appear.

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

        If you have already configured Wi-Fi on the Raspberry Pi Imager, then this step of **Quick Configuration** will not appear and you will go directly to the next step **Set Name**.

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


How to go back to Ezblock 2?
----------------------------------------

1. If you are not used to the Ezblock 3, then you can go back to the Ezblock 2.
#. Click the **menu** icon in the upper right corner of the homepage.

    .. image:: img/imgIMG_0406.png
        :align: center

#. Click **Version**.

    .. image:: img/imgIMG_0405.png
        :align: center

#. Click **Head to EzBlock version 2.5** to jump to Ezblock 2!

    .. image:: img/imgIMG_0404.png
        :align: center