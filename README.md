# Trade With Another World

Trade With Another World is a Valheim mod. Explore the Black Abbey and trade what you recover with the Weathered Wayfarer.

## Private playtest

Get the single-DLL install from the [v1.0.4 playtest release](https://github.com/octerockman/TradeWithAnotherWorld/releases/tag/v1.0.4). The ZIP includes `PLAYTEST.txt` with installation and testing instructions.

## Source

[`TradeWithAnotherWorld-v1.0.4-source.zip`](./TradeWithAnotherWorld-v1.0.4-source.zip) contains the C# sources used for the playtest and the compiler project. Extract it to a working folder before opening the project. A full rebuild requires the original project resource inputs, the bundled payload index, and local copies of the Valheim 1.0.21, BepInExPack 5.4.2333, and Jotunn 2.30.2 reference assemblies. The project lists the expected resource paths. Set `ValheimPath`, `BepInExCorePath`, and `JotunnPath` to the game directory, BepInEx core directory, and Jotunn DLL respectively.

The archive includes code and the build definition. Art, motion, audio, and third-party binaries are supplied separately from authorized local inputs.
