# Rec Room Legacy Optimizer

A small MelonLoader mod made to improve the performance of the September 1st, 2021 version of Rec Room.

This project focuses on making the older client run a little better, especially on lower-end hardware. The idea is to clean up unnecessary overhead, improve resource usage, and make the overall experience smoother without changing what makes the original client feel like Rec Room.

## What does it do?

The optimizer is designed to improve different parts of the client, including:

- Reducing unnecessary CPU usage.
- Improving memory management.
- Cutting down on avoidable background processing.
- Improving garbage collection behavior where possible.
- Looking for performance bottlenecks in the original client.
- Keeping the original gameplay and visuals intact.

The goal isn't to completely remake or change the client. It's simply to make the existing September 2021 version run better.

## Requirements

- September 1st, 2021 Rec Room client.
- MelonLoader.
- Windows.
- A compatible version of the .NET runtime, if required by the selected MelonLoader version.

## Installation

1. Make sure MelonLoader is installed in your Rec Room directory.
2. Download the latest DLL release.
3. Open your Rec Room installation folder.
4. Find the `Mods` folder.
5. Place the optimizer DLL inside it.
6. Launch the game.

MelonLoader should automatically detect and load the mod.

## Compatibility

This mod is specifically made for the September 1st, 2021 Rec Room client.

It hasn't been designed with newer Rec Room versions in mind, so using it with other releases may cause problems or prevent it from working entirely.

Compatibility with other MelonLoader mods may vary.

## Development

This project is still being worked on. Performance improvements are tested against the target client, and new optimizations may be added as more bottlenecks are discovered.

Not every optimization will make a noticeable difference on every computer. Results depend on your hardware and the condition of your game installation.

## Reporting Issues

If something isn't working, feel free to open an issue.

Try to include:
- Your Rec Room client version.
- Your MelonLoader version.
- Your PC specifications.
- Any relevant MelonLoader logs.
- A description of what happened.

This makes it much easier to figure out what's going wrong.

## Credits

- MelonLoader team for the mod-loading framework.
- Rec Room for the original game.
- Everyone helping test, report issues, and improve the project.

---

This is an unofficial community project and is not affiliated with Rec Room Inc.

**Made for the September 2021 Rec Room client.**
