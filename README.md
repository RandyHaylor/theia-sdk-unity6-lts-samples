# Theia SDK - Unity 6 LTS Samples

Sample scenes and scripts for the Theia SDK (formerly HarmonEyes SDK) targeting Unity 6 LTS.

## Important: Import Samples Individually

This repository contains **3 separate sample packages** that should be imported individually to avoid conflicts. Each sample is designed for a specific VR platform.

**⚠️ Do NOT import multiple platform samples simultaneously** - only import the sample(s) you need for your target VR platform.

## Required First: Core SDK

Before importing any sample, you must first install the core Theia SDK:

```
https://github.com/RandyHaylor/theia-sdk-core.git
```

## Available Samples


### 1. Oculus/Meta Quest Sample

Sample scene for Oculus/Meta Quest headsets with interactive eye tracking demonstrations.

**Import URL:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/OculusSample
```

**What's included:** Demo scene with cubes that highlight when gazed at, showing eye tracking response in real-time.

---

### 2. HTC VIVE Sample

Sample scene for HTC VIVE headsets.

**Import URL:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/HTCViveSample
```

**What's included:** Demo scene configured for HTC VIVE eye tracking testing.

---

### 3. Varjo Sample (Experimental)

Experimental sample scene for Varjo headsets.

**Import URL:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/VarjoSample
```

**What's included:** Early-stage implementation for Varjo device testing.

---

## Installation Instructions

### Step 1: Install Core SDK
1. Open Unity Package Manager (Window > Package Manager)
2. Click "+" → "Add package from git URL..."
3. Paste: `https://github.com/RandyHaylor/theia-sdk-core.git`
4. Click "Add"

### Step 2: Install Your Platform Sample
1. In Package Manager, click "+" → "Add package from git URL..."
2. Paste the URL for your target platform (see above)
3. Click "Add"

## Requirements

- Unity 6 LTS (6000.0) or later
- Theia SDK Core v3.4.0+
- Platform-specific SDKs:
  - **Oculus/Meta Quest:** Meta XR SDK
  - **HTC VIVE:** SteamVR Plugin
  - **Varjo:** Varjo XR Plugin

## Version

Current version: 3.4.0 (matches core SDK version)

## Support

For issues or questions, please open an issue on GitHub.
