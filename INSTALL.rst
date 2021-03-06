..
    This file is part of Python Client Library for STAC.
    Copyright (C) 2019 INPE.

    Web Land Trajectory Service is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.


Installation
============

``stac.py`` depends essentially on `Requests <https://requests.readthedocs.io/en/master/>`_. Please, read the instructions below in order to install ``stac.py``.


Production installation
-----------------------

Install from GitHub:

.. code-block:: shell

        $ pip3 install git+https://github.com/brazil-data-cube/stac.py@b-0.9.0


Development installation
------------------------

Clone the software repository:

.. code-block:: shell

        $ git clone https://github.com/brazil-data-cube/stac.py.git


Go to the source code folder:

.. code-block:: shell

        $ cd stac.py


Install in development mode:

.. code-block:: shell

        $ pip3 install -e .[all]


Run the tests:

.. code-block:: shell

        $ ./run-tests.sh


Generate the documentation:

.. code-block:: shell

        $ python setup.py build_sphinx


The above command will generate the documentation in HTML and it will place it under:

.. code-block:: shell

    doc/sphinx/_build/html/
