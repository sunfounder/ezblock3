.. _install_ezblock_os_latest:

安装EzBlock操作系统
===========================

#. 从此处下载 **预装EzBlock的树莓派操作系统** 镜像文件：

    https://ezblock.cc/download/v31.html


#. 解压您下载的包，您会看到里面的 ``.img`` 文件。

    .. note::
        不要提取.img文件。

#. 从 https://www.raspberrypi.org/software/ 下载工具 - **Raspberry Pi Imager** 。点击与您操作系统匹配的Raspberry Pi Imager链接，下载完成后，点击启动安装程序。

    .. image:: img/image11.png
        :align: center

#. 当您启动安装程序时，您的操作系统可能会试图阻止您运行它。例如，在Windows上，我收到以下消息。如果弹出此消息，点击 **More info** ，然后点击 **Run anyway** ，然后按照指引安装Raspberry Pi Imager。

    .. image:: img/image12.png
        :align: center

#. 将您的SD卡插入计算机或笔记本电脑的SD卡插槽。然后打开Raspberry Pi Imager并点击 **CHOOSE OS**。

    .. image:: img/choose_os.png
        :align: center

#. 滚动至页面底部，选择 **Use Custom** 。在弹出窗口中，选择您在 **第1步** 中下载的 **RaspiOS-xxx_EzBlockOS-xxx.img** ，然后点击 **Open** 。
        
    .. image:: img/use_custom.png
        :align: center

#. 选择您正在使用的SD卡。
        
    .. image:: img/image14.png
            :align: center

#. 按 **Ctrl+Shift+X** 或点击 **settings** 图标，打开 **Advanced options** 页面来设置主机名、启用SSH以及设置用户名和密码。您可以选择总是使用此图像的自定义选项。

    .. note::
        设置主机名是为了您在 :ref:`use_on_web_latest` 时，可以使用主机名连接到您的产品。您也可以选择不设置。

    .. image:: img/configure.png
        :align: center

#. 然后向下滚动以完成wifi配置，然后点击 **SAVE** 。

    .. note::

        **wifi country** 应设置为您正在使用树莓派的国家的两个字母的 `ISO/IEC alpha2代码 <https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements>`_。
        
        此步骤是可选的，如果您在此步骤中不配置WIFI，您稍后也可以直接使用应用程序来配置。

    .. image:: img/image16.png
        :align: center

#. 点击 **WRITE** 按钮。

    .. image:: img/image17.png
        :align: center


#. 等待一段时间后，系统会提示您镜像已写入到您的Micro SD卡中，您可以取出它。然后，您可以将其插入树莓派。

    .. image:: img/burning2.png
        :align: center
