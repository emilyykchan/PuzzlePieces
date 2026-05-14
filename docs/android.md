# Android version

The Android version of **Puzzle Pieces** uses touch-screen interaction.

Unlike the Windows version, the Android version does not use the Leap Motion Controller.

## Requirements

- Android tablet or Android device
- Puzzle Pieces `.apk` file
- Configuration files:
  - `NameList.json`
  - `Level.json`

Optional:

- Example user record file, such as `ExampleUser_01.json`

## Installing the app

1. Copy the `.apk` file to the Android device.
2. Install the `.apk`.

Depending on the Android device settings, you may need to allow installation from unknown sources.

## Adding configuration files

After installing the app for the first time, copy the required configuration files into the app data folder on the Android device.

Required files:

```text
NameList.json
Level.json
```

These files are provided in this repository as examples:

```text
docs/config/NameList.example.json
docs/config/Level.example.json
```

When preparing the Android app data folder, rename or copy them as:

```text
NameList.json
Level.json
```

## Android data folder

Connect the Android device to a computer and open the Android data directory.

Look for a path similar to:

```text
/Android/data/com.PuzzlePieces_Spanish/
```

The exact folder name may vary depending on the app package name. Look for the folder containing `PuzzlePieces_Spanish` or a similar project name.

Copy the following files into that folder:

```text
NameList.json
Level.json
```

## Optional example user record

The app saves individual player records as JSON files, usually named after the player:

```text
{name}.json
```

An example completed or partially completed user record can be copied into the same Android data folder to demonstrate the performance/record page.

Anonymised sample records are provided in:

```text
docs/config/sample-records/
```

For example:

```text
docs/config/sample-records/ExampleUser_01.json
```

If needed, copy one sample record into the Android data folder and rename it appropriately.

## Performance records

After a student completes a level, the game creates or updates a record file:

```text
{name}.json
```

This file stores the student's level progress and performance data.

If a player's JSON record file is deleted from the Android data folder, that player's record will no longer appear on the performance/record page.

## Interaction

The Android version is controlled by touching the screen.

This is the main difference from the Windows PC version, which supports contactless Leap Motion interaction.