################################################################################
reStructure 开始
################################################################################

记录一些内容, 写作一篇文章, 简单来说, 只需要几个注意少数几种格式即可:

#. 标题
#. 图片
#. 超链接
#. 代码

********************************************************************************
标题格式
********************************************************************************

标题

********************************************************************************
图片格式
********************************************************************************

整行图片一般如下:

.. image:: img/demo_png.png
    :width: 100 px
    :height: 100 px
    :alt: alternate text.
    :align: center

还有一种行内图片, 如果通过替换 replace 来实现.

|this| is inline image.

.. |this| image:: img/demo_png.png
    :width: 50 px
    :height: 50 px
    :align: top

********************************************************************************
超链接格式
********************************************************************************

- 行内 `百度1 <https://www.baidu.com>`_ 网络超链接, 仅适用于网络 URL.

- 行外 `百度2`_ 网络超链接.

.. _百度2: https://www.baidu.com

********************************************************************************
代码格式
********************************************************************************

.. function:: foo(x)
              foo(y, z)
   :module: some.module.name

   Return a line of text input from the user.

.. code-block::
   :caption: A cool example

       The output of this line starts with four spaces.

.. code-block::

       The output of this line has no spaces at the beginning.

.. code:: python

  def my_function():
      "just a test"
      print 8/2

.. code:: c++

    void init(int a, double b) {
        std::cout << "cout something.";
    }

待定
================================================================================

attention", "caution", "danger", "error", "hint", "important", "note", "tip", "warning", "admonition

.. attention::
    attention

.. caution::
    caution

.. danger::
    danger

.. error::
    error

.. hint::
    hint

.. important::
    important

.. note::
    note

.. tip::
    tip

.. warning::
    warning

.. admonition:: And, by the way...

   You can make up your own admonition too.


脚注

引文

替换
