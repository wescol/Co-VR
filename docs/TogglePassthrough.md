# TogglePassthrough

This script allows for turning the passthrough layer on and off. It is intended to be attached to the `Passthrough Toggle` prefab.

## Properties

### XRRig
*public GameObject XRRig*
<br>The rig required for VR interaction with wall drawing and passthrough.

### mainCamera
*public Camera mainCamera*
<br>The main camera of the scene.

<br>

## Methods

### Toggle
*public void Toggle()*
<br>Toggle passthrough on and off based on whether or not passthrough is currently enabled in the `XRRig`.

### SetPassthrough
*public void SetPassthrough(bool isOn)*<br>
Turn passthrough layer on or off.
- **isOn**: *bool* - Whether to turn passthrough on or off 
