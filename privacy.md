# Privacy Policy

**hæl** — last updated June 2, 2026

---

## What hæl collects

hæl stores fasting history, body weight entries, menstrual cycle dates, streak counts, and user preferences. All data is stored locally on the device using UserDefaults and App Group shared storage. No data is transmitted to any server, cloud service, or third party.

## HealthKit

With permission, hæl reads and writes the following HealthKit data types:

- **Menstrual flow** — used to determine cycle phase and provide cycle-aware fasting context.
- **Body mass** — used to track weight entries and surface trends in the body ledger.
- **Workouts** — used to log completed fasts as mindfulness sessions.

HealthKit data is accessed only when the user grants permission through the standard iOS authorization prompt. hæl does not access HealthKit data for advertising, marketing, or any purpose beyond the core functionality described above. HealthKit data is never shared with third parties.

## Notifications

hæl may schedule local notifications (morning nudges, fast completion reminders) if the user enables them. Notifications are scheduled entirely on-device. No notification tokens or identifiers are sent to any server.

## Purchases

hæl offers a one-time in-app purchase processed entirely through Apple's StoreKit framework. Purchase verification happens on-device against Apple's signed transaction receipts. No payment information is collected or stored by hæl. Purchase status is cached locally to unlock features.

## No accounts, no server, no tracking

hæl does not require an account. There is no server. There is no analytics SDK. There are no advertising identifiers. There are no third-party SDKs that collect data. The app does not track users across apps or websites.

## Data storage

All data resides on the device in:

- **UserDefaults** (App Group `group.com.hael.fasting`) — fasting sessions, preferences, cycle dates, weight history, purchase status.
- **HealthKit** — menstrual flow, body mass, and workout samples (managed by iOS, subject to the user's HealthKit privacy settings).

hæl does not use iCloud sync, CloudKit, or any remote database.

## Data deletion

Deleting the app removes all locally stored data. HealthKit data persists in the Health app and can be managed through iOS Settings > Health > Data Access & Devices.

## Children

hæl is not directed at children under 13 and does not knowingly collect data from children.

## Changes to this policy

If this policy changes, the updated version will be published at this URL with a revised date. Continued use of the app after changes constitutes acceptance.

## Contact

For questions about this policy, contact: **hello@ki-gen.studio**
