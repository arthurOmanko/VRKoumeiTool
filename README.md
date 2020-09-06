# VRKoumeiTool

This mod is one improving existing Vrboop.dll, which makes grabbing and touching breasts enabled.

## [Installation]
1. Extract the zip file into User's HoneySelect directory.
2. Run (HoneySelect|StudioNEO)_(64|32)_for_VR_with_IBL
3. Enjoy super high quality on VR!

**Caution!** 
- This mod might rewrite some existing files and cause some bugs depending on User's environment.
  Please back up Game root folder before installing necessarily.
- If you using other VR tools as of now except for here, your game might work unproperly. Then reconsider removing other VR tools (${GameFolder}/Plugins/*.dll files etc.).  

## [Requirements]
- Game updated with the last patch and DLC installed.
- Installed and set up SteamVR.
- public VRmod (by Eurth) or improved VRmod (one with IBL&LRE made by arthurOmanko). 

## [Mod Settings]
- Setting:      
  -- ${GameFolder}\Plugins\VRKouemiTool\VRKoumeiToolConfig.xml   --- settings for VRKoumeiTool.dll  

## Modes & Controls

## Tools

These tools are mainly meant to be used in *standing mode* but some of them are also available in *seated mode*. By default, your left hand will start with the *menu tool* and your right hand will start with the *warp tool*. In order to change them on either hand, press the *menu button* on your Vive controller. [See here an overview of buttons](https://forums.unrealengine.com/attachment.php?attachmentid=87367&d=1460020388).

**You can get in-game help any time by holding the menu button!**

### Menu Tool (seated / standing)
![preview](https://user-images.githubusercontent.com/68005887/92324350-d72e4980-f07b-11ea-9ac0-073b22da5fe8.png)

With the *menu tool* you can interact with the user interface of the game. There are, in fact, two ways you can control the mouse: a two-handed way that makes use of a laser pointer, and a one-handed way that lets you use your trackpad like a ... touchpad!

#### Laser pointer
![laser_pointer](https://user-images.githubusercontent.com/68005887/89115930-0f64ca00-d4c9-11ea-84d9-7c39582e845a.jpg)  

To use the laser pointer, simply point the *other controller* at the menu screen. A laser pointer will appear and you can easily interact with the UI. To make a click, press the trigger button.

#### Trackpad

To use the trackpad, slide with your thumb over the trackpad and the mouse cursor will move accordingly. To make a click, press the trackpad.

#### Attaching, Detaching and Resizing the Menu
![scale](https://user-images.githubusercontent.com/68005887/89115937-20154000-d4c9-11ea-96f9-975ffb9da280.jpg)  


It's possible to detach and resize the menu you're holding at any point in the game.

Simply press the grip button to "let go" of the menu screen -- the screen will then stay put where you left it. You can even use other tools and still interact with the screen using the *laser pointer* mechanism.

Furthermore, it's possible to *resize* the screen. In order to do that, point both your controllers at a screen, press the trigger button, and move the controllers apart. It's also possible to move the screen around like this.

Lastly, to take control of the screen again, press the grip button once more.

#### UI/UX abstract on Menu
Tag      |  Move   | 
----     | ------  | 
only one hand needed
<kbd>trackpad</kbd>+<kbd>move</kbd> | move mouse cursor
<kbd>trigger</kbd> | click mouse cursor
<kbd>menu</kbd> | display menu
<kbd>grip</kbd> | put GUI or grab put GUI
both hands needed
<kbd>trigger</kbd>+<kbd>trigger</kbd> | resize put GUI.

### Warp Tool (standing)
![warp_tool](https://user-images.githubusercontent.com/68005887/89115946-358a6a00-d4c9-11ea-87b0-ba7e6088070a.png)  

The *warp tool* is only available in room scale mode and allows you to jump around in the scene.

#### Warping

In order to warp, touch the trackpad, choose your position and press. While touching the trackpad you are able to see:

1. Where you will warp to
2. Your play area
3. A HMD that further shows where your head will be

You can also *rotate* your play area while touching the trackpad by drawing circles with your thumb.

![warp](https://user-images.githubusercontent.com/68005887/89115953-49ce6700-d4c9-11ea-811b-39a77fc49fe3.jpg)  

#### Changing Scale and Height

It's also possible to change scale and height with this tool, although it's a bit cumbersome at the moment. To do this, hold the trackpad *pressed* before warping. You can now change your future height by moving the Vive controller up and down and your scale by moving back and forth. Note that you can only change one of those two each time.

By pressing the *grip button* you can reset the scale and height.

#### UI/UX abstract on Warp
By improved UI/UX and leap functions, User can easily move where User want.  
Tag      |  Move   | 
----     | ------  | 
only one hand needed
<kbd>menu</kbd>+<kbd>trigger</kbd> | warp in front of chara along User's line of sight
<kbd>tigger</kbd>+<kbd>1 second</kbd> | impersonate chara along User's line of sight
<kbd>grip</kbd>+<kbd>trackpad</kbd> | rotate around y-axis (normal)
<kbd>grip</kbd>+<kbd>trigger</kbd> | rotata around y-axis 
<kbd>trackpad</kbd> | warp where User wants
<kbd>grip</kbd>+<kbd>move</kbd> | move where User wants
<kbd>menu</kbd>+<kbd>holding</kbd> | menu on warp mode
both hands needed
<kbd>Grip</kbd>+<kbd>Grip</kbd> | rotate around y-axis (normal)
<kbd>Grip</kbd>+<kbd>Menu</kbd> | rotate around x-axis (added)
<kbd>Grip</kbd>+<kbd>trigger</kbd> | rotate around z-axis (added)
<kbd>Menu</kbd>+<kbd>UpArrow</kbd>+<kbd>trigger</kbd> <br /> <kbd>Menu</kbd>+<kbd>DownArrow</kbd>+<kbd>trigger</kbd> | decrease/increase the distance up to chara on leaping.

### Play Tool (Standing / Seated)
![play_tool](https://user-images.githubusercontent.com/68005887/89115805-5ce03780-d4c7-11ea-811d-c2b4ceb54b09.png)  
The play tool is used to interact with the scene.  
#### UI/UX abstract on PlayTool
Tag      |  Move   | 
----     | ------  | 
only one hand needed
<kbd>trigger</kbd>+<kbd>DoubleClicks</kbd> | FinishIn or Drink
<kbd>grip</kbd>+<kbd>DoubleClicks</kbd> | Both Gone or Vomit
<kbd>trackpad</kbd>+<kbd>DoubleClicks</kbd> | FinishOut
<kbd>trackpad</kbd>+<kbd>trigger</kbd> | I'm coming!
<kbd>trackpad</kbd>+<kbd>slide along y-axis</kbd> | Change piston speed, Go In/Out, etc.
<kbd>menu</kbd> | display each fuction

## Settings & Tweaks

Settings can be changed in the file *vr_settings_for_IBL.xml*, which is generated the first time you start the game. Use `RenderScale` to tweak the resolution, **not** the internal resolution dialog, as that one will currently only change the resolution of the GUI.

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
