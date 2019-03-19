THETA Plug-in Development - Getting Started
###########################################

.. toctree::
   :maxdepth: 1
   :caption: Documents:


   examples/main
   examples/additional
   firstplugin/firstplugin
   streaming/tips
   

Overview
========

1. `Join the partner program <https://api.ricoh/products/theta-plugin/>`_ (it's free as of Mar 2019)
2. Enable THETA developer mode - Use RICOH desktop application on Mac or Windows
3. Download one of the code examples 
4. Open project in Android Studio and modify
5. Press Play to build project and install into THETA with a USB cable
6. If you hear a "beep-beep-beep" error sound, use `Vysor <https://www.vysor.io/>`_ to set application permissions


Testing Plug-in Untethered
--------------------------

To run the plug-in using the side "mode" button on the camera:

1. Set the default plug-in to launch using the Ricoh mobile app or the Ricoh desktop app
2. Put camera into plug-in mode by pressing the lower mode button for more than 2 seconds. 
   The LED above the shutter button will turn white.

API Choices
===========

Different APIs can be used to take pictures and video with RICOH THETA cameras:

* `Camera API <https://api.ricoh/docs/theta-plugin-reference/camera-api/>`_
* `Web API <https://api.ricoh/docs/theta-plugin-reference/web-api/>`_

You can also use the Web API through third-party libraries such as
`theta4j<https://community.theta360.guide/t/theta4j-minimal-plug-in-example-in-java/4184?u=codetricity>`.


Resources and Help
==================

If you have any questions, please direct them to the community link below.

* `Articles and Discussion <https://community.theta360.guide/c/theta-api-usage/plugin>`_ (Community)
* `Official API Documentation <https://api.ricoh/docs/theta-plugin/api/?utm_source=theta360guide>`_ (RICOH)
