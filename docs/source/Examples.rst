##################
Examples
##################

**********************************************
Simple Setup
**********************************************

**Example Map:** Simple
    
A simple setup showing multiple actors HVRActors in a scene


**********************************************
Using HVRSound to sync Audio
**********************************************

**Example Map:** HVRSound
    
Shows how the HVRSound class can be used to sync audio to a performance


**********************************************
Creating HVRActor Blueprints
**********************************************

- **Useful Unreal Documentation links**
    - `Blueprints`_

**Example Map*** Blueprint

A simple example which shows how blueprint can be used to call functions on HVRActor and HVRAsset

The Blueprint 'HVRActor_BP_PlayOnAwake' is a simple set up which sets the HVRAsset to loop and then begin playing.


**********************************************
Using HVRActors within Sequencer
**********************************************

- **Useful Unreal Documentation links**
    - `Blueprints`_
    - `Sequencer`_
    - `Level Blueprint`_
    - `Custom Events`_

**Example Map:** Sequencer
    
Demonstrates how a HVRActor blueprint can be used within a Sequence

In this example the 'Example Sequence' has an Event Track which causes the HVRActor in the scene to Play and Seek.
The Events that are triggered by the Sequence are picked up within the Level Blueprint's Custom Events. These Custom Events calls functions on the 'HVRActor_BP'.

The Blueprint 'HVRActor_BP' demonstrates a complex Blueprint set up where many controls are exposed and includes a check to ensure that playback is in sync.

.. note::
    When creating Events within Sequencer it is very important that the 'Event Name' matches the 'Custom Event' name in your Level Blueprint. If it does not, the event will not be picked up.





.. _Blueprints: https://docs.unrealengine.com/latest/INT/Engine/Blueprints/
.. _Sequencer: https://docs.unrealengine.com/latest/INT/Engine/Sequencer/Overview/
.. _Level Blueprint: https://docs.unrealengine.com/latest/INT/Engine/Blueprints/UserGuide/Types/LevelBlueprint/
.. _Custom Events: https://docs.unrealengine.com/latest/INT/Engine/Blueprints/UserGuide/Events/Custom/
