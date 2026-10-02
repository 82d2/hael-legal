# Privacy Policy

**hæl** — last updated October 2, 2026

hæl is made by KI-GEN Studios LLC. This policy describes what the app stores, where it goes, and who else handles any of it.

In short: your fasting, cycle, and weight data stays with you, on your devices, in your own iCloud account, and in Apple Health. Two outside services are involved. TelemetryDeck receives anonymous usage signals, and RevenueCat verifies purchases. Neither receives your fasting, cycle, or weight records, or anything from Apple Health.

---

## What hæl stores

- Fasting history (start and end times, target and actual duration, completion)
- Body weight entries
- Menstrual cycle information (last period start date, cycle length)
- Streaks, preferences, and settings
- Whether the full experience has been purchased

## Where it is stored

**On your device.** All of the above is stored in UserDefaults and in App Group shared storage (`group.app.hael.fasting`), which lets the widget read the same data.

**In your iCloud account.** If iCloud is enabled, hæl syncs your fasting history between your own devices using iCloud Key-Value Storage. Weight entries, last period start date, and cycle length sync the same way unless you connect Apple Health for them. Once you do, hæl stops copying them to iCloud, removes what it stored there, and Apple Health keeps them in sync instead. This data lives in your iCloud account under Apple's terms. KI-GEN Studios LLC cannot access it. hæl does not use CloudKit or any server of its own.

**Between your iPhone and Apple Watch.** Fast status, streak, and cycle phase are sent directly from your iPhone to your paired Apple Watch using Apple's WatchConnectivity framework.

## Apple Health (HealthKit)

hæl uses HealthKit only with your permission, granted through the standard iOS prompt. You can change these permissions at any time in Settings > Health > Data Access & Devices.

hæl **reads**:

- **Menstrual flow**, to determine your cycle phase
- **Body mass**, to show weight trends in the body ledger
- **Resting heart rate**, for context in the weekly letter

hæl **writes**:

- **Menstrual flow**, when you record a period start in hæl
- **Body mass**, when you log a weight in hæl
- **Workouts**, recording a completed fast as a mind and body session
- **Dietary energy**, a zero-calorie entry marking a completed fasting window

From hæl 4.2, fasts are recorded in Apple Health only if you turn on "record fasts" in Settings > Apple Health. It is off by default. Earlier versions record every completed fast once Apple Health access is granted.

HealthKit data is never sent to KI-GEN Studios LLC, TelemetryDeck, RevenueCat, or anyone else, and it is never used for advertising or marketing.

## Analytics (TelemetryDeck)

hæl uses TelemetryDeck to understand how the app is used. It sends events such as "session started" or "share completed", with a few details attached:

- days since the app was last opened
- consecutive-day open streak
- whether the full experience has been purchased

TelemetryDeck identifies an install only by an anonymized, hashed identifier. It does not receive your name, email, fasting history, weight, cycle information, or any Apple Health data. See telemetrydeck.com/privacy.

## Purchases (Apple and RevenueCat)

The full experience is a one-time purchase processed by Apple. hæl never sees or stores your payment information.

hæl uses RevenueCat to verify purchases and restore them across devices. RevenueCat receives:

- a random app user ID that RevenueCat generates, not linked to your name, email, or Apple ID
- your purchase and transaction history for hæl
- Apple's identifier for vendor, a device ID that is specific to apps from KI-GEN Studios LLC and cannot be used to track you across other companies' apps
- technical details: device model, operating system version, app version, App Store country, and preferred language

hæl never gives RevenueCat your name, email, or any other personal detail. RevenueCat uses this data only to verify purchases for hæl. It does not receive your fasting, cycle, or weight records, or any Apple Health data. See revenuecat.com/privacy.

## Notifications

If you turn on notifications, hæl schedules them on the device. No notification tokens are sent to any server.

## Siri and Shortcuts

hæl offers Siri Shortcuts to begin a fast and check its progress. Siri and Shortcuts requests are handled by Apple under Apple's privacy policy. hæl does not receive that data.

## What hæl does not do

- No accounts or logins
- No advertising and no advertising identifiers
- No tracking across other apps or websites
- No selling or sharing of personal data

## Exporting your data

You can export your fasting history as a CSV file, or a backup of your records as a JSON file, from Settings. The file is created on your device and goes only where you choose to send it.

## Deleting your data

**In the app:** Settings > delete all data. This erases your fasting history, cycle data, weight entries, and preferences from the device and from iCloud Key-Value Storage. It also deletes the weight, workout, and dietary energy entries hæl wrote to Apple Health. Period starts recorded in Apple Health are kept, because they may be part of your wider cycle history. You can remove them in the Health app. Health data written by other apps is never affected.

**By deleting the app:** this removes on-device data. Data synced to iCloud Key-Value Storage may remain in your iCloud account, so use "delete all data" first if you want it removed everywhere.

**Purchase records:** Apple and RevenueCat keep purchase records so you can restore your purchase. To request deletion of your RevenueCat record, email hello@hael.app with the Apple order ID from your purchase receipt.

## Consumer health data

Residents of Washington, Nevada, Connecticut, and other states with consumer health data laws can read the Consumer Health Data Privacy Policy at hael.app/consumer-health-data.

## Children

hæl is not directed at children under 13 and does not knowingly collect data from children.

## Changes to this policy

If this policy changes, the updated version will be published at this URL with a revised date.

## Contact

Questions about this policy or requests about your data: **hello@hael.app**
