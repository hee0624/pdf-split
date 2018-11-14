Split-Pdf
=========================
The usage is simple.

.. code-block:: shell

   python pypdf.py {read_file} {out_detail}

read_file: pdf文件
out_file: 分割配置

其中：配置格式为　起始页-结束页 分割文件名

例如：　2-4 项目申报书



Installation
------------

To install retrying, simply:

.. code-block:: bash

    $ pip install -r requests.txt




Examples
----------

As you saw above, the default behavior is to retry forever without waiting.

.. code-block:: shell

    python pypdf.py demo.pdf detail.conf


Let's be a little less persistent and set some boundaries, such as the number of attempts before giving up.

Contribute
----------

#. Check for open issues or open a fresh issue to start a discussion around a feature idea or a bug.
#. Fork `the repository`_ on GitHub to start making your changes to the **master** branch (or branch off of it).
#. Write a test which shows that the bug was fixed or that the feature works as expected.
#. Send a pull request and bug the maintainer until it gets merged and published. :) Make sure to add yourself to AUTHORS_.

.. _`the repository`: https://github.com/hee0624/pdf-split
.. _AUTHORS: https://hee0624.github.io/
