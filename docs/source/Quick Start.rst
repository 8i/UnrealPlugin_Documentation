Quick Start
===========

Creating a HVRActor and rendering HVR data
------------------------------------------

1. Install the HVR plugin ( see Installation for steps )
2. Within the root folder of the project ( The same folder contains the PROJECT_NAME.uproject ) create a new folder called 'HVR'
3. Within the 'HVR' folder, create a new folder called 'example_data'. This is the name that will be used when creating an HVRAsset.
4. Copy all .hvrs files into the 'example_data' folder
5. Open your project
6. Create a new HVRActor by searching for it in the Classes panel and dragging it into the scene
7. Select the HVRActor
8. In the Details Panel, expand the HVRActor options, and then the HVRAsset options.
9. Type 'example_data' into the 'Data Name' slot of the HVRAsset and press enter

Creating a build
----------------

The HVR Plugin will automatically copy all data from the HVR directory when creating a build. This is done automatically

.. note::
    Currently ALL data within the HVR folder will be packaged with the build. Packaging relevant data when building will come in an update.