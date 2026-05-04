# Privacy Policy for Tenkt

**Last updated: 4/5/2026

This Privacy Policy describes how Tenkt ("we", "us", "the app") handles
information when you use our iOS application. We are committed to keeping
the app private by default — most features work entirely offline, and we
do not run our own servers or analytics.

## 1. Information We Collect

Tenkt itself collects very little. The data flows are:

### 1.1 Locally on your device (never sent to us)
- Your puzzle progress, completion times, streaks, and statistics
- Your app preferences (theme, language, sound, haptics)
- Your in-progress puzzles (so the app can resume after a crash or
  restart)

This data lives in iOS storage on your device only. It is never uploaded
to any server we control. If you delete the app, this data is gone.

### 1.2 Anonymous global leaderboard (Apple iCloud / CloudKit)
When you complete a daily puzzle set, the app sends the following to
Apple's CloudKit public database:
- An anonymous identifier provided by your iCloud account
  (`CKContainer.userRecordID` — we never see your Apple ID, name, or
  email)
- The UTC date string of the puzzle ("seedID")
- Your total completion time in seconds

This data is used solely to compute and display the global leaderboard.
We never link it to your name, email, or any other personal information.
Other players see only an anonymized identifier (e.g. "Player A3F4"), not
your real name.

CloudKit is operated by Apple under their own privacy terms. You can
sign out of iCloud at any time in iOS Settings to stop this data flow,
but the app will still work without leaderboard features.

### 1.3 Advertising (Google AdMob)
Tenkt is free and supported by ads from Google AdMob. AdMob may collect:
- Your device's advertising identifier (IDFA), if you grant permission
  via the App Tracking Transparency prompt
- Standard advertising signals (ad views, clicks, ad performance)
- Diagnostic data needed to deliver ads (device model, OS version,
  approximate IP-based location, language)

If you decline the App Tracking Transparency prompt, AdMob will only
serve non-personalized ads.

You can permanently remove all ads with a one-time in-app purchase
("Remove ads"). After this purchase, AdMob is fully disabled.

For details on how Google handles this data, see Google's Privacy Policy
at https://policies.google.com/privacy.

### 1.4 Purchases (Apple StoreKit)
If you make the "Remove ads" purchase, Apple processes the transaction
through StoreKit. We receive a transaction record (product ID, purchase
date, transaction ID) so we can verify your purchase and disable ads.
We do not see your payment method, name, or address — Apple handles all
billing.

## 2. Information We Do NOT Collect

We want to be specific about what we do *not* do:
- We do not run our own servers or backend
- We do not use any analytics service (no Firebase Analytics, no Mixpanel,
  no third-party tracking SDKs other than AdMob)
- We do not collect your name, email address, phone number, or contact
  information
- We do not access your camera, microphone, contacts, or location
- We do not send marketing emails or push marketing notifications
- We do not sell your data to anyone

## 3. Push Notifications

Tenkt may send local notifications (a daily reminder at 06:00 if you
enable it). These are scheduled entirely on your device — we have no
push server and never send remote pushes. You can disable notifications
at any time in iOS Settings.

## 4. Children's Privacy

Tenkt does not knowingly collect personal information from children
under 13. The app is rated 4+ and contains no chat features, no user
profiles, and no way for users to communicate with one another. The
ads served by AdMob are subject to Google's family-safe ad policies.

## 5. Your Rights (GDPR / CCPA)

If you are in the European Economic Area, the United Kingdom, or
California, you have the following rights regarding personal data
processed about you:

- **Access**: You can request a copy of any data we hold about you. In
  practice, we hold no personal data — only an anonymous identifier
  tied to your iCloud account.
- **Deletion**: You can delete your leaderboard records by emailing us
  at [SUPPORT EMAIL]. Provide the approximate dates of your submissions
  so we can locate them.
- **Withdraw consent for tracking**: You can disable App Tracking
  Transparency at any time in iOS Settings → Privacy & Security →
  Tracking, or remove all ads via the in-app "Remove ads" purchase.

## 6. Data Retention

- Local data: stays on your device until you delete the app
- CloudKit leaderboard records: retained indefinitely to support
  historical leaderboards. You can request deletion (see Section 5).
- AdMob data: retained per Google's policies (typically 14 months for
  identified data)

## 7. Changes to This Policy

We may update this policy as the app evolves. The "Last updated" date
at the top will reflect any changes. Significant changes will be
announced in the app's release notes.

## 8. Contact

For privacy questions or to exercise your rights, contact us at:

**Email:** jonasbjh@gmail.com
**Developer:** Jonas Haug
**Address:** Konvallveien 20a, Drammen
