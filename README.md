# L3V1 Recoil Suite(TM)

L3V1 Recoil Suite is a native Windows utility with built-in real-time AI operator emblem detection for Rainbow Six Siege.

## Creation Note

L3V1 Recoil Suite was made with AI assistance. I did not personally code the source by hand; I guided the project by giving prompts, testing the app, and choosing the features/changes.

## Features

- Native C++ Win32 application compiled directly into a fast executable (`L3v1Recoil.exe`)
- Automatic AI Operator Emblem Detection (scans in-game HUD and auto-switches operator profiles in real-time)
- Per-operator right-click edit modal to fine-tune X/Y pull values and sleep timing
- Option to disable secondary weapon recoil per operator
- Custom hotkeys and keybindings for Primary and Secondary weapon slots
- Transparent HUD overlay displaying active operator and status
- Standalone background AI engine (`operator_ai/detect.exe`) requiring no Python installation for end users

## Download & Setup

1. Download the latest release from the [Releases page](https://github.com/levifto1120/L3v1Recoil/releases/latest).
2. Extract the `L3V1_Recoil_Release.zip` archive.
3. Right-click `L3v1Recoil.exe` and select **Run as Administrator**.
4. Play in **Borderless Windowed** mode.
5. Press **`F8`** or **`'`** to toggle recoil reduction ON/OFF!
