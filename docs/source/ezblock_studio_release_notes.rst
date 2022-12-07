Ezblock Studio Release Notes
=====================================



Ezblock Studio 3.2
-----------------------------------------------

EzBlock Studio will be switched to offline mode from version 3.2 and the online service will be closed on 2023/2/28 for user-friendly use. Thus, you can save your projects locally without registering and import them on different devices later.


**Detailed Information**

* EzBlock Studio转离线模式后，老用户可以继续登录，并保存云端项目到本地，但新项目都将保存在本地
* 注册入口关闭。新用户不在需要注册账户以使用EzBlock的项目保存功能。
* 新增项目导入导出功能。本地项目导入导出为.ezbpro文件，该功能可以实现设备间传输项目，或者分享项目给其他人
* 新增库导入导出功能。本地库导入导出为.ezblib文件，该功能可以实现设备间传输库，或者分享库给其他人


* After EzBlock Studio goes to offline mode, old users can continue to log in and save cloud projects to local, but all new projects will be saved locally.
* Registration portal is closed. New users are no longer required to register an account to use EzBlock's project saving feature.
* Add project import and export function in .ezbpro format, which allows you to transfer projects between devices or share projects with others.
* Libraries can also be imported and exported in .ezblib format for transfer and sharing.

**FAQ**

* What happens to my account?

    从XXX年X月起至XXX年X月X日，是过渡时间，这段时间内，你可以把云端的项目全部保存到本地。在Ezblock Studio登录后的提醒上点击“保存所有项目到本地”可以一键保存所有云端项目到本地，或者登录后在我的页面，点击“保存所有项目到本地”也可以一键保存所有云端项目到本地。
    XXX年X月X日后Ezblock Studio将会清除所有在线数据，并关闭在线服务。你也可以在“我的”页面点击“删除账户并退出”按钮来删除自己的所有数据

* 网页版EzBlock Studio可以正常使用吗？

可以正常使用。EzBlock Studio改为离线模式后，网页版仍然可以正常使用，数据将保存在浏览器，所以请注意谨慎清楚浏览器数据。网页版也可以使用项目和库的导入导出，并于移动端相互分享。

* 如何在设备间传输项目和我的库？

    新版本新增了项目和库的导入导出功能，项目可以导出为.ezbpro文件，库可以导出为.ezblib文件。导出后可以在其他设备导入项目和库

* 如何批量导出库/项目？

    在库/项目页面，点击右上角的编辑图标，多选想要导出的库/项目，点击导出。这样会导出一个zip文件。文件内是你选择的所有库/项目文件。导入时，你可以直接选择这个压缩包导入或者解压后选择想要的部分库/项目导入

* 如何批量导入库/项目？

    在库/项目页面，点击右上角的导入图标，多选想要导入的库/项目，或者选择导入的zip文件，点击导出。





Ezblock Studio 3.1
-----------------------------------------------

**Main Optimization**

The main optimization of EzBlock 3.1 is the compatibility with the built-in Bluetooth of the Raspberry Pi, no need to use an expansion board with Bluetooth module. 

.. note::
    * The old version of the robot can also be used normally after burning the new image. The bluetooth module on the original robot hat will not conflict with the new system.

    * The EzBlock Studio 3.1 version should be used with the Ezblock 3.1 image (https://ezblock.cc/download/v31.html).

**Add**

* A custom Bluetooth name function has been added to the app to avoid the problem that multiple devices are indistinguishable. (Reboot to take effect.)
* Added three sound effects for boot, successful connection, and disconnection, which gives more feedback.
* The LED next to the power indicator will be used as a bluetooth indicator, which is always on when connected and flashes slowly when not connected.
* (**Android**) Add a full-screen input box to prevent the input box from being blocked.


**Optimization**

* Optimize the battery display, now you can see more accurate information on the APP.
* Optimize the display of product example images and personal information icons.

**Fix**

* Fix a series of problems of Bluetooth search and Bluetooth connection.
* Fix the problem that the product name is not displayed after the wifi configuration.
* Fix the problem of product information not being saved after modification.
* Fix the problem that the picture cannot be saved after taking pictures in the remote control page.

Ezblock Studio 3 2021.06.08
-----------------------------

**Improve the product connection**

* Improve the connection method: Compared with the Bluetooth communication of EzBlock 2, EzBlock 3 uses Websocket to communicate, which is much faster.
* Improve the connection process: Ezblock 3 uses Bluetooth to assist with the product's fast Wi-Fi connection.


**Home Page**


- Remove the carousel.
- Remove the product selection page and change it to a pop-up window.
- Remove the way you must log in to get to the home page.

- Add My Project entry.
- Add Product Information pop-up window button. This Product Information pop-up window is used to show the product name, product type, IP, version, working voltage, and power.
- Add online update function of product image.
- Add product calibration function.
- Add product name modification function.
- Add the Menu function in the upper left corner.

- Optimize the pop-up window for New Project button.


**Examples Page**

* Beautify the UI.
* Add quick run/edit button.
* Add remote control or IoT prompt icon.

**Programming Page**

* Optimize the arrangement of Programming, IoT, Remote Control and Debug Monitor buttons.
* Add product connect button in the top left corner.
* Add Stop/Run program button.
* To save the project and enter the IoT page, make sure that you have logged in to your account.


**Personal Info Page**

* Remove the settings page.
* Add product category function to My Project page.


**Other**

* Change the font of all pages.
* Add the function of entering IP or hostname on the web to connect to the product.