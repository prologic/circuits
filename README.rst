.. _Python Programming Language: http://www.python.org/
.. _#circuits IRC Channel: http://webchat.freenode.net/?randomnick=1&channels=circuits&uio=d4
.. _FreeNode IRC Network: http://freenode.net
.. _Python Standard Library: http://docs.python.org/library/
.. _MIT License: http://www.opensource.org/licenses/mit-license.php
.. _Create an Issue: https://github.com/circuits/circuits/issues/new
.. _Mailing List: http://groups.google.com/group/circuits-users
.. _Project Website: http://circuitsframework.com/
.. _PyPi Page: http://pypi.python.org/pypi/circuits
.. _Read the Docs: http://circuits.readthedocs.org/en/latest/
.. _View the ChangeLog: http://circuits.readthedocs.org/en/latest/changes.html
.. _Downloads Page: https://github.com/circuits/circuits/releases

.. image:: https://travis-ci.org/circuits/circuits.svg
   :target: https://travis-ci.org/circuits/circuits
   :alt: Build Status

.. image:: https://coveralls.io/repos/circuits/circuits/badge.png
   :target: https://coveralls.io/r/circuits/circuits
   :alt: Coverage
 
.. image:: https://landscape.io/github/circuits/circuits/master/landscape.png
   :target: https://landscape.io/github/circuits/circuits/master
   :alt: Quality
 
.. image:: https://badge.waffle.io/circuits/circuits.png?label=ready&title=Ready 
   :target: https://waffle.io/circuits/circuits
   :alt: Stories Ready

.. image:: https://requires.io/bitbucket/circuits/circuits/requirements.png?branch=default
   :target: https://requires.io/bitbucket/circuits/circuits/requirements?branch=default
   :alt: Requirements Status

circuits is a **Lightweight** **Event** driven and **Asynchronous**
**Application Framework** for the `Python Programming Language`_
with a strong **Component** Architecture.

circuits also includes a lightweight, high performance and scalable
HTTP/WSGI compliant web server as well as various I/O and Networking
components.

- Visit the `Project Website`_
- `Read the Docs`_
- Download it from the `Downloads Page`_
- `View the ChangeLog`_


Examples
--------

.. include:: examples/index.rst


Features
--------

- event driven
- concurrency support
- component architecture
- asynchronous I/O components
- no required external dependencies
- full featured web framework (circuits.web)
- coroutine based synchronization primitives


Requirements
------------

- circuits has no dependencies beyond the `Python Standard Library`_.


Supported Platforms
-------------------

- Linux, FreeBSD, Mac OS X, Windows
- Python 2.6, 2.7, 3.2, 3.3, 3.4
- pypy 2.0, 2.1, 2.2


Installation
------------

The simplest and recommended way to install circuits is with pip.
You may install the latest stable release from PyPI with pip::

    $ pip install circuits

If you do not have pip, you may use easy_install::

    $ easy_install circuits

Alternatively, you may download the source package from the
`PyPi Page`_ or the `Downloads Page`_ extract it and install using::

    $ python setup.py install


.. note::
    You can install the `development version
    <https://github.com/circuits/circuits/archive/master.zip#egg=circuits-dev>`_
    via ``pip install circuits==dev``.


License
-------

circuits is licensed under the `MIT License`_.


Feedback
--------

We welcome any questions or feedback about bugs and suggestions on how to
improve circuits.

Let us know what you think about circuits. `@pythoncircuits <http://twitter.com/pythoncircuits>`_.

Do you have suggestions for improvement? Then please `Create an Issue`_
with details of what you would like to see. I'll take a look at it and
work with you to either incorporate the idea or find a better solution.


Community
---------

There is also a small community of circuits enthusiasts that you may
find on the `#circuits IRC Channel`_ on the `FreeNode IRC Network`_
and the `Mailing List`_.
