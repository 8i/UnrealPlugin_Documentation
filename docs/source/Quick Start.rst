Quick Start
===========

Create a scene
------------------------------------------

    1. Install the HVR plugin ( see Installation for steps )
    2. Within the root folder of the project ( The same folder contains the PROJECT_NAME.uproject ) create a new folder called 'HVR'
    3. Within the 'HVR' folder, create a new folder called 'example_data'. This is the name that will be used when creating an HVRActor
    4. Copy all .hvr files into the 'example_data' folder
    5. Open your project
    6. Create a new HVRActor by searching for it in the Classes panel and dragging it into the scene
    7. Select the HVRActor
    8. In the Details Panel, expand the HVRActor options
    9. Type 'example_data' into the 'Data URI' slot of the HVRActor section and press enter

Create a build
----------------

There are no special steps when creating a build.

The HVR Plugin will automatically copy data from the HVR directory when creating a build. This is done automatically.

.. note::
    Currently all data within the HVR folder will be copied when creating a build. Packaging relevant data when building will come in an update.