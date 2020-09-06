# VRKoumeiTool

This mod is one improving existing Vrboop.dll, which makes grabbing and touching breasts enabled on VR.

## [Installation]
1. Extract the zip file into User's HoneySelect directory.
2. Run your Game execution file with "--vr" optino. 
3. Enjoy new functions on VR!

**Caution!** 
- This mod might rewrite some existing files and cause some bugs depending on User's environment.
  Please back up Game root folder before installing necessarily.
- If you using other VR tools as of now except for here, your game might work unproperly. Then reconsider removing other VR tools (${GameFolder}/Plugins/*.dll files etc.).  

## [Requirements]
- Game updated with the last patch and DLC installed.
- Installed and set up SteamVR.
- public HoneySelect VRmod (by Eusth) or improved HoneySelect VRmod (one with IBL&LRE made by arthurOmanko). 

## [Mod Settings]
- Setting:      
  -- ${GameFolder}\Plugins\VRKouemiTool\VRKoumeiToolConfig.xml   --- settings for VRKoumeiTool.dll  

## Modes & Controls

## Tools

These tools are mainly meant to be used in *standing mode* but some of them are also available in *seated mode*. In order to use added new function, press the *menu button* on your VR controller. [See here an overview of buttons](https://forums.unrealengine.com/attachment.php?attachmentid=87367&d=1460020388).

**You can get in-game help any time by holding the menu button!**

### KoumeiTool (seated / standing)
![preview](https://user-images.githubusercontent.com/68005887/92324350-d72e4980-f07b-11ea-9ac0-073b22da5fe8.png)

#### UI/UX abstract on KoumeiTool
Tag      |  Move   | 
----     | ------  | 
only one hand needed
<kbd>menu</kbd>+<kbd>holding</kbd> | display function of each button
<kbd>trigger</kbd>+<kbd>doubleClicks</kbd> | Koumei Wind (generates wind)
<kbd>trigger</kbd>+<kbd>holding + moving</kbd> | Koumei Strip (strips cloth of female in front of you)
<kbd>grip</kbd>+<kbd>doubleClicks</kbd> | Koumei Gaze1 (along your sight, chara changes clothes)
<kbd>grip</kbd>+<kbd>holding + moving</kbd> | Koumei Grab/Touch (grabs and touches breasts, hips, hairs, skirts or items with DynamicBones)
<kbd>trackpad</kbd>+<kbd>doubleClicks</kbd> | Koumei Gaze1 (along your sight, chara changes accessories)
<kbd>trackpad</kbd>+<kbd>holding + moving</kbd> | Koumei Move (move + rotate)

### ChageLightColorTool (Standing / Seated)
![lightColor](https://user-images.githubusercontent.com/68005887/92324643-a996cf80-f07e-11ea-9c67-c6039d60e73d.png)

#### UI/UX abstract on ChangeLightColor
Tag      |  Move   | 
----     | ------  | 
only one hand needed
<kbd>trackpad</kbd>+<kbd>holding + moving</kbd> | Change colors of front directional light
<kbd>trigger holding</kbd>+<kbd>trackpad</kbd>+<kbd>holding + moving</kbd> | Change colors of back directional light
<kbd>menu</kbd>+<kbd>holding</kbd> | display each fuction

## Settings & Tweaks

Settings can be changed in the file *VRKoumeiToolConfig.xml*, which is generated the first time you start the game.  
Tag      | Default | Effect | Mode
----     | ------  | ------ | ----
`<Distance>` | 0.1 | Sets the distance between the camera and the GUI at `[0,0,0]`. | Seated
`<Angle>` | 170 | Sets the width of the arc the GUI takes up.  | Seated
`<IPDScale>` | 0.83 | Sets the scale of the camera. The higher, the more gigantic the player is. | Seated / Standing
`<OffsetY>` | 0 | Sets the vertical offset of the GUI in meters. | Seated
`<Rotation>` | 0 | Sets by how many degrees the GUI is rotated (around the y / up axis) | Seated
`<Rumble>` | True | Sets whether or not rumble is activated. | Seated / Standing
`<RenderScale>` | 1 | Sets the render scale of the renderer. Increase for better quality but less performance, decrease for more performance but poor quality. | Seated / Standing
`<MirrorScreen>` | False | Sets whether or not the view should be mirrored in the game window. | Seated / Standing
`<ApplyShaders>` | true | Sets whether or not post-processing shaders should automatically be applied to the camera. | Seated / Standing
`<NearClip>` | 0.01 | Within this distance, seen chara gets transparent. | Seated / Standing
`<PitchLock>` | false | Whether or not can rotate on all axises (unlocked = false) | Seated
`<Projection>` | flat | The appearance of GUI seen | Seated
`<SpeechRecognition>` | false | Whether or not speech recognition is enabled. | Seated / Standing
`<RotationMultiplier>` | 2.5 | Accelaration of rotation | Seated / Standing
`<Leap>` | true | Whether or not Leap Motion support is activated. | Standing 
`<GrabRotationImmediateMode>` | true | Determines the rotation mode. If enabled, pulling the trigger while grabbing will immediately rotate you. When disabled, doing the same thing will let you 'drag' the view. | Standing
 `<DefaultDistanceOfLeap>` | 0.5 | Default distance up to chara on leaping. | Standing
 `<SpeedOfMouseWheel>` | 3 | speed of mouse wheel on PlayTool | Seated / Standing
