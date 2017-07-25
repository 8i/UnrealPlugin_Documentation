HVRActor
========

HVRActor is the main object you will be interacting with from the 8i Unreal Plugin.

A HVRActor can be assigned a HVRAsset and used to render HVR content.

How To Create
-------------

1. Create a new HVRSound object by searching for it in the Classes window.
2. See HVRAsset for details about how to assign data

Parameters
----------

**HVRAsset**
    The HVRAsset object which this HVRActor is assigned.

**Render Method**
    - Point Sprite [ Default ]
        - Renders the actor with hard edges.
        - Renders faster than PointBlend
    - Point Blend
        - Renders the actor with smooth points which soften the look of the actor