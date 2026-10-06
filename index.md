---
layout: default
---
# WorkReset AI — Privacy Policy

*Last updated: 2026-09-25 (pre-release). This is the source text for the page
you will host; replace the placeholder contact email before publishing.*

WorkReset AI is a calm movement assistant for your workday. It runs entirely
on your phone. This policy explains, in plain language, what the app stores,
what it never does, and the few third parties involved.

## What WorkReset AI stores

All of the following lives in **local storage on your device only**:

- Your work schedule and work-hour settings
- Your movement/break (reset) sessions and their history
- Reminder and reset interaction history
- Your preferences (theme, notification settings, personalized suggestions)

None of it is ever uploaded to a server we operate, and none of it is
attached to ad requests.

## What WorkReset AI does NOT do

- **No accounts.** There is no sign-up, login, or user profile.
- **No servers.** There is no backend; the app is offline-first.
- **No sale of your WorkReset data.** We do not sell, rent, or share your
  work sessions, resets, or settings. (The ads SDK's own data handling is
  described separately under *Advertising* below, and is governed by Google.)
- **No health-data sharing.** Per the product spec, movement and break
  patterns are used only to personalize your suggestions locally and are
  never classified or shared as health data.

## Advertising

WorkReset AI includes the **Google Mobile Ads SDK**. It is initialized at app
start on every install, including Premium, so that ads can load immediately if
an ad is ever needed. This is the part of the app that talks to a network for
advertising, and it is worth being specific about what it does.

**What the ads SDK collects and shares.** Google states that the Mobile Ads
SDK automatically collects and shares:

- **IP address** — which Google notes may also be used to derive an approximate
  location
- **Ad and product interactions** — that you viewed, clicked, or ignored an ad
- **Diagnostic information** — device and app state used to measure ads
- **Device and account identifiers** — including the Android advertising ID
  (`com.google.android.gms.permission.AD_ID`)

This is used for advertising, analytics, and fraud prevention. You can read
Google's own disclosure here:
<https://developers.google.com/admob/android/privacy/play-data-disclosure>

**What stays out of it.** Your WorkReset records — work sessions, resets, and
settings — are never included in ad requests. The app does not read your ad
identifier for any purpose of its own.

**Your controls.** You can manage your ad privacy choices in two places:

- **In the app:** Settings → Ad privacy options, which opens Google's consent
  interface where you can change or reset your choices.
- **On your device:** reset or delete your advertising ID, and opt out of
  interest-based ads, in Android system settings.

Upgrading to Premium removes ads entirely.

## Purchases

**Google Play** processes any Premium purchase and verifies your entitlement on
launch. The payment flow happens entirely inside Google Play, so WorkReset AI
never sees or stores your payment details.

## Data safety

- Your local data is **never uploaded by WorkReset AI**. The collection
  described under *Advertising* comes from Google's ads SDK, not from us.
- Android backup and device-to-device transfer for this app are **disabled**
  with explicit `dataExtractionRules` and `fullBackupContent` rules, so your
  data is not extracted or migrated off-device. If you move to a new device,
  you simply start fresh — by design, for privacy.
- Uninstalling the app removes its local data.

## Contact

Questions about privacy? Email us at **privacy@workreset.example** (replace
with your real contact before release).
