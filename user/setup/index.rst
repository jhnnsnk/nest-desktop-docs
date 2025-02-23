===========
Setup Guide
===========

This guide provides a detailed documentation on how to install and start both instances: NEST Desktop and NEST
Simulator.

.. note::
   To enable the full functionality of NEST Desktop, you also need to install NEST Simulator on your computer. NEST
   Simulator provides an API Server which can forward requests to the simulation engine. In summary, you have to start
   NEST Server as well.

   You can find the detailed information on NEST Server in
   :doc:`NEST Simulator user documentation <nest-simulator:connect_nest/nest_server>`.

.. raw:: html
   :file: ./templates/setup.html

|br|

Docker (or Docker Compose) and Apptainer provide both NEST Desktop and NEST Simulator, so you have everything you need
to run NEST Desktop and NEST Simulator.

Alternatively, you can install NEST Desktop with the ``conda`` or ``pip`` command.

You are able to download and start the NEST Desktop application, e.g. AppImage (without NEST Simulator) or Snap (with
NEST Simulator) in Linux.

If you only have NEST Desktop (i.e., NEST Simulator is not running as back-end), you can create networks but cannot run
simulations within the application. In this case, you have to start NEST Server in a terminal or with Docker.

.. seeAlso::
   :doc:`NEST Server user documentation <nest-simulator:connect_nest/nest_server>`


|br|

.. _setup_docker-compose-linux-windows-apple:

.. include:: docker-compose.rst

|br|

.. _setup_apptainer-linux:

.. include:: apptainer.rst

|br|

.. _setup_conda-linux-windows-apple:

.. include:: conda.rst

|br|

.. _setup_python-linux-windows-apple:

.. include:: python.rst

|br|

.. _setup_appimage-linux:

.. include:: appimage.rst

|br|

.. _setup_snap-linux:

.. include:: snap.rst


.. |apple| image:: /_static/img/icons/apple.svg
   :alt: apple
   :target: #
   :width: 24px

.. |linux| image:: /_static/img/icons/linux.svg
   :alt: linux
   :target: #
   :width: 24px

.. |windows| image:: /_static/img/icons/windows.svg
   :alt: windows
   :target: #
   :width: 24px
