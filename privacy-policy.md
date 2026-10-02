---
layout: 'default'
title: 'Fitch Privacy Policy'
lang: 'en'
permalink: '/privacy-policy/'
home: '/'
alternates:
  - lang: 'en'
    label: 'English'
    url: '/privacy-policy/'
  - lang: 'zh-Hans'
    label: '简体中文'
    url: '/zh-Hans/privacy-policy/'
  - lang: 'ja'
    label: '日本語'
    url: '/ja/privacy-policy/'
---

# Fitch Privacy Policy

**Effective date:** 30 September 2026
**Developer:** Fateh Khan
**Contact:** fatehkhann@gmail.com

## Summary

Fitch is a running and cycling app for iPhone. It records your location while you are recording a workout, stores your activities on your device, and mirrors them to your own private iCloud database. The developer cannot access that data. Fitch has no user accounts, no analytics or crash-reporting SDKs, no advertising, and does not sell, rent, or share your data with third parties. Fitch operates no servers of its own.

## Data Fitch collects

Fitch collects only what it needs to record and compare your workouts:

1. **Location (GPS route).** While you are recording a run or ride, Fitch collects GPS samples from your iPhone (coordinates, timestamps, horizontal accuracy, and speed). These are used to draw your route on the map, calculate distance, pace, speed, and splits, and to compare your position against a saved route or a virtual companion.
2. **Activity metrics.** For each saved activity: sport (running or cycling), date and time, distance, active time, average pace or speed, kilometre or mile splits, the virtual companion target and its pacing history if you used one, the race result (time gap) if you raced a saved route, and whether the activity was a demo.
3. **Preferences.** Your selected sport, measurement units (metric or imperial), chosen virtual companion, and whether you have dismissed the race card. These are stored only on your device.
4. **Recovery checkpoints.** While a recording is in progress, Fitch periodically writes a checkpoint to local storage so an interrupted workout can be recovered. Checkpoints stay on the device and are never synced.

Fitch does not collect your name, email address, contacts, photos, health records, advertising identifiers, or any persistent device identifier. Fitch does not read from or write to Apple Health.

## Where your data is stored

- **On your device.** Activities are stored in a local database inside the app's private container, protected by iOS data protection.
- **In your private iCloud.** If you are signed in to iCloud with iCloud data enabled for Fitch, activities are mirrored to the CloudKit **private database** for your Apple Account. Only devices signed in to your Apple Account can read it. The developer has no way to read, list, or export the contents of your private database. Apple's iCloud terms and Apple's privacy policy govern that storage.
- **Nowhere else.** No route data goes to a public or shared CloudKit database, and nothing is sent to any developer-operated server, because there is none.

If you are not signed in to iCloud, or you turn iCloud off for Fitch, the app keeps working with local storage only.

## Apple services used

- **iCloud (CloudKit).** Sync of your activities between your own devices, as described above. Deleting an activity on one device deletes it from iCloud and from your other devices.
- **Apple Maps (MapKit).** Fitch displays your routes on Apple Maps. Your route line is drawn on the device; Fitch does not upload your route to Apple Maps. Loading map imagery does mean your device requests map tiles for the region on screen from Apple's map service, which is subject to Apple's privacy policy. Map tiles require a network connection unless already cached; recording and saving do not.
- **Live Activities.** During a recording, iOS shows the workout's distance, time, pace and companion gap on the Lock Screen and in the Dynamic Island. This is rendered on the device from the same data; nothing is sent anywhere.
- **Silent push notifications.** Fitch registers for background remote notifications so that iCloud can tell the app when your data changed on another device. These pushes are silent, contain no content, and never appear as an alert. Fitch does not request permission to send you notifications and does not send any.

## Permissions and why Fitch asks for them

- **Location: While Using the App (with Precise Location).** Requested the first time you start a run or ride, never on the Home screen. Fitch uses it to record your route and, once granted, to show your current position on the Home map. Without it you can still browse and manage saved activities, but you cannot record new ones. Precise Location is needed because a coarse location cannot produce a usable route.
- **Background location.** Fitch declares background location so that a workout you have started keeps recording when you lock the screen or switch apps. Background location is used only during a recording that you started and have not paused. Pausing stops location updates entirely, and the system location indicator stays visible whenever Fitch is receiving location. Fitch never collects your location when you are not recording.
- **Background remote notifications.** Used only for the silent iCloud sync pushes described above.

If you revoke location permission mid-workout, Fitch pauses the workout and preserves the data recorded so far.

## Analytics, advertising, and third parties

Fitch contains no analytics SDK, no crash-reporting SDK, no advertising SDK, and no other third-party code that transmits data. Fitch does not sell, rent, trade, or otherwise share your personal data with anyone.

Apple may provide the developer with anonymised crash logs and usage statistics if you have chosen to share diagnostics with app developers in iOS Settings (Privacy & Security > Analytics & Improvements). That choice is controlled by you and by Apple, and those reports do not contain your routes or activities.

## Retention and deletion

Your activities are kept until you delete them.

- **Delete a single activity.** Open it under Races and choose Delete. The deletion is applied on your device and, if iCloud is enabled, propagated to iCloud and to your other devices.
- **Delete everything on this device.** Uninstalling Fitch removes the local database, preferences, and recovery checkpoints from the device.
- **Delete the iCloud copy.** In iOS Settings, open your Apple Account, then iCloud, then the storage management screen, find Fitch and choose to delete its data from iCloud. Exact wording varies by iOS version. You can also delete each activity in the app before uninstalling.

Because the developer holds no copy of your data, there is nothing for the developer to delete on your behalf. All deletion is under your direct control.

## Children

Fitch is a general-audience fitness app and is not directed at children under 13, or the equivalent minimum age in your region. Fitch does not knowingly collect personal information from children. Since Fitch has no accounts and sends data only to the user's own iCloud, the developer never receives personal information from any user, child or adult. If you believe a child has used Fitch in a way that concerns you, contact the developer at the address below.

## Security

Data on your device is protected by iOS data protection and the app sandbox. Data sent to iCloud travels over Apple's encrypted connections and is stored in your private CloudKit database. Fitch does not transmit data over any other channel.

## Your rights

Depending on where you live, you may have rights to access, correct, export, or delete personal data. Because your data lives only on your devices and in your own iCloud, you can exercise these rights directly: view any activity in the app, delete it in the app, or remove Fitch's iCloud data as described above. If you have a question the app cannot answer, email the developer.

## Changes to this policy

If this policy changes, the updated version will be published with a new effective date. Continued use of Fitch after a change means you accept the updated policy.

## Contact

Fateh Khan
fatehkhann@gmail.com
