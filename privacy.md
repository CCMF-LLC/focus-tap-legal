# Focus Tap Privacy Policy

**Public-facing publisher/operator:** CCMF Interactive (an unregistered public-facing name)

**Privacy and support contact:** [ccmfllc1926@gmail.com](mailto:ccmfllc1926@gmail.com)

**Last revised:** November 7, 2026

**Scope:** Focus Tap Beta 0.2.0, Android package `com.aethrion.focustap`.

## Scope

This policy covers Focus Tap, Android package `com.aethrion.focustap`. The game does not require a Focus Tap account. It provides local gameplay across 12 worlds, Daily and Rush modes, seasonal adventures and a personal Event Vault. Worlds 1–2 are free; Full Game Unlock opens Worlds 3–12 and eligible event Stages 2–3 after prior-stage completion. Active event Stage 1, previews and personal Vault history are free. These access rules do not mean that premium purchase or advertising SDKs are absent from the app.

## Data stored on your device

The app stores a save in its private device storage: a randomly generated local player ID; your selected name/avatar; gameplay, worlds, scores, stars, collections, event stages/history, achievements and rewards; coins, helpers and lives; purchase entitlements and a purchase-reward ledger; and preferences such as music, sound, vibration, reduced motion and reminders. A local analytics preference may also be stored.

For purchase duplicate protection, the ledger stores a shortened SHA-256-derived purchase-token key. Raw purchase tokens are handled temporarily for purchase processing, acknowledgement and consumption, rather than saved in the gameplay save. A derived token key is still purchase-related data; it is not a promise of anonymity.

This version does not send the local save to a Focus Tap server, create a Focus Tap cloud account, submit online leaderboard scores, or enable a separate Focus Tap analytics or crash-reporting provider. This statement does not cover the Google SDK communications described below. An in-app analytics preference does not disable those separate SDK communications.

## Google Play Billing

The app includes Google Play Billing Library 9.1.0. It connects to Google Play and checks available products and ownership at startup and when its billing connection is established again. You do not have to open the Shop for these checks to occur.

Products include Full Game Unlock, Starter Bundle, four coin packs and the Magic Objects Avatar Pack. Google Play processes payments under its own terms and policies. The app receives product, purchase-state and purchase-token information needed to grant rewards, acknowledge purchases, consume repeatable coin-pack purchases and restore eligible ownership. The app does not receive your card or bank-account details or send purchase tokens to a Focus Tap backend.

Billing SDK code also supports operational diagnostic reporting to Google through Google's data transport service. Technical information relating to the app, device, billing operations and errors may be processed for service operation, reliability and fraud prevention. This app has no separate switch for Billing SDK diagnostics. Google controls its own purchase and diagnostic retention.

## Google consent and advertising SDKs

This version includes Google Mobile Ads SDK 25.5.0 and User Messaging Platform (UMP) 4.0.0. Its ordinary release gameplay disables both rewarded and interstitial ad requests; purchasing Full Game is not required to avoid forced gameplay ads in this build. This does not disable SDK startup communication.

At startup the app asks UMP to update consent information. UMP's network request can include app/package and SDK versions, device model/Android version, language, screen information and stored consent-related values. Google also receives the connection's IP address. UMP may show a privacy message when required. The app can initialize Mobile Ads when UMP says ads may be requested, even though this build's gameplay ad requests remain disabled.

Google's Mobile Ads disclosure describes automatic processing of IP address, app interactions, diagnostic information and device/account identifiers, including advertising ID and app-set ID, for advertising, analytics and fraud prevention. IP address can support approximate location. The exact values and processing depend on SDK execution, consent, device settings and availability; a manifest permission alone does not establish that a particular identifier was sent. Google is a third-party recipient of SDK data and its use is governed by its policies. This app does not supply the local player name or save as advertising targeting data.

When Google requires a privacy-options entry point, use **Settings → Privacy choices** to review available choices. Resetting or deleting the advertising ID in Android settings affects that identifier, not every SDK communication. Offline play remains available; network-dependent services may be unavailable. Google's disclosures: [Mobile Ads data handling](https://developers.google.com/admob/android/privacy/play-data-disclosure), [Google Privacy Policy](https://policies.google.com/privacy).

## Optional reminders and sharing

Reminders are scheduled locally using Android alarms and notifications for the daily gift, full lives and streak. On Android 13 or later, displaying notifications requires your permission. Turn reminders off in Settings or use Android notification controls. Reminder scheduling does not upload your save to a Focus Tap server.

When you choose Share, the app creates a result image locally, copies it to its private cache and opens Android's share sheet. It grants the app you select access to the shared image/text. Focus Tap does not automatically post it. The receiving app handles anything you choose to send under its own policies.

## Permissions and platform components

Internet/network access supports Google services. Billing permission supports purchases; vibration supports optional tap feedback; notification permission supports reminders. The merged SDK manifest also includes advertising ID, Android AdServices ID/attribution/topics, wake-lock and foreground-service permissions. These allow platform/SDK functions and do not establish that every capability is exercised. The app does not declare camera, microphone, contacts, phone/SMS, precise/coarse device-location, or broad storage/media-reading permissions. IP-derived approximate location is distinct from device-location permission.

## Retention and deletion

The save remains on the device between sessions. Clearing Android app data removes local progress and rewards; uninstalling normally removes app-private data. Updates normally preserve local data. There is no Focus Tap cloud backup. Consumed coins, spent helpers, local rewards and local progress are not promised to return after data loss; eligible non-consumable ownership can be re-queried from Google Play.

Google keeps its own purchase, SDK and consent records under its policies. Clearing Focus Tap data does not delete those records. We do not promise a specific Google retention period or a deletion service for Google's records. Contact **ccmfllc1926@gmail.com** with questions about our handling; use Google's controls and policies for Google-held information.

## Security and audience

Google SDK services use encrypted network transport. Local app-private storage and platform safeguards reduce risk but do not guarantee security. Focus Tap is intended for a general audience and is not specifically directed to children. It is not represented as enrolled in Google's Families program. Any future change to the audience, providers or data handling requires review of this policy.

## Contact and changes

This policy is provided under the public-facing publisher/operator name **CCMF Interactive**. The name is currently unregistered; no incorporated or registered-entity status is claimed. Privacy and support questions: **ccmfllc1926@gmail.com**. We will update this policy and its effective date when practices change.
