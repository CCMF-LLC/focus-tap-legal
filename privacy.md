# Focus Tap Privacy Policy

**Public brand:** Onnique Studios
**Operator:** Onnique Studios, operated by a sole proprietor in Jamaica
**Contact:** aethrion.collective@outlook.com
**Effective date:** September 26, 2026

## 1. Scope

This Privacy Policy describes the Focus Tap Android game and the data
practices enabled in its current V1 configuration. Focus Tap does not require
a player account and is not specifically directed to children. The approved
audience is general audience.

## 2. Information Focus Tap stores on the device

Focus Tap creates a local save file on the device. Depending on how the player
uses the app, it can contain:

- a locally generated anonymous player identifier and player-selected display
  name;
- scores, run summaries, accuracy/combo records, Campaign and Daily progress,
  stars, achievements, mastery/progression, Collection state, and earned local
  rewards;
- settings such as music, sound, haptics, reduced motion, and other local
  preferences; and
- the analytics-consent choice and local Full Game entitlement metadata.

This local save supports gameplay, progression, profile presentation, local
leaderboard-style views, accessibility preferences, and entitlement state. It
is not an online account and is not a Focus Tap cloud profile.

## 3. What Focus Tap transmits

In the current V1 configuration, Focus Tap does not transmit the local player
ID, display name, gameplay/progression data, Collection data, settings,
consent state, or local entitlement metadata to Focus Tap servers.

Android, Google Play, and other platform services may communicate with a
device. Google Play Billing may communicate with Google Play when a purchase,
catalog, or ownership operation is available and exercised. Those platform
operations are separate from Focus Tap transmitting local gameplay data to its
own server.

There is no active Focus Tap production Firebase Auth/Firestore service,
online leaderboard submission, analytics provider, advertising provider, or
crash-reporting provider in the current V1 release.

## 4. Google Play Billing and Full Game Unlock

The Android package includes a Google Play Billing bridge for the planned
one-time, non-consumable `full_game_unlock` product. Scene 1 is free; Scenes
2–11 are intended to require the Full Game Unlock. Seasonal Event
participation is intended to be free for all players.

Google Play processes purchase, product metadata, ownership, and payment
records under its own services and policies. The local save stores entitlement
metadata reported by the bridge. Raw purchase tokens are not persisted by
Focus Tap's save layer.

Play Console product and test-track verification, real purchase,
acknowledgement, restore/re-query, pending/cancel/error, refund, reinstall
recovery, and any trusted server-side verification are separate release
steps. Focus Tap does not claim to delete Google Play transaction records.

## 5. Permissions and platform services

The app uses Internet access for provider-ready services, vibration for haptic
feedback, Google Play Billing for the Full Game Unlock, and network-state
availability checks for the Billing integration.

Focus Tap does not request contacts, location, camera, microphone, storage,
phone, SMS, Bluetooth, notification, or advertising-ID permissions in the
current release.

## 6. Retention and deletion

The local save is stored in app-private device storage.

- When the app is closed or backgrounded, saved values remain and are loaded on
  the next launch. Closing does not intentionally delete data.
- When the app is updated in place, Focus Tap does not reset the save. Android
  normally preserves app-private data for an update of the same package and
  signing identity.
- Uninstalling the app normally removes its app-private local save. Focus Tap
  has no server-side deletion callback in V1.
- Clearing Android app data removes the local save. The next launch creates a
  new anonymous local identity and default state.
- Reinstalling after local data removal starts as a fresh local installation.
  Local save data is not a cloud backup. Any entitlement recovery depends on
  Google Play ownership re-query after the Billing path is configured and
  verified.

Focus Tap currently provides no online account-deletion workflow because V1
does not create player accounts or cloud saves. Android app-data and uninstall
controls remove local Focus Tap data. They do not delete Google Play records or
platform-level data.

## 7. Children's privacy and audience

Focus Tap launches as a general-audience game and is not specifically directed
to children. It is not opting into a child-directed/Families posture in V1.

## 8. Security and policy changes

Onnique Studios uses reasonable safeguards appropriate to the app and services
actually enabled. No device, operating system, or third-party platform can be
promised to be risk-free.

If Firebase, online accounts, online leaderboards, analytics, ads, or other
providers are enabled later, this policy will be reviewed and updated before
that release.

Onnique Studios may update this policy when the app, services, or legal
requirements change. The effective date above will be updated when this policy
is published or revised.

## 9. Contact

For privacy or support questions, contact:

**aethrion.collective@outlook.com**
