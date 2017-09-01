##################
HVRAsset
##################

How To Create
-------------

When an HVRActor is created it will automatically created and be assigned an HVRAsset.

Parameters
----------

**Data Name**
    This parameter is a string and is the name of the folder within the projects 'HVR' folder this HVRAsset should load.
    ie: If the parameter is set to 'tiger' the path to load will be: "PROJECT_ROOT/HVR/tiger/"

**Play on Awake**
    Should this HVRAsset begin playing as soon as it is created?

**Loop**
    Should this HVRAsset loop?

Blueprint
---------

**Properties**

.. code-block:: c

    None Exposed

**Functions**

.. code-block:: c

    void    Play();
    void    Pause();
    void    Seek(float time);
    void    Step(int frames);
    void    ResetPlayback();
    void    SetLooping(bool looping);
    float   GetCurrentTime();
    float   GetDuration();
    bool    IsPlaying();
    bool    IsSeeking();
    bool    IsLooping();