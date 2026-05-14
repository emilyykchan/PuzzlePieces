# Windows builds

Pre-built Windows builds are distributed through GitHub Releases rather than committed directly to the repository.

A typical Windows build should be provided as a `.zip` file containing the executable and its required Unity data/runtime files, for example:

```text
PuzzlePieces_Spanish_0420.exe
PuzzlePieces_Spanish_0420_Data/
UnityPlayer.dll
UnityCrashHandler32.exe
Mono/
```

Do not move the `.exe` away from its accompanying `_Data/` folder.

For Windows installation and Leap Motion usage instructions, see:

```text
docs/windows.md
```