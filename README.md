# Ballance Mod Loader Mods

The project served for my BML mods.

**There is no any update or bug fix for this project in the future. I feel desperate to Ballance and its community. My dedication and love to Ballance seems to be totally vain. It's time to terminate this project. The last supported BMLPlus version is 0.2.3 and no support to BML. Good luck to you and your Ballance career.**

## Introduction

### BallanceOptiFine
 
See [project readme](./BallanceOptiFine/README.md)

### BaseCmoCfg

Allow you change 2 settings located in `base.cmo`, God Mode and Debug Mode. Change settings in mod configuration file and restart game to apply them. If you find some game font changed when enabling some settings, calm down. It's just normal.

### Coredump

**This mod is deprecated and not included in Visual Studio solution file.**

Dump current game scene as a Virtools compisition file via commandline. Type `/help` to get this mod's command.

### FontCraft

Allow you change Ballance default font. Input font name and style in mod configuration page and restart game to apply it. This mod rely on GDI+ function and will draw a special image in memeory for font initialization when staring game. So if your game stuck 1-2 seconds in starting, please calm down. This is normal phenomenon and usually happeded on some computer with low quality hardware component.

### ExtraSector

Yet another 999 sector loader. (Named Extra_Sector in old BML)

### BLinguist

Multi-language support for Ballance. The improvement version of 2jjy & jxpxxzj Chinese version Ballance. Not only Chinese.

### BallanceBBOR

Ballance Bounding Box Outline Reloaded. Operate like the Minecraft mod with same name, but show the depth cubes, transformer sphere, ventilator activation area and etc instead.

## Compile

Because all BML mods within this repository rely on BML SDK. So I seperate configurations into project configurations and BML configuration. Project configurations are stored in `.vcxproj` file and BML configurations are stored in `MacroProp.props` file located in root path of this repository.  
For compiling this repository, or compiling some parts of this repository, such as some standalone BML mods, you should change `MacroProp.props` file. Point them to your BML SDK path. Then, all projects should be compiled fluently. By the way, if you want to contribute to this repository, do not forget `git checkout -- MacroProp.props` to restore `MacroProp.props` file to their original status.  
As the alternative, I enable GitHub Action to auto build my mods. You also can download mods from GitHub Action Artifacts within 30 days.
