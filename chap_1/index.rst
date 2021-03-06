语法篇
==========

基本语法测试
----------

`cheat-sheet of rst syntax <http://openalea.gforge.inria.fr/doc/openalea/doc/_build/html/source/sphinx/rest_syntax.html>`_ 

.. math:: \sum a_i 

.. code:: python

    import python3
        print("haha")


- A bullet list item
- Second item

  - A sub item

- Spacing between items separates list items

* Different bullet symbols create separate lists

- Third item

1) An enumerated list item

2) Second item

   a) Sub item that goes on at length and thus needs
      to be wrapped. Note the indentation that must
      match the beginning of the text, not the 
      enumerator.

      i) List items can even include

         paragraph breaks.

3) Third item

#) Another enumerated list item

#) Second item

A sentence with links to `Wikipedia`_ and the `Linux kernel archive`_.

.. _Wikipedia: https://www.wikipedia.org/
.. _Linux kernel archive: https://www.kernel.org/

 




::

  some literal text

This may also be used inline at the end of a paragraph, like so::

  some more literal text

.. code:: python

   print("A literal block directive explicitly marked as python code")


.. toctree::
    :maxdepth: 2
    :numbered: 2

    01_linux
    02_ipython
    03_numpy
