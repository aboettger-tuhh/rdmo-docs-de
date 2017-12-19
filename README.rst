RDMO - Research Data Management Organiser
=========================================

RDMO is a tool to support the systematic planning, organisation and implementation of the data management throughout the course of a research project. RDMO is funded by the Deutsche Forschungsgemeinschaft (DFG).

German documention
------------------

Setup
~~~~~

First install `sphinx`, `sphinx-autobuild`, and `sphinx_rtd_theme`:

.. code:: bash

    pip install -r requirements.txt

Then, the HTML files can be created using:

.. code:: bash

    make html

A live server, which auto-updates itself after a file is saved, can be started using:

.. code:: bash

    make live

The documentation is then available on http://localhost:8000.
