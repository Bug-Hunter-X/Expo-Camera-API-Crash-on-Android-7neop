# Expo Camera API Crash on Android

This repository demonstrates a bug in the Expo Camera API that causes crashes on certain Android devices. The issue manifests as a frozen preview or a complete application crash, often without clear error messages. The bug is particularly noticeable when switching between camera modes or using the zoom functionality.  This repository includes the buggy code, steps to reproduce the issue, and a potential solution.

## Steps to Reproduce

1. Clone this repository.
2. Run the project using Expo Go.
3. Observe the camera preview.
4. Attempt to switch between camera modes (front/rear) or use the zoom feature.
5. The preview will likely freeze or the app will crash.

## Potential Solution

The provided solution involves adding error handling and utilizing asynchronous operations for smoother camera transitions. This is just a potential fix; a more comprehensive solution might be needed depending on the specific device and Android version.