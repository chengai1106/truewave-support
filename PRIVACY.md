# TrueWave Privacy Policy

Last updated: November 23, 2026

TrueWave does not collect, sell, or share personal data. There are no user accounts, no sign-up, no advertising, and no cross-app tracking.

## Data we collect (anonymous product interaction)

TrueWave synthesizes audio locally on your device in real time and contains no third-party analytics or advertising SDKs.

To understand which presets and instrument controls are useful and to improve the app, TrueWave sends minimal anonymous product interaction events (such as app opens, preset session starts and durations, custom generator adjustments, and purchase-flow status) over HTTPS to our EU-hosted analytics service (PostHog EU) using a random app-scoped identifier generated locally on your device. If you listen offline or in Airplane Mode, events may be queued locally in app storage and sent when a connection becomes available.

This anonymous interaction data is:
- **Not linked to your identity** (no name, email address, Apple ID, or contact information is collected)
- **Never used for tracking** across apps or websites (`NSPrivacyTracking = false`)
- **Never sold or shared** with advertisers or data brokers

## Data stored on your device

TrueWave stores your unlock status cache, review-prompt eligibility counters, and random app-scoped analytics identifier in local app preferences (`UserDefaults`, declared under Apple Required Reason `CA92.1`), and uses on-device monotonic system uptime (`35F9.1`) to measure active playback and timer intervals accurately. Deleting the app removes local app storage.

## Apple services

When you purchase or restore the one-time unlock, Apple processes the transaction through StoreKit and the App Store. TrueWave never sees your payment details and receives only the entitlement status needed to unlock features. Apple's handling of purchase and account information is governed by Apple's privacy policy.

When you choose to rate the app, TrueWave uses Apple's native App Store review interface.

## Changes

If TrueWave's privacy practices change, this policy and the App Store privacy disclosure will be updated before the change takes effect.

## Contact

For privacy questions, [open a support request](https://github.com/chengai1106/truewave-support/issues/new). Do not include passwords, payment details, or other sensitive information.
