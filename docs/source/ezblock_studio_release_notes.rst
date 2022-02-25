Ezblock Studio Release Notes
=====================================


Ezblock Studio 3.1 2022.03.08
-----------------------------------------------

The update of Ezblock version 3.1 is mainly to optimize the connection at the bottom layer. Solved the problem that the Bluetooth of the Raspberry Pi could not be successfully paired when the peripheral was used in the past. This means that the Ezblock can directly pair with the Raspberry Pi's Bluetooth without the need for an external Bluetooth expansion board.
Note: The old version of the robot can also be used normally after burning the new image. The bluetooth module on the original robot hat will not conflict with the new system.

1. Compatible with the built-in Bluetooth of Raspberry Pi, no need to use an expansion board with Bluetooth. 
2. A custom Bluetooth name function has been added to the app to avoid the problem that multiple devices are indistinguishable. (Reboot to take effect.)
3. Added three sound effects for boot, successful connection, and disconnection, which gives more feedback.
4. The LED next to the power indicator will be used as a bluetooth indicator, which is always on when connected and flashes slowly when not connected.
5. (Android) Add a full-screen input box to prevent the input box from being blocked.
6. Optimize the battery display, now you can see more accurate information on the APP.
7. Optimized the usage details of some connection functions.




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