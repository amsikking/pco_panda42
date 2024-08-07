# pco_panda42
Python device adaptor: PCO.panda 4.2 USB sCMOS camera.
## Quick start:
- Install the PCO USB interface driver, then install 'Camware' to test the camera and get the latest
 "SC2_Cam.dll" (a version included here). Put the .dll in the directory with "pco_panda42.py" and run
 the script (requires Python and numpy).

![social_preview](https://github.com/amsikking/pco_panda42/blob/main/social_preview.png)

## Details:
- The adaptor reveals a minimal API from the extensive PCO SDK by following the 'typical implementation'
for a series of .dll calls for camera setup, image acquisition and tidy up.
- See the '\_\_main__' block at the bottom of "pco_panda42.py" for some typical ways to interact with a
stand alone camera or "pco_panda42_external_trigger_example.py" for an example of high speed external
triggering (a very useful mode for ultra fast synchronization in a multi-device/microscope system).
