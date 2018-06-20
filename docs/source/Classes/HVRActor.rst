HVRActor
========

    HVRActor is the main object you will be interacting with from the 8i Unreal Plugin.

    A HVRActor can specify a data URI and be used to render HVR content.

How To Create
-------------

    1. Create a new HVRActor object by searching for it in the Classes window.
    2. See HVRAsset for details about how to assign data

Parameters
----------

	**Data URI**
        This parameter is a string and is the name of the folder within the projects 'HVR' folder this HVRActor should load.
        ie: If the parameter is set to 'tiger' the path to load will be: "PROJECT_ROOT/HVR/tiger/"

	**Play on Awake**
        Should this HVR begin playing as soon as it is created?

    **Loop**
        Should this HVR loop?

    **Render Method**
    	- FastCubes [Default]
    		- The recommended way for rendering content.
        - Point Sprite
            - Renders the actor with hard edges.
            - Renders faster than PointBlend
        - Point Blend
            - Renders the actor with smooth points which soften the look of the actor