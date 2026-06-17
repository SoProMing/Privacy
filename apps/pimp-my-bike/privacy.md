---
layout: default
title: Pimp My Bike Privacy Policy
permalink: /apps/pimp-my-bike/privacy/
---

# Privacy Policy for Pimp My Bike

Effective date: June 17, 2026

This privacy policy explains how Pimp My Bike handles data in the iPhone app. It is written both for App Store review and for people who find the source code or project files in a public GitHub repository.

## Short Version

Pimp My Bike is designed as a local-first bike dashboard, rear-view mirror, ride safety, and dashcam app.

- The app does not require an account with Flatbrainer.
- The app does not contain advertising SDKs.
- The app does not sell personal data.
- The app does not use third-party analytics or third-party crash reporting SDKs.
- Your bike profiles, ride events, settings, road-quality reports, and saved clips are stored on your device unless you choose to export, share, save to Photos, or use Apple/system services.
- Camera frames used for the mirror, dashcam, and vehicle/proximity detection are processed on device.
- Some optional features use Apple system services or external services, such as Location Services, Camera, Microphone, Motion, Speech Recognition, Apple Music, StoreKit/App Store purchases, Photos, Maps, weather data, and point-of-interest lookup.

## Data You May Store in the App

Depending on how you use Pimp My Bike, the app may store the following data on your device:

- Bike profiles, bike names, bike styles, colors, notes, ride modes, dashboard style, theme settings, and mirror calibration settings.
- Setup state, mount side, proximity warning settings, audio warning settings, route settings, power-saving settings, and clip retention settings.
- Ride speed, ride distance, elapsed ride time, total distance, ride recaps, ride events, close-pass events, saved-clip references, and safety summaries.
- Parked-bike location, parked-bike note, and parked-bike saved time, if you save a parked-bike location.
- Maintenance reminders, including service dates and distance counters for tasks such as chain lube, tire pressure, brakes, lights, and battery.
- Road-quality reports, including vibration severity, classification, detected time, speed, location coordinates if available, horizontal accuracy, bike identifier, and sync/export status.
- Dashcam clips saved by the app, including front-camera and optional back-camera video. Clips may include microphone audio if audio recording is enabled.
- Temporary rolling video segments used to create dashcam clips.
- Purchase entitlement state needed to unlock app features.
- Exported files you explicitly create, such as road-quality JSON payloads, incident packages, and shared video clips.

This data is used to provide the app's mirror, dashboard, ride tracking, safety warnings, dashcam, road-quality, maps, music, voice command, maintenance, and export features.

## Local Storage

By default, app data is stored locally on your device using app storage, UserDefaults, the app's Documents directory, and temporary files. Flatbrainer does not operate a server that receives your Pimp My Bike ride database, camera feed, or saved clips.

Deleting settings, reports, clips, recaps, or other items inside the app removes those items from the app's local data store where the app provides deletion controls, subject to normal device backup and operating system behavior.

Deleting the app removes its local app data from the device. Files you exported, shared, copied through file sharing, or saved to Photos may remain wherever you saved or shared them.

## Camera and Dashcam Data

Pimp My Bike uses camera permission for the rear-view mirror, front/back dashcam capture, and on-device vehicle/proximity detection.

Camera frames are used locally by the app. The app includes an on-device Core ML vehicle detection model for proximity warnings. The app is not designed to send the camera feed to a Flatbrainer server.

When dashcam history is enabled, the app may keep short temporary rolling video segments. When you manually save a clip or a safety event triggers a clip save, the app exports an MP4 file into the app's local Documents directory. Clips may be deleted according to your clip retention setting unless you mark them as protected.

If you share a clip, export an incident package, use file sharing, or save a clip to Photos, you choose where that media goes. The receiving app, service, or Photos library handles the media under its own settings and privacy policy.

## Microphone and Speech Recognition

Microphone permission may be used for dashcam audio and for in-app voice commands.

If audio recording for saved clips is enabled, microphone audio may be included in saved dashcam clips. If you share or export those clips, the audio is included in what you share.

Speech Recognition may be used for hands-free app controls. Speech recognition is provided through Apple's system speech recognition services and is governed by Apple's privacy policies and device settings. The app is not designed to send voice command audio or transcripts to a Flatbrainer server.

You can control microphone and speech recognition permissions in iOS Settings.

## Location, Maps, Weather, and POI Data

Location permission is used for speed, distance tracking, heading, ride context, nearby points of interest, parked-bike location, route aids, weather lookup, and optional location-tagged incident or road-quality events. The app may request background location so speed and distance can stay updated while riding.

When location features are enabled, the app may process or store:

- Current location and heading while riding.
- Speed, distance, and total distance.
- Parked-bike coordinates and notes.
- Coordinates attached to road-quality reports or incident events, if those features are enabled.
- Map destinations, route context, and nearby point-of-interest results.

The app may use Apple services such as Location Services, MapKit, Maps search, routes, and opening destinations in Apple Maps. Those Apple services are governed by Apple's privacy policies and your Apple ID/device settings.

The app may send coordinates to weather or point-of-interest services so those services can return local ride weather or nearby amenities. In the current app implementation, weather lookups use Open-Meteo and drinking-water point-of-interest lookup may use the Overpass API. Those services process requests under their own policies.

You can disable location access at any time in iOS Settings. If you disable location access, speed, distance, maps, weather-by-location, parked-bike location, and location-tagged safety features may not work.

## Motion and Road-Quality Data

Motion permission may be used to detect forceful vibration, damaged roads, bad surfaces, and possible crashes while riding.

Road-quality reports are stored locally unless you choose to export or share them. Exported reports may include classification, severity, timestamp, acceleration value, speed, bike identifier, and coordinates if location was available for the report.

## Apple Music

Apple Music or media library permission may be used to show music controls and operate playback while riding. Pimp My Bike is not designed to collect your music library or listening history for Flatbrainer.

Apple's handling of Apple Music and media library information is governed by Apple's privacy policies and your device settings.

## Photos, Files, Exports, and Sharing

Photo library add permission is used only when you choose to save a dashcam clip to Photos.

The app supports document/file access and sharing so you can manage saved clips, incident packages, and exported road-quality data. Exported files may include video, audio, dates, event details, speed, bike profile information, road-quality details, and coordinates depending on what you export.

Once you share, export, copy, or save app data to another location, that destination handles the data under its own privacy policy and settings.

## Purchases

In-app purchases are handled by Apple's StoreKit and App Store systems. Pimp My Bike uses purchase information to load product offers, complete purchases, restore purchases, and unlock purchased app features.

Flatbrainer does not receive your full payment card details. Apple may provide purchase status or transaction information needed to operate App Store purchases.

## Data Not Collected by Flatbrainer

The app is not designed to collect the following data for Flatbrainer:

- Advertising identifiers.
- Third-party tracking identifiers.
- Browsing history.
- Contacts.
- HealthKit health records.
- Photos library contents, except clips you explicitly save to Photos.
- Full payment card numbers.
- Analytics events sent to a Flatbrainer server.
- Crash reports sent to a third-party crash reporting service by the app.
- Camera feeds, microphone audio, or speech transcripts sent to a Flatbrainer server.

Apple may still provide developers with App Store Connect information such as app downloads, sales, subscription or purchase information, crash diagnostics, and aggregated usage metrics according to Apple's developer tools and user privacy settings.

## Public GitHub Repository

This policy describes the Pimp My Bike app. If you interact with a public GitHub repository for the app, GitHub may process your GitHub account information, issues, pull requests, comments, and repository activity under GitHub's own privacy policies.

Do not post private ride data, routes, addresses, coordinates, bike identifiers, road-quality exports, incident packages, dashcam clips, screenshots, or other personal data in public GitHub issues or pull requests.

## Data Retention and Deletion

Data you create in the app remains in the app until you delete it, export it, overwrite it, clear it, or uninstall the app. Saved clips may also be removed by the app's clip retention policy unless protected.

To remove app data:

1. Delete saved clips in the app where available.
2. Clear ride events, recaps, road-quality reports, parked-bike location, or other saved items where the app provides controls.
3. Delete exported files wherever you saved or shared them.
4. Remove clips from Photos if you saved them there.
5. Delete the app from your device to remove local app data.

## Children

Pimp My Bike is a ride dashboard, safety, and dashcam tool. It is not directed to children and is not intended to knowingly collect personal data from children.

## Changes to This Policy

This policy may be updated when the app's features or data handling change. The effective date at the top of the policy will be updated when meaningful changes are made.

## Contact

For privacy questions, use the developer contact information listed for Pimp My Bike on the App Store or the contact method published by the repository owner.

If you use GitHub to ask a general question, do not include personal data, private routes, coordinates, dashcam clips, incident packages, or private screenshots in a public issue or pull request.
