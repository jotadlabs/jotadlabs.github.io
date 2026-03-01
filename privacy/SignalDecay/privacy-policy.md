---
layout: default
title: Privacy Policy — Signal Decay
---

# Privacy Policy

**Signal Decay**  
Last updated: February 27, 2026  
Developer: JOTAD Labs

---

## Overview

Signal Decay is a location-based audio game. This policy explains what data is accessed, how it is used, and what is stored.

**Short version:** all data stays on your device. Nothing is transmitted to any server.

---

## Data We Access

### Location (GPS)

Signal Decay uses your device's GPS to position in-game audio sources in the real world. This is core to the gameplay — the audio you hear is spatially anchored to your real-world position.

- **What is read:** latitude and longitude while the app is in the foreground.
- **What is stored:** nothing. Your position is used in real time to calculate audio direction and distance. No location history is recorded or stored.
- **What is shared:** nothing. Location data never leaves your device.

### Device Compass / Magnetometer

The compass determines which direction you are facing, so audio pans correctly as you turn.

- **What is read:** compass heading while the app is in the foreground.
- **What is stored:** nothing.
- **What is shared:** nothing.

### Audio Output

The app plays audio through your headphones or speaker. It does not access your microphone.

---

## Data We Store Locally

Signal Decay stores the following data in local encrypted storage (Hive) on your device:

| Data | Purpose |
|------|---------|
| Game progress (completed zones, unlocked bands) | Save your progress between sessions |
| Settings (volume, haptic preferences) | Remember your preferences |
| Play statistics (distance walked, fragments collected) | Display stats in-app |
| Daily streak / session timestamps | Calculate streak achievements |
| In-app purchase status | Remember whether you have purchased the Pro upgrade |

This data is stored only on your device. It is not backed up to any cloud service or transmitted anywhere.

---

## In-App Purchases

Signal Decay offers an optional one-time in-app purchase ("Upgrade Your Receiver") to unlock additional content. Payment is processed entirely by Google Play (Android) or the App Store (iOS). The developer does not handle payment card data. The only record stored on your device is a boolean flag indicating whether the purchase was completed.

---

## Third-Party SDKs

Signal Decay uses the following third-party SDKs. These operate entirely on-device and do not transmit data externally:

| SDK | Purpose |
|-----|---------|
| `geolocator` | GPS access |
| `flutter_compass` | Compass access |
| `just_audio` | Audio playback |
| `hive` | Local storage |
| `in_app_purchase` | In-app purchases (interfaces with the OS store) |

The `in_app_purchase` SDK communicates with Google Play or the App Store to verify purchases. That communication is between your device and the store you use; the developer does not see or store any data from that exchange beyond the grant/deny result.

---

## Permissions

| Permission | Why it is requested |
|-----------|-------------------|
| `ACCESS_FINE_LOCATION` | GPS-based audio positioning |
| `ACCESS_COARSE_LOCATION` | Fallback if fine location is unavailable |
| `VIBRATE` | Haptic feedback when near a signal source |
| `WAKE_LOCK` | Keep the screen/CPU active during active gameplay |

---

## Children

Signal Decay is intended for players aged 12 and older. The app does not knowingly collect data from children under 13. If you believe a child under 13 has used the app, please contact us — though note that no personal data is collected or transmitted regardless of age.

---

## Data Retention and Deletion

All game data is stored locally on your device. You can delete it at any time by uninstalling the app. No data remains on any server because no data is ever sent to a server.

---

## Changes to This Policy

If this policy changes materially (e.g. if analytics or cloud features are added in a future version), this page will be updated and the "Last updated" date above will change. Continued use of the app after such changes constitutes acceptance of the updated policy.

---

## Contact

Questions about this privacy policy:

**JOTAD Labs**  
Email: [jotad.labs@gmail.com](mailto:jotad.labs@gmail.com)  
GitHub: [github.com/jotadlabs](https://github.com/jotadlabs)

---

*Signal Decay does not use advertising, analytics SDKs, crash reporting services, or any form of remote data collection. Your location data never leaves your device.*
