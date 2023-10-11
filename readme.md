> View the entire tutorial on [What Up Games](https://www.whatupgames.com).

# How to make a configurable camera with the new Unity Input System
> This tutorial was created with Unity version 2019.2.

In this tutorial, you’re going to build a configurable camera that handles moving, zooming and rotating. This design works great for games that do not want an attached 3rd or 1st person camera, but instead want freedom to move around a scene. Instead of using the old input system, we’ll be hooking it up to the new one and will review key concepts as we go.

Configuration features of the camera are:

1. Camera angle
2. Zoom min/max
3. Zoom default
4. Look offset (where you want the camera to focus on the y axis)
5. Rotation speed

![Demo of Final Result](FinishedExample.gif)

## Learning Outcomes

1. Understand key concepts of the new Input System. 
2. Have a configurable camera that can be customized for your game.

## Prerequisites
This tutorial assumes you have basic knowledge of how Unity works. It does not cover the basics, such as what a GameObject is, a component, when Start is called, etc. 

> You can clone this repository to get the starter project and follow along!  

## Resources
1. Comments, concerns and/or questions can be posted [here](https://github.com/Yecats/GameDevTutorials/issues/1).
2.	Input System [documentation](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.0/manual/index.html) and [GitHub repository](https://github.com/Unity-Technologies/InputSystem).
3. [Introducing the new Input System - Unite Copenhagen Video](https://youtu.be/hw3Gk5PoZ6A)
1. This project uses the [Low Poly: Free Pack](https://www.assetstore.unity3d.com/en/#!/content/58821) by AxeyWorks.

