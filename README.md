# VR Boxing Trainer

## Project Description
- VR boxing simulation built using Unreal Engine 5.1, optimized for Meta Quest 2. 
- Features includes boxing tutorial, hand tracking, physics-based punching bag, and real-time reaction.

# Project Git
https://github.com/IsaacLSK/UE5_VR_Boxing

## Clone the repository
- git clone https://github.com/IsaacLSK/UE5_VR_Boxing.git
   
# How to open the project
- First, just double click \UE5_VR_Boxing\VRProject_Demo_5_1.uproject
- Then, waiting for project build, shading

# Requirements
- Unreal Engine 5.1.1
- Meta Quest 2
- Android Studio (Project APK deployment requires)
- Quest 2 Install MetaXR Plugin to UE5
	- https://developers.meta.com/horizon/downloads/package/unreal-engine-5-integration/54.0
	- place it in C:\Program Files\Epic Games\UE_5.1\Engine\Plugins\Marketplace\MetaXR

## Project Setup - Android SDK (Project APK deployment requires)
- SDK -> C:/Users/[UserName]/AppData/Local/Android/Sdk
- NDK -> C:/Users/[UserName]/AppData/Local/Android/Sdk/ndk/25.1.8937393
- JDK -> C:/openlogic-openjdk-11.0.17+8-windows-x64

# Control
- Using Meta Quest 2:
	- Left controller's Thumbstick to control moving
	- Left controller's Thumbstick Button to control jumping
	- Right controller's B Press to open menu
	- Right controller's Thumbstick to select menu items
	
# Key Project Structure

## Input Mapping
- /All/Content/FirstPerson/Input/IMC_Default.uasset

## Map 

### World 
- /All/Content/FirstPerson/Maps/FirstPersonMap.umap 

## Background
- /All/Content/GymEAP/Levels/L_GYM.umap

## Actor 

### AI_Trainer
/All/Content/MCO_Mocap_Basics

### AI_Dummy
- /All/Content/Characters/Mannequin_UE4

### AI_temp
- /All/Content/Characters/Mannequins

### Punching hands
- /All/Content/Characters/MannequinsXR

### Punching Bag
- /All/Content/VRTemplate/Materials/AI_PunchingBag/AI_PunchingBag.uasset

## Blueprint

### VR Camera, Movement, Punching hands tracking, collision
- /All/Content/VRTemplate/Blueprints/VRPawn.uasset

### Menu, game flow controllng
- /All/Content/VRTemplate/Blueprints/WidgetMenu.uasset

### Tutorial Board
- /All/Content/VRTemplate/Blueprints/tutorial_board.uasset

### Punching Bag
- /All/Content/VRTemplate/Blueprints/BP_PunchingBag.uasset

### AI_Dummy
- /All/Content/VRTemplate/Blueprints/AI_Dummy.uasset

### AI_temp
- /All/Content/VRTemplate/Blueprints/AI_temp.uasset

### AI_Trainer
- /All/Content/VRTemplate/Blueprints/AI_Trainer.uasset

## Audio
- /All/Content/VRTemplate/Audio/well_done.uasset

## Tutorial Animations
- /All/Content/VRTemplate/AI/Animations/

## Tutorial Board Descriptions
- /All/Content/VRTemplate/Materials/
