.. _install_ezblock_os_3.0:

Install EzBlock OS(3.0)
================================

#. Download the **Raspberry Pi OS with EzBlock Pre-installed** image file here: 

    https://ezblock.cc/download/v3.html.

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
#. Scroll down to the bottom and select **Use Custom**. In the pop-up window, select **RaspiOS-xxx_EzBlockOS-xxx.img** that you downloaded in **Step 1**, and click **Open**.
        
    .. image:: img/use_custom.png
        :align: center

#. Select the SD card you are using.
        
    .. image:: img/image14.png
            :align: center

#. Press **Ctrl+Shift+X** or click the **setting** button to open the **Advanced options** page to set hostname and enable SSH. You can choose to always use this image customization options.

    .. note::
        The hostname is set so that when you use the Ezblock Studio in a browser, you can use the hostname to connect to your product, see :ref:`use_on_web_latest` for more details. You can also leave it unset.

    .. image:: img/configure.png
        :align: center

#. Then scroll down to complete the wifi configuration and click **SAVE**.

    .. note::

        **wifi country** should be set the two-letter `ISO/IEC alpha2 code <https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements>`_ for the country in which you are using your Raspberry Pi.

    .. image:: img/image16.png
        :align: center

#. Click the **WRITE** button.

    .. image:: img/image17.png
        :align: center


#. After waiting for a while, you will be prompted to tell you that the image has been written to your Micro SD card and you can remove it. Then you can insert it into the Raspberry Pi.

    .. image:: img/burning2.png
        :align: center