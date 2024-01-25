# ExportTilesetDefinitionNetCore

This is a ".Net Core" version of [LDtkTilesetExporter](https://github.com/Cammin/LDtkTilesetExporter).

It is intended to be used for people using Unity for Linux.

To make it work :
- get a build version in [here] ;
- do not install the Windows version as described [here](https://cammin.github.io/LDtkToUnity/documentation/Installation/topic_StartupGuide.html#2-install-the-export-app)
- unzip it in you `/Library` folder in your Unity project
- add a custom command for LDtk like described [here](https://cammin.github.io/LDtkToUnity/documentation/Installation/topic_StartupGuide.html#3-add-a-custom-command)
  - and put this command : `../../Library/ExportTilesetDefinitionNetCore/ExportTilesetDefinitionNetCore "<NAME OF YOUR PROJECT>"`
