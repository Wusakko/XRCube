# XRCube

## General
This is Unity base project for XR development. Not rocket science at the moment, but you should check "OtherMaterials/Documentation"-folder for the future (system description pics etc.)

## Current state 
It is currently possible to build for PC via OpenXR (that supports SteamVR and Oculus SDK). I tested with Oculus Quest via Oculus link. Quest standalone (apk) is not supported at the moment. It is also supported to build for android devices that uses ARCore via ARfoundation.

## Setup
Here is fast instructions:
1. Download project, 
2. Open project with Unity 2020.2.7f1 (or atleast 2020.2.X) 
3. Open "01Construct" scene from "Scenes"-folder
4. Play or build!

More detailed instructions are coming later and it might contain: Unity installation and device specific project setups

## Install build for the devices
Protoversion (XRCube v0.3) of this project can be tested as Quest standalone build (.apk): https://urly.fi/1VJY 

## Media 
XRCube related videos and list of created realities can be found https://wusakko.com/xrcube

## (Tech) choices
This project is open source and that's why there are no third-party assets used. As you can see from "XRCubeTechTree"-file (*1), OpenXR can lso be used for web developent via WebXR. I think web browsers are not currently ready for immersive XR development and that's why I use Unity game-engine. You don't play games in browser, do you?





