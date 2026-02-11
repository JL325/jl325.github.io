# JL Bridge (BLE Bridge for Valeton GP-5/GP-50 & Sonicake Pocket Master) - User Guide

This application serves as a comprehensive controller and BLE bridge for Valeton GP-5/GP-50 & Sonicake Pocket Master guitar multi-effects processors. It allows you to control your device wirelessly and acts as a bridge to let the official Valeton App connect to your device simultaneously.
![connection](https://github.com/user-attachments/assets/5f52a737-a3e7-47c6-9805-4db0ca1f8b63)

## 📱 Features

*   **Dual Mode Support:** Fully compatible with both **Valeton GP-5**/**GP-50** & **Soincake Pocket Master**.
*   **BLE Bridge Mode:** Allows the official app (Valeton/Sonicake) to connect to your device *through* JL Bridge.
*   **Preset Management:** Switch presets instantly (0-99) with quick-access buttons.
*   **Effect Control:** Toggle individual effects (NR, DST, AMP, CAB, DLY, RVB, etc.) on/off.
*   **Dual Volume Control:** 
    *   **Global Volume:** Master output level (affects all presets)
    *   **Preset Volume:** Individual preset volume level
*   **Quick CTRL Panel:** 
    *   4 customizable preset slots for instant access
    *   4 quick effect toggle buttons
*   **Advanced Delay Controls:**
    *   **MS Mode:** Direct millisecond input (1-9999ms)
    *   **Beat Mode:** Musical note synchronization with 9 beat types
*   **Effect Chain Visualization:** Visual effect chain with drag-and-drop reordering
*   **Tap Tempo:** Set delay time with visual BPM indicator and LED pulse
*   **Preset Naming:** Save custom preset names (up to 10 characters)
*   **Landscape/Portrait Support:** Optimized UI for both orientations
*   **Ad-Free Sessions:** Watch 15s ads for 15-min ad-free experience (stackable)

---

## 🚀 Getting Started

### 1. Installation
*   Download and install the [JL Bridge](https://play.google.com/store/apps/details?id=com.jl325.jlbridge&pcampaignid=web_share) APK on your Android device.
*   Ensure **Bluetooth** and **Location Services** (required for BLE scanning on Android 11 and below) are enabled.
*   Grant the necessary permissions when prompted upon first launch.



### 2. Connecting to Your Device
1.  Turn on your Valeton GP-5/GP-50 or Pocket Master unit.
2.  Open the **JL Bridge** app.
3.  On the startup screen, select your device model:
    *   **GP-5**
    *   **GP-50**
    *   **Pocket Master**
    <img src="https://github.com/user-attachments/assets/122c12a4-ccdc-4953-9ce7-5ae41af412f9" width="30%">
4.  The app will automatically scan for available devices.
5.  Tap your device name in the list to connect.

    <img src="https://github.com/user-attachments/assets/38e5c582-b1da-40f6-bd0f-2040e1e8666c" width="30%">
6.  Wait for initialization to complete
   
    <img src="https://github.com/user-attachments/assets/4f0fde89-caab-4de0-a74a-c4a0c64b8965" width="30%">
---

## 🎛️ Modes of Operation

### Mode A: Standalone Controller
Use JL Bridge as your primary controller.
*   **Change Presets:** Click preset name on top bar, it will pop up a preset list.

<img src="https://github.com/user-attachments/assets/093e2657-0bb7-40f8-8aa4-b185a6b8757b" width="30%">

*   **Toggle Effects:** Tap the effect blocks (NR, DST, AMP, CAB, etc.) at the bottom to turn them ON/OFF.
   <img src="https://github.com/user-attachments/assets/89b90008-9982-4373-a6dc-56c30d02fe63" width="30%">

*   **Adjust Volume:** Drag the volume slider to change the output level.
   <img src="https://github.com/user-attachments/assets/8260c401-daa2-41d3-982e-4c4fc6f8a2ba" width="30%">


### Mode B: Bridge Mode (Using with Official App)
This is the unique feature of JL Bridge. It lets you use the official Valeton App wirelessly while keeping JL Bridge running.

1.  **Connect JL Bridge** to your GP-5/GP-50/Pocket master first (as described above).
2.  **Keep JL Bridge open** (do not force close it).
3.  Open the **Official Valeton App** on another device.
4.  In the Official App's connection menu, look for:
    *   **"JL BRIDGE"**

<img src="https://github.com/user-attachments/assets/65ef8794-d2ef-4692-ae92-ea2e8b4f1d25" width="30%"> <img src="https://github.com/user-attachments/assets/dc7c7f8d-7ca4-4d00-bfa2-1d976a48aed6" width="30%"> <img src="https://github.com/user-attachments/assets/a486f3ff-1f5c-498e-8443-6018c34b8410" width="30%">

5.  Connect to it.
6.  **Done!** Now any change you make in the Official App is forwarded to the pedal, and any change on the pedal is reflected in both apps.

---

## 🎛️ Main Interface

### Top Bar
*   **Preset number + name**
*   **LED BPM indicator**
*   **Store button**
*   **Home button**
*   **More:** show/hide LED indicator/Save button/Home button, Watch Ads to remove Ads, About for Terms & Conditions
<img width="30%" src="https://github.com/user-attachments/assets/25d7475a-b795-4085-ae4a-c5ba900b15f6" />

<img width="30%" height="711" alt="image" src="https://github.com/user-attachments/assets/714f0d26-dba2-4b2c-bc8d-250c6fd6b86a" />


### Panel 1
*   **Preset Number Display:** Current preset (0-99)/(P01-F50)
*   **Gloabl volume:** Mute button + bar control
*   **Preset volume:** Mute button + bar control
  <img width="30%" src="https://github.com/user-attachments/assets/5d80b44a-7998-40c5-9c59-68350f78aeab" />


### Panel 2
*   **ms/beat mode:** switch ms mode/beat mode
*   **Beat note:** Offer the option of 1/4, 1/8, 1/16, 1/4T, 1/8T, 1/16T, 1/4D, 1/8D, 1/16D
*   **Delay time/BPM display**
*   **-/+ button for ms & BPM adjustment:** Short press to decrease by 1; long press to decrease continuously.
*   **Tap tempo**
  <img width="30%" src="https://github.com/user-attachments/assets/574d0bdd-e6d3-459a-a2af-d915bc2f453b" />

### Effect Chain (Bottom Panel)
*   **Effect Blocks:** Visual representation of effect order
    *   **color:** Effect is ON
    *   **Gray:** Effect is OFF
*   **Tap to toggle:** Enable/disable individual effects
*   **Long-press to drag:** Reorder effects in the chain
<img width="30%" src="https://github.com/user-attachments/assets/b2c30a4a-a6a7-4205-bb53-2457538ca862" />

---

## 💡 Advanced Features

#### Quick Presets Switches
*   **4 Quick Preset Slots:** Assign your presets for instant recall
*   **To Configure:**
    1. Long-press a slot
    2. Select a preset number (0-99)
    3. Optionally name it
*   **To Use:** Single tap to switch to that preset
<img width="30%" height="159" alt="image" src="https://github.com/user-attachments/assets/a6138103-88d0-4164-ad4e-3f77ec668328" />
  <img width="30%" height="811" alt="image" src="https://github.com/user-attachments/assets/fa2b608e-a531-4a00-9f43-8e1f2d921a60" />

#### Quick Effects
*   **4 Effect Toggles:** Quickly turn effects on/off
*   **To Configure:**
    1. Long-press a slot
    2. Select an effect type (NR, DST, AMP, CAB, DLY, RVB, MOD, CHO, EQ, WAH)
*   **To Use:** Single tap to toggle effect on/off
*   **Visual Feedback:** color = ON, Gray = OFF
<img width="30%" height="159" alt="image" src="https://github.com/user-attachments/assets/45348384-aadc-4a29-a23a-5cdce58daf3e" />
<img width="30%" height="903" alt="image" src="https://github.com/user-attachments/assets/523915e9-0659-41b8-93e2-1ee7c651be57" />


#### Quick ctrl
*   **4 Effect Toggles:** Quickly turn control
*   **To Configure:**
    1. Long-press a slot
    2. Select an ctrl type (<, >, MODE, TAP)
*   **To Use:** Single tap to switch corresponding function
<img width="30%" height="151" alt="image" src="https://github.com/user-attachments/assets/827a9f58-7bcd-4fba-beb8-c1052cad7fb8" />
<img width="30%" height="1177" alt="image" src="https://github.com/user-attachments/assets/979ef4da-a3d9-4a52-8ee0-13b36bc2c1f9" />


### Advanced Delay Settings

#### Under ms Mode
Long-press the **Delay time/BPM display** button to access:
*   **Range:** 20-4000ms
*   **Input Methods:**
    *   Tap number buttons
*   **Apply:** Tap "OK" to confirm
<img width="30%" height="182" alt="image" src="https://github.com/user-attachments/assets/88b1f492-c77e-4fc1-a5fe-aae0ffa1ec49" />
<img width="30%" height="631" alt="image" src="https://github.com/user-attachments/assets/068f5695-527a-4087-b2bd-c252a2476a90" />


#### Beat Mode
Long-press the **Delay time/BPM display** button to access:
*   **BPM Control:** Set tempo (40-300 BPM)
*   **Input Methods:**
    *   Tap number buttons
*   **Apply:** Tap "OK" to confirm
<img width="30%" height="175" alt="image" src="https://github.com/user-attachments/assets/1fd39157-f652-468d-8a1e-c75ad712b040" />
<img width="30%" height="631" alt="image" src="https://github.com/user-attachments/assets/85a9d19d-e70c-4276-8ec4-c04067483501" />


*   #### Beat Note set as default**
Long-press the **Beat note** button to access:
*   **Beat Types (9 options):**
    *   Whole Note (1/1)
    *   Half Note (1/2)
    *   Quarter Note (1/4)
    *   Eighth Note (1/8)
    *   Sixteenth Note (1/16)
    *   Dotted Quarter (1/4.)
    *   Dotted Eighth (1/8.)
    *   Quarter Triplet (1/4T)
    *   Eighth Triplet (1/8T)
*   **Apply:** Tap "OK" to confirm
<img width="30%" height="182" alt="image" src="https://github.com/user-attachments/assets/c5c5b140-1221-43e6-9945-f1ae6bf59a85" />
<img width="30%" height="865" alt="image" src="https://github.com/user-attachments/assets/ec9e2418-3e92-4ee1-8eaa-3c8f79355a14" />



---

## 🌐 Bridge Mode (Multi-Device Connection)

JL Bridge can act as a BLE server, allowing the official app to connect simultaneously.

### Setting Up Bridge Mode

1.  **Connect JL Bridge** to your GP-5/GP-50/Pocket Master first
2.  **Keep JL Bridge open** (do not force close)
3.  **On another device** open the official app:
    *   **Valeton App** (for GP-5/GP-50)
    *   **Sonicake App** (for Pocket Master)
4.  **In the official app**, look for:
    *   **"JL BRIDGE"**
5.  **Connect** to it
6.  **Done!** Now both apps control the same device

> **Note:** JL Bridge must remain connected to the physical device for bridge mode to work.

---

## 📐 Landscape Mode

JL Bridge automatically adapts to screen orientation.

<img width="2340" height="1080" alt="image" src="https://github.com/user-attachments/assets/6b91dc25-5662-4395-932d-90cfe540a641" />



---
## External Command Assignments: Quick Presets, Effects, and Controls
*    Quick preset switch: CC01, CC02, CC03, CC04
*    Quick effect switch: CC11, CC12, CC13, CC14
*    Quick ctrl switch: CC21, CC22, CC23, CC24

---
## Chocolate Pedal Setting
*   Select **Advanced custom mode**
*   Mode: Short tread (Bank A information), Long tread (Bank B information)
*   For example:
    *   [A] Foot Switch: A Bank → Channel 1, Type: CC, Data 1: 1, Data 2: 0
    *   [A] Foot Switch: B Bank → Channel 1, Type: CC, Data 1: 11, Data 2: 0
<img width="30%" height="2622" alt="image" src="https://github.com/user-attachments/assets/5debc4a9-8707-49f7-a80b-223461ed3218" />
<img width="30%" height="2622" alt="image" src="https://github.com/user-attachments/assets/256326fd-74bf-4ac7-a1ca-a1ebb0191b53" />
<img width="30%" height="2622" alt="image" src="https://github.com/user-attachments/assets/e2a96a51-1a85-4374-9b91-9fda3f0ccb9f" />
<img width="30%" height="2622" alt="image" src="https://github.com/user-attachments/assets/54790455-954e-4e61-997c-da1401e9ec3c" />
<img width="30%" height="2622" alt="image" src="https://github.com/user-attachments/assets/888090e5-6cce-421c-9515-5c2dc220d88b" />
<img width="30%" height="2622" alt="image" src="https://github.com/user-attachments/assets/f0ab1e2d-ea35-43f6-9d2a-b0e5d84affd8" />

*    feel free to download my setting for Mvave Chocolate pedal setting (it contains 2 .fcp files for my chocolate pedals)
*    [Chocolate plus setting.zip](https://github.com/user-attachments/files/25238103/Chocolate.plus.setting.zip)


## ⚙️ Settings & Customization

### Top Bar Icon Configuration
*   Long-press icons to rearrange
*   Show/hide specific functions
*   Customize for your workflow

### Quick CTRL Configuration
*   **Presets:** Long-press slot → assign preset
*   **Effects:** Long-press slot → assign effect type
*   **Reset:** Long-press slot → select "Clear"

### Ad-Free Sessions
*   **Watch Ad:** Tap ad button → watch 15s video
*   **Reward:** 15 minutes ad-free experience
*   **Stackable:** Watch multiple ads to extend time
*   **Persistent:** Time persists across app restarts

---

## ⚠️ Troubleshooting

### Connection Issues

**Q: Cannot find my device during scanning.**
*   **A:** Ensure device is powered on and Bluetooth is enabled
*   **A:** Check if device is already connected to another app
*   **A:** Try restarting both device and phone
*   **A:** Enable Location Services

### Bridge Mode Issues

**Q: Official app cannot find "JL BRIDGE".**
*   **A:** Check if 4 clients are already connected (max limit)
*   **A:** Restart JL Bridge to reset bridge server

**Q: Commands from official app don't work.**
*   **A:** Ensure JL Bridge has stable connection to hardware
*   **A:** Try disconnecting and reconnecting official app

### Volume Control Issues

**Q: Global Volume vs Preset Volume confusion.**
*   **A:** Global Volume affects all presets equally
*   **A:** Preset Volume is saved per preset
*   **A:** Changes to Preset Volume require saving preset

---

## 📝 Disclaimer

This application is an independently developed tool and is **NOT** an official product of Valeton or Sonicake. It is not affiliated with, authorized, maintained, sponsored, or endorsed by the manufacturers. All product names, logos, and trademarks are the property of their respective owners.

**Use at your own risk.** The developer assumes no responsibility for any damage to your device or equipment.

---

## 📧 Support & Contact

**Email:** johnworks325@gmail.com  
**Privacy Policy & Terms:** https://jl325.github.io/policy/jl-bridge

For bug reports, feature requests, or general inquiries, please contact us via email.

---

**Thank you for using JL Bridge!** 🎸🎵

