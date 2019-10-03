# SuitUpMechsContent

## Created By: Lightnet

## Information:
 This is "AS IS" content.
 
## Notes:
 * There are many licenses.
 
## Blender 2.80 to UE4

### Blender Settings

Scene
```
Units:
 Unit System: Metric
```

Character size should be scale up to 96 unit by default cube reference.

Armature object name should be rename that should not be "Armature" that will not enable to reimport animation correct to update new chagnes.

Export
```
Main
 * Apply Scalings: FBX ALL
 * Forward: -X Forward
 * Up: Z Up
 
 [x] Armature
 [x] Mesh

Deometries
 [x] Apply Modifiers
 Smoothing: Face
 [o] Lose Edge
 [x] Tangent Space

Armature
 [o] Only Deform Bones
 [o] Add Leaf Bones

 Primary Bone Axis: Y Axis
 Secondary Bone Axis: X Axis
 Armature FBXNode Type: Null

Animation
 [x] Back Animation
 [x] Key All Bones
 [x] NLA Strips
 [x] All Actions
 [x] Force Start/End Keying
  Sampling Rate: 1
  Simplify: 1
```

### Unreal Setting import
```
 Miscellaneous
 [0] Convert Scene 
```