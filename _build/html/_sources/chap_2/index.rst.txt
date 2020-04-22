多个文件
==========

如何用 ReadtheDocs、Sphinx 快速搭建写书环境
 `anonymous link to the Python website`__.

__ https://www.jianshu.com/p/78e9e1b8553a

上面介绍了一种方法：把文件分别放在不同文件夹里面。\
一个巧妙的地方是，toctree的toctree自动被当做子树。


.. toctree::
    :maxdepth: 2
    :numbered: 2

    01_linux
    02_ipython
    03_numpy
