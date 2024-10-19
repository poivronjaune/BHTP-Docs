.. BHTP documentation master file, created by
   sphinx-quickstart on Thu Oct 17 18:04:39 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

BHTP documentation
===================

**B**\rothers **H**\obby **T**\rading **P**\latform is a python package to help hobbyist implement trading strategies for fun.

Installation
^^^^^^^^^^^^^

::

   pip install git+https://github.com/poivronjaune/BHTP-Tools.git

.. note::
   If running in `Google Colab`_ use  

   ::

   !pip install git+https://github.com/poivronjaune/BHTP-Tools.git

.. _Google Colab: https://colab.research.google.com/

Usage 
^^^^^^

::

   import bhtp

   print(bhtp.version)
   print(bhtp.get_version())



.. toctree::
   :maxdepth: 2
   :caption: Contents:

.. automodule::bhtp.github
   :members: