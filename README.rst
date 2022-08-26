tesla_dashcam for mac
=====================

Python program that provides an easy method to merge saved Tesla Dashcam footage into a single video.

Customized for Mac, especially for ARM Mac. Trascoding is much faster than a normal PC.


Requirements
-------------


Download a MacOS binary for ffmpeg from: https://www.osxexperts.net and use --ffmpeg. Or use brew install ffmpeg.

Then pip3 install all the requirements. You must have python3.8.6+.

Then download tesla_dashcam.py.


Example
-------

.. code:: bash

    python3 tesla_dashcam.py --layout WIDESCREEN --motion_only --gpu --encoding x265 --rear --output ~/Movies/TeslaDashCAM --quality MEDIUM --compression veryslow --fps 30 --no-check_for_update

Or like:

.. code:: bash

    python3 tesla_dashcam.py --layout WIDESCREEN --motion_only --rear --output ~/Movies/TeslaDashCAM --quality MEDIUM --compression veryslow --fps 30 --no-check_for_update --enc hevc_videotoolbox --ffmpeg ~/Applications/Bin/ffmpeg


More Usage
----------

See to ehendrix23/tesla_dashcam.
