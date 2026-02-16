# Theia SDK - HTC VIVE Sample (Unity 6 LTS)

Sample scene demonstrating eye tracking with HTC VIVE headsets using the Theia SDK.

## Installation

Add via Unity Package Manager git URL:
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/HTCViveSample
```

## Prerequisites

**Important:** The OpenVR/SteamVR package cannot be automatically installed by Unity Package Manager. You must install it manually before using this sample.

### Option 1: SteamVR Unity Plugin (Recommended)
1. Open Unity Asset Store
2. Search for "SteamVR Plugin"
3. Download and import into your project
4. This will automatically include the OpenVR XR Plugin

### Option 2: Manual OpenVR XR Plugin Installation
1. Download the OpenVR XR Plugin package from Valve's GitHub
2. In Unity: Window > Package Manager > + > Add package from disk
3. Select the downloaded .tgz file

### Enable OpenVR
After installation:
1. Edit > Project Settings > XR Plugin Management
2. Check "OpenVR Loader"

## Dependencies

- Theia SDK Core (com.harmoneyes.sdk)
- OpenVR XR Plugin (com.valvesoftware.unity.openvr) - **requires manual installation**

## Version

3.4.1
