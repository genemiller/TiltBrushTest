# AR-AlphaTest

Unity Project containing three of Darcy Gerbarg’s artworks for the AR Installation Alpha Test.
- Initial release 6/15/2021
- Gene Miller

The artworks are named:
1.	Violet Brush (animated framed painting)
2.	Party (animated framed painting)
3.	TL15_11 (3D Painting)

## Assumptions and questions

- Assumption 1. Darcy Gerbarg and the Alpha Test team will decide locations, orientations, and scales for each of the three artworks.
  - Each artwork is currently prepared with bottoms near ground level, and tops about double the height of a person (e.g. 3 to 4 meters)

- Assumption 2. The Alpha Test team will be using a Game Engine (such as Unity3D.)
  - NOTE: The models are currently packaged as a Unity3D Project – Version  2019.4.
  - Does Alpha Test team prefer a different Game Engine? (e.g. Unreal)

- Assumption 3. The Alpha Test team will be using an AR SDK (such as Google ARCore)
  - NOTE: An AR SDK has NOT yet been integrated with the Unity3D Project 
  - Does the Alpha Test team plan to integrate the AR SDK?
  - Or should Gene Miller integrate the AR SDK? (which one?)


## Asset folders and files

#### Scenes: (scenes for each of three artworks)
- VioletBrush.unity
    - VioletBrush is enabled, other two objects are disabled
- Party.unity
    - Party object is enabled, other two objects are disabled
- TL15.unity
    - TL15 object is enabled, other two objects are disabled

#### Texture: (textures for two paintings)
- Violet Brush-Brighter 32x18 75dpi.jpg
- DG-Party+TL220180509-181050D1C2 54x54 75dpi 2018.jpg
- Darcy Gerbarg 2021 sig.png

#### Materials: (materials for two paintings)
- VioletBright.mat
- DG-Party.mat
- DG-Wood-Frame.mat
- Signature-Black.mat
- Signature-White.mat

#### Animation:   (animation for two paintings)
- Pivot.controller
- PivotCamera.anim

#### Ciconia Studio Shaders: (Double-sided emissive shader for two paintings)
- Double Sided Emissive Diffuse.shader

#### TL15_11.glb (3D Painting artwork; materials and textures included in GLB file)

#### TiltBrush: (Tiltbrush shaders required for TL15_11.glb)

#### ThirdParty: (Required for TiltBrush)


## Operational Steps (based on Assumptions listed above)
1. Download this GitHub repository (https://github.com/genemiller/AR-AlphaTest)

2.  Open the Unity Project AR-AlphaTest (Note: this Project was tested with Unity Version 2019.4.2f1)

3. Integrate with AR toolkit (E.g. Google AR-Core)

4. For each of the three scenes:
        1. VioletBrush
        2. Party
        3. TL15
   1. Load the scene
   2. Unload the other two scenes
   3. Build for target platform(s) (e.g. Android)
   4. Deploy the build file(s) (e.g., APK) to target platform (e.g. Android)

5. Review the results (consult with Gene Miller if there are bugs)

6. Provide build files (or AR Package integration) to Darcy Gerbarg and Gene Miller (who will also review the results)

8. Discuss possible changes, e.g.,
   - Scale, height, orientation
   - Timing and degree of animation
   - Whether colors and shading look right
