# MYNOX CAMERA PRO — Complete Android source project

Native Android app using Kotlin + CameraX. Android displays the runtime Camera permission prompt at first launch.

## Included features
- Runtime Android Camera permission request on launch
- Runtime Microphone permission request only when recording video
- Front/back camera switching
- Photo capture at CameraX maximum-quality mode and JPEG quality 100
- Video recording: prefers UHD where supported, falls back to HD-or-higher supported quality
- Torch/flash control on supported rear cameras
- Zoom slider and exposure compensation slider
- 3s / 5s / 10s photo timer
- Rule-of-thirds grid overlay
- Natural, Warm, B&W and Vivid filters applied to saved photos
- Saves photos to Pictures/MynoxCamera and videos to Movies/MynoxCamera
- Opens the Android gallery

## Build APK using a phone
1. Download and extract this ZIP.
2. Create a GitHub repository.
3. Upload all files and folders inside the extracted project.
4. Open Actions -> Build MYNOX Camera Pro APK -> Run workflow.
5. After the workflow succeeds, download artifact MYNOX-CAMERA-PRO-APK.
6. Extract the artifact ZIP and install app-debug.apk.
7. Launch the app and tap Allow on the Android Camera permission prompt.

## Important limits
- This project source is provided; it has not been compiled or tested on your handset in this environment.
- Camera sensor quality, UHD recording, torch, zoom range, and exposure range depend on the phone's hardware and vendor camera implementation.
- Filters are applied to saved photos; they are not live preview filters.
- This is a debug build configuration for testing, not a signed Play Store release.
