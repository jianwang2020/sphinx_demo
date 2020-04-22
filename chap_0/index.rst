安装篇
==========

sphinx隶属于python工具系列。

有些电脑python分不清是2 还是3.
为了让环境清晰，我使用venv。
这个venv是python3自带的一个工具，进入了此venv环境后，pip和python的版本都是python3对应的那个版本。

.. code-block::

   $a = 'b';

.. code-block:: bash

    python3 -m venv venv
    source venv/bin/activate
 
    pip install sphinx    

    sphinx-quickstart

    make html

    make clean

    git add .
    git commit -m "hahaha"
    git push origin master

    deactivate   
