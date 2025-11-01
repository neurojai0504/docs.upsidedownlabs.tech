.. _npg-lite-ninja:

NPG Lite - Ninja Pack
##################################

The Ninja Pack is designed for those who want a pre-assembled, ready-to-use setup.  
It comes with the VibZ Playmate for both haptic and auditory feedback, packaged in a custom 3D-printed case with battery included.  
This kit is perfect for users who want a smoother, plug-and-play experience without compromising flexibility or functionality.  

👉🏻 **Get yours on CrowdSupply**: `Neuro PlayGround Lite <https://www.crowdsupply.com/upside-down-labs/neuro-playground-lite>`__

.. figure:: ./media/npg-lite-ninja-box.*
    :align: center
    :alt: Neuro PlayGround Lite Ninja Pack
    
    Neuro PlayGround Lite Ninja Pack


Contents of the kit
********************

.. figure:: ./media/npg-lite-ninja-pack.*
    :align: center
    :alt: Kit Content Ninja Pack
    
    Kit Contents of NPG Lite Ninja Pack

+-------------------+-----+
| Kit Contents      | Qty |
+===================+=====+
| NPG Lite board    |  1  |
+-------------------+-----+
| VibZ Playmate     |  1  |
+-------------------+-----+
| Snap cables       |  7  |
+-------------------+-----+
| Alligator cables  |  5  |
+-------------------+-----+
| Gel electrodes    | 24  |
+-------------------+-----+
| LiPo battery      |  1  |
+-------------------+-----+
| Type-C cable      |  1  |
+-------------------+-----+
| 3D-printed case   |  1  |
+-------------------+-----+

VibZ Playmate
*******************

VibZ Playmate introduces a vibration motor for haptic feedback, a buzzer for auditory feedback, 
a QWIIC port for easy I2C sensor integration, an ON/OFF slide switch, 2.54 mm electrode header 
pins and common negative electrode option. With these Playmates, users can customize their setup 
for specific applications, whether in research, education, or interactive biofeedback experiments. 
This modular approach ensures flexibility, scalability, and better user experience.

Using the Kit
********************

This kit is beginner-friendly and you can easily start recording biopotential signals to create compelling 
HCI/BCI projects and explore the field of neuroscience. 
The VibZ Playmate easily connects to the NPG Lite board, providing simple haptic and auditory feedback and
expanding the system for interactive experiments without complex wiring.

Step 1: Skin Preparation
=========================

Apply Nuprep skin preparation Gel on the target areas where the
electrodes will be placed → rub in circular motion → clean with an alcohol swab or wet wipe.

For more information, please check out detailed step by step :ref:`Skin Preparation Guide <skin-preparation>`.

Step 2: Connect BioAmp Cables
===============================

Using VibZ you can record 3-channel biopotential signals, connect the jumper
wires according to the number of channels required:

.. figure:: ./media/npg-lite-vibz-back.*
    :align: center
    :width: 70%
    :alt: NPG Lite Vibz Back Side
    
    NPG Lite Vibz Back Side

+---------+---------+----------------------------+
| Channel | Pin     | Channel Connection         |
+=========+=========+============================+
|         | **A0P** | +ve of Channel 0           |
+Channel 0+---------+----------------------------+
|         | **A0N** | -ve of Channel 0           |
+---------+---------+----------------------------+
|         | **A1P** | +ve of Channel 1           |
+Channel 1+---------+----------------------------+
|         | **A1N** | -ve of Channel 1           |
+---------+---------+----------------------------+
|         |**A2P**  | +ve of Channel 2           |
+Channel 2+---------+----------------------------+
|         | **A2N** | -ve of Channel 2           |
+---------+---------+----------------------------+
|         | **REF** | Reference cable to REF     |
+---------+---------+----------------------------+
|         | **CN**  | Common Negative            |
+---------+---------+----------------------------+

Step 3: Place Gel Electrodes
===============================

Step 4: Upload Firmware
========================

Follow the quick steps below to upload the firmware to your NPG Lite device:

For detailed firmware upload guide, visit: :ref:`How to Flash Firmware on NPG Lite<npg-lite-flasher>`

- Power ON NPG Lite by flipping the on/off switch.
- Connect it to Laptop/PC via USB-C cable.
- Download the :ref:`NPG Lite Flasher<npg-lite-flasher>` and run the app.
- Select a firmware type, select your port, and flash it on your NPG Lite.
- For a WiFi or BLE connection, remove the USB-C cable and enable Bluetooth or Wi-Fi on your laptop based on Firmware uploaded.

Step 5: Visualizing the signals
================================

Follow the steps below to view real-time biopotential signal data from your NPG Lite device:

- Go to `Chords Web <https://chords.upsidedownlabs.tech/>`_
- Click on ``Visualize Now``, navigate to the ``NPG-Lite``, hit the ``Connect`` button and choose your device. 
- You can see the biopotential signals in real-time. 

For the detailed guide, visit: :ref:`Chords Web<chords>`

Explore features like play/pause data stream, apply filters,
increase channel count, enable features for recording and
downloading data in CSV format.