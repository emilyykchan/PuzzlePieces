# Windows version

The Windows version of **Puzzle Pieces** supports contactless interaction using the **Leap Motion Controller**.

## Requirements

- Windows PC
- Leap Motion Controller
- Leap Motion Controller SDK/runtime
- Puzzle Pieces Windows build folder

## First-time Leap Motion setup

If you are using the Leap Motion Controller on the PC for the first time, install the Leap Motion Controller SDK/runtime before launching the game.

Download it from the official Leap Motion / Ultraleap developer website:

```text
https://developer.leapmotion.com/sdk-leap-motion-controller/
```

After installation, connect the Leap Motion Controller to the PC using USB.

## Launching the game

1. Unzip the Windows build folder, for example:

   ```text
   PuzzlePieces_Spanish_0420/
   ```

2. Open the `.exe` file inside the folder.

3. A Unity launch configuration window should appear.

4. Set the screen resolution to:

   ```text
   1280 × 800
   ```

5. Click **Play**.

6. Use the Leap Motion Controller to interact with the game.

## Interaction

Every page and button in the game is designed to support Leap Motion interaction.

The user should be able to interact with menus, levels, and record pages using hand gestures detected by the Leap Motion Controller.

## Typical Windows build contents

A Windows build folder may contain files such as:

```text
PuzzlePieces_Spanish_0420.exe
PuzzlePieces_Spanish_0420_Data/
UnityPlayer.dll
UnityCrashHandler32.exe
Mono/
```

Keep these files together in the same folder. The `.exe` depends on the accompanying data folder and Unity runtime files.

## Troubleshooting

If the Leap Motion Controller does not respond:

1. Check that the Leap Motion SDK/runtime is installed.
2. Check that the controller is connected by USB.
3. Restart the game after connecting the controller.
4. Keep the controller and the `_Data/` folder in the original build structure.

## Notes

- Do not move the `.exe` away from its accompanying `_Data/` folder.
- The recommended launch resolution is `1280 × 800`.
- The Android version uses touch input instead of Leap Motion interaction.
