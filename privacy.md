# Focus Tap Privacy Policy

**Public developer/publisher brand:** CCMF Interactive  
**Privacy and customer-support contact:** [ccmfllc1926@gmail.com](mailto:ccmfllc1926@gmail.com)  
**Effective date:** November 4, 2026

## 1. Scope

This Privacy Policy describes the Focus Tap Android game and the data
practices enabled in the published Billing-only version. Focus Tap does not
require a player account and is not specifically directed to children. The
approved audience is general audience.

## 2. Information Focus Tap stores on the device

Focus Tap stores a local save file in app-private device storage. Depending on
how the player uses the app, it can contain a locally generated anonymous
player identifier and player-selected display name; scores, run summaries,
accuracy and combo records, Campaign and Daily progress, stars, achievements,
mastery and progression, Collection state, earned local rewards; settings and
local preferences; an analytics-consent choice; and local Full Game entitlement
metadata. This save supports gameplay, progression, profile presentation,
local leaderboard-style views, preferences, and entitlement state. It is not an
online account or a Focus Tap cloud profile. Focus Tap does not send this local
save or its gameplay/profile fields to a Focus Tap server.

## 3. What Focus Tap transmits

The published Billing-only version can communicate with Google Play through
Google Play Billing. The Billing Library connects and checks the product
catalog and existing purchase ownership automatically after the app starts and
after a Billing service reconnection, when the service and network are
available. These checks can happen without the player opening the purchase
screen or starting a new purchase. Focus Tap does not transmit its local player
identifier, display name, gameplay/progression data, Collection data, settings,
consent choice, or local entitlement metadata to a Focus Tap server.

The Google Play Billing Library also automatically sends diagnostic events to
Google through Google's transport service when those events occur. They can
include billing API operation and result/error information, app/package and
library versions, Android version/build and device model, locale, time zone,
network type, and mobile operator codes. Google receives this information for
diagnostics and service reliability. Focus Tap does not offer a control to
disable these SDK diagnostic transmissions.

For billing operations, the library uses a random `billingClientSessionId`
correlation value generated for a BillingClient instance and reused across
operations handled by that instance. The value is sent with purchase
acknowledgement data to correlate the operation. Focus Tap does not save it in
its local save or associate it with the local player identifier or display
name.

There is no active Focus Tap production Firebase Auth/Firestore service,
online leaderboard submission, analytics provider, advertising provider, or
crash-reporting provider in this release.

## 4. Google Play Billing and Full Game Unlock

Focus Tap offers the one-time, non-consumable `full_game_unlock` product.
Google Play processes the payment and related purchase records under its own
services and policies. Payment-card, bank-account, and other payment-instrument
details are handled by Google Play; Focus Tap does not receive those details.

When a purchase is made, the Billing Library provides Focus Tap with purchase
information needed to grant and acknowledge the product, including the product
identifier, purchase state, and purchase token. Focus Tap uses the token to
acknowledge the purchase through Google Play. The raw token is held transiently
for that operation and is not persisted in Focus Tap's local save. The local
save stores entitlement metadata only. Google Play ownership checks also run
automatically at startup and after a Billing service reconnection, as described
in Section 3.

Focus Tap does not send purchase tokens to a Focus Tap server and does not
claim to delete Google Play purchase or diagnostic records. Google Play's
retention and deletion practices are governed by Google's own services and
policies; Focus Tap does not control their retention period.

## 5. Permissions and platform services

The published Android app uses Internet access and network-state information
for Google Play Billing and its automatic catalog and ownership checks. It
does not request contacts, location, camera, microphone, storage, phone, SMS,
Bluetooth, notification, or advertising-ID permissions in this release.

## 6. Retention and deletion

The local save is stored in app-private device storage. When the app is closed
or backgrounded, saved values remain and are loaded on the next launch. An
in-place update normally preserves app-private data. Clearing Android app data
removes the local save; uninstalling normally removes the app's local data. A
later launch or reinstall starts with fresh local state. The local save is not
a Focus Tap cloud backup.

Focus Tap has no online player accounts, Focus Tap cloud saves, or app-level
account-deletion workflow in this release. Android app-data and uninstall
controls remove local Focus Tap data. They do not delete records or diagnostics
held by Google Play. Focus Tap does not control Google's retention period or
promise deletion of Google's records. The privacy contact is for questions; it
does not provide a deletion-request service for Google Play records or
diagnostics.

## 7. Children's privacy and audience

Focus Tap launches as a general-audience game and is not specifically directed
to children. It is not opting into a child-directed/Families posture in this
release.

## 8. Security and policy changes

Google Play Billing operations and Billing Library diagnostics use encrypted
network transport. CCMF Interactive uses reasonable safeguards
appropriate to the app and services actually enabled. No device, operating
system, or third-party platform can be promised to be risk-free.

If Firebase, online accounts, online leaderboards, analytics, ads, or other
providers are enabled later, this policy will be reviewed and updated before
that release. CCMF Interactive may update this policy when the app, services,
or legal requirements change. The effective date above will be updated when
this policy is published or revised.

## 9. Contact

For privacy questions, contact CCMF Interactive at:

**[ccmfllc1926@gmail.com](mailto:ccmfllc1926@gmail.com)**
