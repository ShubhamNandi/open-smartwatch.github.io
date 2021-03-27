Open SmartWatch
===============

Logo Here 

Introduction
~~~~~~~~~~~~

This is a Open Source Smart Watch by Paul Smith

Media
~~~~~

Check this out a blog by `Hackster.io on Open
SmartWatch <https://www.hackster.io/news/there-s-something-especially-impressive-about-the-opensmartwatch-project-c2c878b983cf>`__

Join the Discussion
~~~~~~~~~~~~~~~~~~~

-  Discussion happens on Discord : `Paul 3D
   Things <https://discord.com/invite/9DK5JY6>`__
-  GitHub organisation :
   `Open-SmartWatch <https://github.com/Open-Smartwatch>`__

Light Edition Watch
~~~~~~~~~~~~~~~~~~~

-  `PCB Source File
   (KiCAD) <https://github.com/Open-Smartwatch/open-smartwatch-light>`__
-  `Order PCB <https://aisler.net/p/EBEIQYQD>`__ (Hint: AISLER sponsored
   the PCBs for prototyping this project, hence the logo on the PCB 😀 )
-  Here's the
   `BOM <https://htmlpreview.github.io/?https://github.com/Open-Smartwatch/open-smartwatch-light/blob/master/docs/bom/osw-light-ibom.html>`__
   for Light Edition Watch
-  All the `3D
   Files <https://github.com/Open-Smartwatch/3d-files/tree/master/case-light>`__

.. image:: assets/osw-light-top.svg 
   :width: 300
   :alt: Ligth Edition Top PCB
.. image:: assets/osw-light-bottom.svg 
   :width: 300
   :alt: Ligth Edition Bottom PCB
.. image:: assets/osw-light-schematic.svg 
   :width: 1000
   :alt: Ligth Edition Schematic PCB

GPS Edition
~~~~~~~~~~~

-  `PCB Source Files
   (KiCAD) <https://github.com/Open-Smartwatch/open-smartwatch-gps>`__
-  Here's the
   `BOM <https://htmlpreview.github.io/?https://github.com/Open-Smartwatch/open-smartwatch-gps/blob/master/docs/bom/osw-ibom_v.html>`__
   for GPS Edition Watch
-  All the `3D
   Files <https://github.com/Open-Smartwatch/3d-files/tree/master/case-gps>`__

.. image:: assets/osw-top.svg 
   :width: 300
   :alt: GPS Edition Top PCB
.. image:: assets/osw-bottom.svg 
   :width: 300
   :alt: GPS Edition Bottom PCB
.. image:: assets/osw-schematic.svg 
   :width: 10000
   :alt: GPS Edition Schematic PCB

Getting Started 
~~~~~~~~~~~~~~~~~

**Repositories:**

-  `Open-Smartwatch
   OS <https://github.com/Open-Smartwatch/open-smartwatch-os>`__, see
   README.md
-  `Open-Smartwatch
   Libraries <https://github.com/Open-Smartwatch/lib-open-smartwatch>`__,
   see README.md

**Code:**

Here is how to add the OS to VScode with PlatformIO `recommended YouTube
Tutorial <https://youtu.be/JmvMvIphMnY>`__

1. Clone this repository:

   git clone --recurse-submodules
   https://github.com/Open-Smartwatch/open-smartwatch-os.git

2. Open it with VSC:

   code open-smartwatch-os

  If you experience troubles with cloning the linked submodules on
  macOS, check that your VSC is in the applications folder and not in
  the downloads. Also, this might
  `help <https://stackoverflow.com/questions/29955500/code-not-working-in-command-line-for-visual-studio-code-on-osx-mac>`__

**Build:**

1. Use Visual Studio Code with the PlatformIO extension
2. Change the config.h.example file in ./include to suit your data, and
   change it to a header file (remove .example).
3. Select the correct PlatformIO Project environment
   (pico32\_GPS\_EDITION of pico32\_LIGHT\_EDITION)
4. For uploading, you need to hold the lower left button and then click
   the reset button (top left). It enables flash mode, the display
   should get dark. Orientation for the display: USB insert at the left
   side.
5. Press the reset button after uploading
6. App changer works by holding the lower left button to switch to your
   desired app.

The Big BOM
~~~~~~~~~~~

.. list-table:: The parts for the GPS Edition are a super set of the **Light Edition**, so the following list covers the **GPS Edition**
   :widths: 25 70 70
   :header-rows: 1

   * - Parts
     - Description
     - Aliexpress Link
   * - U7
     - TTGO T-MICRO32
     - https://www.aliexpress.com/item/32869180373.html
   * - U4
     - GC9A01
     - https://www.aliexpress.com/item/1005001382307998.html
   * - U8
     - Quectel L96-M33
     - https://www.aliexpress.com/item/32920337260.html  
   * - D1
     - LED 0805
     - https://www.aliexpress.com/item/32947001269.html
   * - U2
     - BMA400
     - https://www.aliexpress.com/item/4001043933700.html
   * - U6
     - CH340E
     - https://www.aliexpress.com/item/4000171821951.html  
   * - U1
     - DS3231MZ
     - https://www.aliexpress.com/item/32962505279.html
   * - U3
     - PSRAM
     - https://www.aliexpress.com/item/4000242457828.html
   * - U10,U13
     - XC6209F332MR-G
     - https://www.aliexpress.com/item/4000687517883.html
   * - U11
     - MCP73831T-2ACI/OT SOT23-5
     - https://www.aliexpress.com/item/32714249253.html
   * - U9
     - TPS2115APWR
     - https://www.aliexpress.com/item/32612393464.html
   * - U5
     - USB-Micro
     - https://www.aliexpress.com/item/32820570603.html
   * - SW1, SW2, SW4, SW5
     - Buttons
     - https://www.aliexpress.com/item/32870278366.html
   * - XS1
     - uSD Slot
     - https://www.aliexpress.com/item/1005001470093106.html
   * - Q1
     - 2N7002
     - https://www.aliexpress.com/item/32912312094.html            
   * - R1-RN
     - 0603 SMD R
     - https://www.aliexpress.com/item/32298348854.html
   * - C5,C6
     - 1206 SMD C
     - https://www.aliexpress.com/item/32956133014.html 
   * - C1-CN  
     - 0603 SMD C
     - https://www.aliexpress.com/item/32841971485.html