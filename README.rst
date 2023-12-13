==============
MetaCovasim
==============

MetaCovasim was developed by the `Research Institute of Systems Biology and Medicine`_

.. _Research Institute of Systems Biology and Medicine: https://sysbiomed.ru/

.. contents:: **Contents**
   :local:
   :depth: 2

Modification
======
1) Microbiota parameters, that increase probability to be severe
2) Cumulative formula of infection
3) New plots and design in web-version
4) Multicities module

Requirements
============

Python >=3.6 (64-bit). (Note: Python 2 is not supported.)

We also recommend, but do not require, using Python virtual environments. For
more information, see documentation for venv_ or Anaconda_.

.. _venv: https://docs.python.org/3/tutorial/venv.html
.. _Anaconda: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html


Quick start guide
==================

1.  Clone a copy of this repository:

.. code-block:: shell

    git clone https://github.com/InstituteforDiseaseModeling/covasim_webapp

2.  Navigate to the root of the repository and install the Covasim Webapp Python package:

.. code-block:: shell

    python setup.py develop

3. Change to package folder and run the application via Flask:

.. code-block:: shell

    cd covasim_webapp
    python cova_app.py

4. Go to ``localhost:8188`` in your browser to view the webapp.

See the `webapp README`_ for more information.

.. _webapp README: ./covasim_webapp


Docker
======

This folder contains the ``Dockerfile`` and other files that allow Covasim to be run as a webapp via Docker. See the `Docker README`_ for more information.

.. _Docker README: ./docker


Disclaimer
==========

Based on Covasim_

.. _Covasim: https://github.com/InstituteforDiseaseModeling/covasim
