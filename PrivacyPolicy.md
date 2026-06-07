# Privacy Policy — GestureRobotPilot

**Last updated: 2026-06-07**

## Overview

GestureRobotPilot is a local robot-control application. It uses your device camera to detect hand gestures and sends UDP control packets to a robot on your local network. The app does **not** collect, store, transmit, or share any personal data.

## Data Collected

**None.** Specifically:

- **Camera:** The camera feed is processed entirely on-device by MediaPipe Tasks Vision. No video or image data is stored or transmitted off-device.
- **Network:** The app sends UDP command packets exclusively to IP addresses you configure. These packets contain only robot control codes (no personal information).
- **Analytics:** The app contains no analytics, crash-reporting, or telemetry SDKs.
- **Advertising:** The app contains no advertising frameworks or ad identifiers.
- **Location:** The app does not request or access location data.
- **Health/Fitness:** The app does not access HealthKit or motion/fitness data.

## Third-Party SDKs

| Library | License | Data collected |
|---|---|---|
| MediaPipe Tasks Vision (Google LLC) | Apache 2.0 | None — on-device inference only |
| SwiftTasksVision (Pascal Burlet) | MIT | None |
| MobileVLCKit (VideoLAN) | LGPL 2.1+ | None — local RTSP stream decoding only |

## Children's Privacy

The app does not knowingly collect data from anyone, including children under 13.

## Changes

If this policy changes, the updated version will be posted at this URL. The "Last updated" date will reflect any revision.

## Contact

Questions: open an issue at https://github.com/drhenrich/GestureRobotPilot
