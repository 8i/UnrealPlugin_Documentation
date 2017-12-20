HVRSound
========

    Allows you to keep audio in sync with an HVRAsset's playback.

How To Create
-------------

    1. Create a new HVRSound object
    2. In the Details panel, expand the 'HVRSound' section
    3. Set the 'HVR Actor' parameter to target the HVRActor which the audio should sync to
    4. Once the scene is playing, this audio will sync automatically.

Parameters
----------

    **HVR Actor**
        The HVRActor this component will sync audio to.

    .. note::
        There is a known issue where large jumps ( > 2 seconds ) in time in the HVRActor's HVRAsset time can cause the audio to go out of sync.