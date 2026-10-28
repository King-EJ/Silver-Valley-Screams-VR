# Silver-Valley-Screams-VR
VR Mod for Silver Valley Screams

<img width="683" height="1024" alt="libraryule_2x" src="https://github.com/user-attachments/assets/878f1971-87ca-4268-9b87-2ee3b5aaa85f" />


SILVER VALLEY SCREAMS VR  -  VR mod (Unity 2019.4.18, IL2CPP x64, URP, BepInEx 6 be.788)
=========================================================================================
Version 0.3.0 (test build)

INSTALL
  1.unzip to game folder, only tested with virtual desktop XR,
      to disable Mod rename winhttp.dll to winhttp.dll.bak
  2. Start your OpenXR runtime first (Virtual Desktop / SteamVR / Quest Link), then the game.

CONTROLS (the VR controllers act as keyboard + mouse - see SilverValley_VR_Controller_Layout.png)

  <img width="1920" height="1080" alt="SilverValley_VR_Controller_Layout" src="https://github.com/user-attachments/assets/6e127b47-d4f5-4267-a2ea-ce4fa569f1da" />


INTERACTING
  * The game's own camera follows your right controller in play (your eyes stay at the player's head), so the
    game's interaction ray, crosshair and weapons come from your hand. Things the game attaches to its camera
    (held flashlight / weapon) may follow your hand too.
  * Point at things with your RIGHT controller (a thin laser with a dot shows where) and press X (E) - you interact
    with what the controller points at, not the middle of your view.
  * The game's interaction words ("Door", "Take"...) float by your right controller; the crosshair in the middle of
    the HUD is hidden while you point.
  * Settings [Interact]: PointWithRightController, Laser, WordsByRightHand, WordsOffset, WordsHeight,
    HideCrosshairWhenPointing.

VIEW
  * Play: first person, your head looks around and turns the player, so walking goes where you look. The right
    stick turns you. The HUD floats in front of you (its black parts see-through).
  * Menus / anything with a mouse cursor: the game's picture on a screen in front of you; point the laser from your
    right controller at it and press the right trigger to click.
  * Cut-scenes / moments where the game locks the camera: you see from the game camera; your view turns with it
    when the shot changes.
  * Tip: switch off head bob and camera shake in the game's settings - much more comfortable in VR.
  * Headset picture upside down: FlipEyes in the config. Menus upside down / laser pointing wrong up-down:
    ScreenPictureFlip / ScreenGeometryFlip.




