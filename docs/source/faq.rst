常见问题解答
============

检查APP版本
-----------------------------

按照以下方法确认应用版本，然后前往不同版本的常见问题解答。

点击左上角的 **Menu** 按钮。

.. image:: img/click_menu.jpg
    :align: center

接着点击 **Version** 按钮。

.. image:: img/version.jpg
    :align: center

现在您可以查看到版本信息。

.. note::

    如果是EzBlock 3.1，建议您更新至最新版本，详细教程请参见：:ref:`quick_guide_latest`。

    .. image:: img/check_version.png
        :align: center



EzBlock Studio 3.1
--------------------------

#. APP无法搜索到蓝牙

    * 开启产品电源，查看是否有悦耳的音乐声（而非仅有"zi~"的声音）。若无，请重新 :ref:`install_ezblock_os_latest`。
    * 检查您的移动设备的蓝牙是否已开启。
    * 检查应用是否获得了访问设备位置的权限。
    * 有些移动设备还需要开启位置服务功能。
    * 检查电源状态。如果两个电源指示灯都熄灭，或只有一个在闪烁；则表示电量较低，请充电。
    * 如果以上方法都已尝试，可尝试按下RST按钮，或重启产品和APP。

#. APP搜索到蓝牙但无法连接。

    * 开启产品电源，查看是否有悦耳的音乐声（而非仅有"zi~"的声音）。若无，请重新 :ref:`install_ezblock_os_latest`。
    * 检查ROBOT HAT上的BLE或USR灯是否常亮（意味着产品已被其他设备连接），如是，请断开其他设备连接或重启产品。
    * 如果以上方法都已尝试，可尝试按下RST按钮，或重启产品和APP。

#. 配置WIFI后APP无法连接。

    * 检查国家、SSID及PSK是否正确。
    * 检查此WIFI的网络状态。
    * 检查电源状态。如果两个电源指示灯都熄灭或只有一个电源指示灯在闪烁；则表示电量较低，请充电。
    * 检查配置的WiFi与移动设备连接的WiFi是否一致。

#. 视频模块不工作？

    .. image:: img/video_not.png
        :width: 400

    当在网页上使用视频功能时，如果您的代码没有报错并已成功运行，但在遥控页面上看不到拍摄画面，您需要检查以下2种情况：

    * 检查网络状态并重试。
    * 对于Google Chrome的最新版本，您需要手动设置。
        
        打开Google Chrome并前往：chrome://flags/page。

        .. image:: img/chrome1.jpg

        搜索：Block insecure private network requests

        .. image:: img/chrome2.jpg

        设置为 **Disabled**，然后点击 **Relaunch**。



.. EzBlock Studio 3.0
.. -------------------------------

.. .. note::
..     EzBlock Studio已更新至3.1版本，建议您更新至最新版本，详细教程请参见：:ref:`quick_guide_latest`。

.. #. APP无法搜索到蓝牙
..     * 开启产品，听到当前的"zi~"声音后，再出现一段悦耳的音乐；这意味着EzBlock OS下载不正确，请参照:ref:`install_ezblock_os_3.0`安装正确版本。
..     * 检查您的移动设备的蓝牙是否已开启。
..     * 确认应用是否被授权访问设备位置。
..     * 部分移动设备需要开启位置服务功能。
..     * 检查电源状态。如果两个电源指示灯都熄灭或只有一个在闪烁；则表示电量较低，请充电。
..     * 如果已尝试上述所有方法，可试着按下RST按钮，或重启产品和APP。

.. #. APP搜索到蓝牙但无法连接
..     * 开启产品，听到当前的"zi~"声音后，再出现一段悦耳的音乐；这意味着EzBlock OS下载不正确，请参照:ref:`install_ezblock_os_3.0`安装正确版本。
..     * 检查ROBOT HAT上的BLE或USR指示灯是否常亮（表示产品已被其他设备连接），如果是，请断开其他设备的连接或重启产品。
..     * 如果已尝试上述所有方法，可试着按下RST按钮，或重启产品和APP。

.. #. 配置WIFI后APP无法连接
..     * 确认国家、SSID和PSK设置是否正确。
..     * 检查此WIFI的网络状态。
..     * 检查电源状态。如果两个电源指示灯都熄灭或只有一个在闪烁；则表示电量较低，请充电。
..     * 确认配置的WiFi与移动设备连接的WiFi是否相同。
