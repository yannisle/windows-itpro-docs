---
title: Troubleshoot HoloLens issues
description: Solutions for common HoloLens issues.
author: mattzmsft
ms.author: mazeller
ms.date: 12/02/2019
ms.prod: hololens
ms.topic: article
ms.custom: CSSTroubleshooting
audience: ITPro
ms.localizationpriority: medium
keywords: issues, bug, troubleshoot, fix, help, support, HoloLens
manager: jarrettr
ms.custom: 
- CI 111456
- CSSTroubleshooting
appliesto:
- HoloLens (1st gen)
- HoloLens 2
---

# Troubleshoot HoloLens issues

This article describes how to resolve several common HoloLens issues.

## My HoloLens is unresponsive or won't start

If your HoloLens won't start:

- If the LEDs next to the power button don't light up, or only one LED briefly blinks, you may need to charge your HoloLens.
- If the LEDs light up when you press the power button but you can't see anything on the displays, hold the power button until all five of the LEDs turn off.

If your HoloLens becomes frozen or unresponsive:

- Turn off your HoloLens by pressing the power button until all five of the LEDs turn themselves off, or for 10 seconds if the LEDs are unresponsive. To start your HoloLens, press the power button again.

If these steps don't work, you can try [recovering your device](hololens-recovery.md).

## Hologram image color or brightness does not look right
For HoloLens 2, take the following steps to ensure the highest visual quality of holograms presented in displays:

- **Increase brightness of the display:** Holograms look best when the display is at its brightest level.
- **Bring visor closer to your eyes:** Swing the visor down to the closest position to your eyes.
- **Shift visor down:** Try moving the brow pad on your forehead down, which will result in the visor moving down closer to your nose.
- **Run eye calibration:** The display uses your IPD and eye gaze to optimize images on the display. If you don't run eye calibration, the image quality may be made worse.

## Holograms look unstable

If your holograms are unstable, jumpy, or don't look right, try:

- Cleaning your device visor and sensor bar on the front of your HoloLens.
- Increasing the light in your room.
- Walking around and looking at your surroundings so that HoloLens can scan them more completely.
- Calibrating your HoloLens for your eyes. Go to **Settings** > **System** > **Utilities**. Under **Calibration**, select **Open Calibration**. 

## HoloLens doesn't respond to gestures

To make sure that HoloLens can see your gestures.  Keep your hand in the gesture frame - when HoloLens can see your hand, the cursor changes from a dot to a ring.

Learn more about using gestures on [HoloLens (1st gen)](hololens1-basic-usage.md#use-hololens-with-your-hands) or [HoloLens 2](hololens2-basic-usage.md#the-hand-tracking-frame).

If your environment is too dark, HoloLens might not see your hand, so make sure that there's enough light.

If your visor has fingerprints or smudges, use the microfiber cleaning cloth that came with the HoloLens to clean your visor gently.

## Lights to indicate problems

| When you do this | The lights do this | It means this |
| - | - | - |
| You press the Power button. | One light flashes five times, then turns off. | The HoloLens battery is critically low. Charge your HoloLens. |
| You press the Power button. | All five lights flash five times, then turn off. |  HoloLens cannot start correctly and is in an error state. [Reinstall the operating system](hololens-recovery.md) to recover your device. |
| You press the Power button. | The 1st, 3rd, and 5th lights flash together continually. |  HoloLens may have a hardware failure. To be sure, [reinstall the OS](hololens-recovery.md#hololens-2), and try again. After reinstalling the OS, if the light-flash pattern persists, contact [support](https://support.microsoft.com/en-us/supportforbusiness/productselection?sapid=3ec35c62-022f-466b-3a1e-dbbb7b9a55fb). |

## HoloLens doesn’t respond to my voice commands

If Cortana isn't responding to your voice commands, make sure Cortana is turned on. On the All apps list, select **Cortana** > **Menu** > **Notebook** > **Settings** to make changes. To learn more about what you can say, see [Use your voice with HoloLens](hololens-cortana.md).

## I can't place holograms or see holograms that I previously placed

If HoloLens can't map or load your space, it enters Limited mode and you won't be able to place holograms or see holograms that you've placed. Here are some things to try:

- Make sure that there's enough light in your environment so HoloLens can see and map the space.
- Make sure that you're connected to a Wi-Fi network. If you're not connected to Wi-Fi, HoloLens can't identify and load a known space.
- If you need to create a new space, connect to Wi-Fi, then restart your HoloLens.
- To see if the correct space is active, or to manually load a space, go to **Settings** > **System** > **Spaces**.
- If the correct space is loaded and you're still having problems, the space may be corrupt. To fix this issue, select the space, then select **Remove**. After you remove the space, HoloLens starts to map your surroundings and create a new space.

## My HoloLens can't tell what space I'm in

If your HoloLens can't identify and load the space you're in automatically, check the following factors:

- Make sure that you're connected to Wi-Fi
- Make sure that there's plenty of light in the room
- Make sure that there haven't been any major changes to the surroundings.

You can also load a space manually or manage your spaces by going to **Settings** > **System** > **Spaces**.

## I'm getting a "low disk space" error

You'll need to free up some storage space by doing one or more of the following:

- Delete some unused spaces. Go to **Settings** > **System** > **Spaces**, select a space that you no longer need, and then select **Remove**.
- Remove some of the holograms that you've placed.
- Delete some pictures and videos from the Photos app.
- Uninstall some apps from your HoloLens. In the **All apps** list, tap and hold the app you want to uninstall, and then select **Uninstall**.

## My HoloLens can't create a new space

The most likely problem is that you're running low on storage space. Try one of the [previous tips](#im-getting-a-low-disk-space-error) to free up some disk space.

## The HoloLens emulators isn't working

Information about the HoloLens emulator is located in our developer documentation.  Read more about [troubleshooting the HoloLens emulator](https://docs.microsoft.com/windows/mixed-reality/using-the-hololens-emulator#troubleshooting).
