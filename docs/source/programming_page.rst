.. _programming_block:

编程页面
==========================

当您编写代码（创建新项目、编辑示例、编辑个人项目）时，您将进入编程页面。
此处显示的是Blockly语言的编程界面。关于Python语言的编程，请查看 :ref:`programming_python`。

.. image:: img/sp210805_143809.png

1. 返回主页
2. 选择产品
3. 项目名称
4. 帮助
5. 菜单
6. 编程界面

7. 遥控界面
8. 调试监视器

A. 代码块分类
B. 编程区域
C. 运行
D. 烧录并运行

**代码块分类**

.. image:: img/sp210805_151353.png

从此处找到代码块，并将代码块拖到编程区域进行编程。具体用法请查看 `代码块参考 <https://docs.ezblock.cc/en/latest/reference-for-block/block.html>`_。

**调试监视器**

.. image:: img/sp210805_145042.png

点击右下角的调试图标，会出现一个可移动的调试监视器。 **print** 块的文本会在这里显示。

**帮助**

.. image:: img/sp210805_150120.png

选择后，ezblock的教程会弹出，包括FAQ、入门指南和 `参考 <https://docs.ezblock.cc/en/latest/reference.html>`_。

**菜单**

.. image:: img/sp210805_150436.png

* **New Project**：用于创建一个新项目。
* **My Projects**：使用此按钮进入 **My Projects** 页面，查看、导出或导入项目或库。
* **Save**：将项目添加到 **My Projects**。
* **Save As**：项目以新文件名保存到 **My Projects** 页面。
* **Create Library**：通过选择项目中的功能来创建一个库。详细教程请参考：:ref:`library_function_latest`。
* **Import Library**：导入已保存的库。
* **Save As File**：保存到设备的文件夹。如果您通过Web访问EzBlock Studio，项目(``.ezbpro``)将下载到您的计算机。使用移动设备，您可以将项目(``.ezbpro``)保存到设备文件夹或使用应用程序共享。





**提示**

您可以长按编程区域或代码块来使用一些辅助功能。

.. image:: img/sp210805_151610.png
.. image:: img/sp210805_151819.png

.. list-table:: 代码块菜单

    * - **选项**
      - **描述**
    * - Duplicate 
      - 复制选中的（及其子块）代码块。
    * - Add/Remove Comment
      - 点击后，代码块右上角会出现一个 ``?`` 图标，用于添加有助于阅读代码的文字。这些文字不会被程序执行。
    * - Expand/Conllapse Block
      - 当您的代码有更多的块时，可以折叠它们，并在需要时展开。
    * - Disable/Enable Block
      - 此功能可以禁用特定的代码块，而不更改程序。
    * - Delete `xxx` Blocks
      - 移除选中的（及其子块）代码块。
    * - 帮助
      - 
    * - Create `xxx`
      - 用于 `Vibration` 或 `Function` 代码块。它允许您快速创建与所选代码块配对的块（从函数块点击`创建`，调用块就会出现）。
    * - Hightlight Function Definition
      - 用于函数的调用块，允许您找到函数的定义。

.. list-table:: 编程页面菜单

    * - **选项**
      - **描述**
    * - Undo
      - 
    * - Redo
      - 取消撤销
    * - Clean up Blocks
      - 对齐代码块
    * - Conllapse Blocks
      - 折叠所有的块
    * - Expand Blocks
      - 展开所有的块
    * - Delete `xxx` Blocks
      - 删除所有的代码块


.. _programming_python:


Python编程页面
-----------------------

当您创建项目时选择Python语言，您可以进入Python编程页面。

.. image:: img/sp210805_154924.png

为了完成您的项目，您需要参考 `Python参考 <https://docs.ezblock.cc/en/latest/reference-for-python/ezblock.html>`_。



遥控界面
------------------------

关于如何使用，请查看 :ref:`remote_control_latest`

.. image:: img/sp210805_144019.png

1. 控件类别
2. 遥控区域

.. image:: img/sp210805_152451.png

点击控件以显示消息框，长按控件或点击删除按钮以删除该控件。

.. list-table:: 遥控界面的控件

    * - **控件**
      - **描述**
    * - 操纵杆
      - 白点居中时，X和Y值都是0。向右拖动白点以增加X值；向上拖动以增加Y值。X和Y的范围均为(-100, 100)。
    * - 滑杆
      - 当白点在最左侧时，值为0。向右拖动白点以增加值。范围是(0, 100)。
    * - 方向键
      - 由4个按钮组成的控制器，每个按钮互不影响。按下时按钮的值为1，释放时值为0。
    * - 按钮
      - 按下时的值为1，释放时的值为0。
    * - 开关
      - 打开时，值为1；关闭时，值为0。
    * - 视频
      - 请查看 :ref:`video_latest`
    * - 数字管
      - 可以像真实的四位数字管一样显示数字（如123.3）或时间（如11:55）。
    * - 饼状图
      - 用于指示数据系列中部分与整体的比例。每组数据应包含一个 ``name`` 和 ``value``。
    * - 柱状图
      - 可以直观地显示多个对象的数据，用于比较分析。每个对象应包括一个 ``name`` 和 ``value``。
    * - 折线图
      - 可以显示多个对象的连续数据。每个对象应包括一个 ``name`` 和 ``value``。连续数据的生成基于多次调用（通常使用循环）。
    * - 灯泡
      - 就像真实的LED，当写入1时它会亮起，写入0时则熄灭。

