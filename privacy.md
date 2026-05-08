<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Privacy Policy — Tenkt</title>
<style>
  body { font-family: -apple-system, system-ui, sans-serif; max-width: 720px; margin: 40px auto; padding: 0 20px; line-height: 1.6; color: #1a1a1a; }
  h1 { font-size: 28px; }
  h2 { font-size: 20px; margin-top: 32px; }
  h3 { font-size: 16px; margin-top: 20px; }
  ul { padding-left: 22px; }
  .updated { color: #666; font-style: italic; }
  code { background: #f4f4f4; padding: 1px 5px; border-radius: 3px; }
</style>
</head>
<body>

<h1>Privacy Policy for Tenkt</h1>
<p class="updated"><strong>Last updated: 5/8/2026</strong></p>

<p>This policy describes how Tenkt handles information in its iOS application. Most features work entirely offline, and we do not run our own servers or analytics.</p>

<h2>1. Information We Collect</h2>

<h3>1.1 Locally on your device (never sent to us)</h3>
<ul>
  <li>Puzzle progress, completion times, streaks, and statistics</li>
  <li>App preferences (theme, language, sound, haptics)</li>
  <li>In-progress puzzles for resuming after crashes</li>
  <li>In-app currency balance ("traces"), unlocked marks, and quest progress</li>
</ul>
<p>Data remains in iOS storage only and is deleted when the app is removed.</p>

<h3>1.2 Anonymous global leaderboard (Apple iCloud / CloudKit)</h3>
<p>Upon completing daily puzzle sets, the app transmits to Apple's CloudKit public database:</p>
<ul>
  <li>Anonymous identifier from your iCloud account</li>
  <li>UTC date string of the puzzle (<code>seedID</code>)</li>
  <li>Total completion time in seconds</li>
</ul>
<p>This data is used solely to compute and display the global leaderboard. Players see anonymized identifiers like "Player A3F4," not real names. Users can sign out of iCloud in iOS Settings to disable this feature.</p>

<h3>1.3 Advertising (Google AdMob)</h3>
<p>AdMob may collect device advertising identifier (IDFA), ad performance data, and diagnostic information for ad delivery. The app shows three ad formats: banner ads, interstitial ads between sessions, and optional rewarded ads (which users actively choose to watch in exchange for in-app currency). All three follow the same AdMob data practices.</p>
<p>Declining the App Tracking Transparency prompt results in non-personalized ads only. Users can purchase "Remove ads" or the "Pro Bundle" to disable all AdMob ads entirely.</p>

<h3>1.4 Purchases (Apple StoreKit)</h3>
<p>Apple processes the following in-app purchases through StoreKit:</p>
<ul>
  <li><strong>Remove ads</strong> (one-time, kr 29) — disables advertising</li>
  <li><strong>Daily 2×</strong> (one-time, kr 19) — doubles daily trace earnings</li>
  <li><strong>Pro Bundle</strong> (one-time, kr 39) — combines both above</li>
  <li><strong>Trace bundles</strong> (consumable, kr 19 / 49 / 99) — purchase 500 / 1500 / 3500 in-app currency ("traces")</li>
</ul>
<p>The developer receives transaction records (product ID, purchase date, transaction ID) to verify purchases and unlock features. Payment details (credit card, Apple ID password) remain with Apple — the developer never sees them.</p>

<h2>2. Information We Do NOT Collect</h2>
<p>Tenkt does not:</p>
<ul>
  <li>Run proprietary servers or backend infrastructure</li>
  <li>Use analytics services beyond AdMob</li>
  <li>Collect names, emails, phone numbers, or contact details</li>
  <li>Access cameras, microphones, contacts, or location data</li>
  <li>Send marketing communications</li>
  <li>Sell user data</li>
</ul>

<h2>3. Push Notifications</h2>
<p>If you enable notifications, Tenkt schedules local reminders on-device only — daily nudges, streak-protection alerts, and rank updates after a top-100 finish. Remote push notifications are not sent. Users can disable notifications in iOS Settings.</p>

<h2>4. Children's Privacy</h2>
<p>Tenkt does not knowingly collect personal information from children under 13. The app is rated 4+ with no chat features, user profiles, or inter-user communication. AdMob serves family-safe ads per Google's policies.</p>

<h2>5. Your Rights (GDPR / CCPA)</h2>
<p>Users in the EEA, UK, or California have rights to:</p>
<ul>
  <li><strong>Access:</strong> Request data held about them</li>
  <li><strong>Deletion:</strong> Request leaderboard record removal via email</li>
  <li><strong>Withdraw consent:</strong> Disable App Tracking Transparency in iOS Settings or purchase ad removal</li>
</ul>

<h2>6. Data Retention</h2>
<ul>
  <li>Local data: retained until app deletion</li>
  <li>CloudKit leaderboard records: retained indefinitely for historical leaderboards; users can request deletion</li>
  <li>AdMob data: retained per Google policies (typically 14 months for identified data)</li>
</ul>

<h2>7. Changes to This Policy</h2>
<p>Updates will be reflected in the "Last updated" date. Significant changes appear in release notes.</p>

<h2>8. Contact</h2>
<p>
  <strong>Email:</strong> jonasbjh@gmail.com<br>
  <strong>Developer:</strong> Jonas Haug<br>
  <strong>Address:</strong> Konvallveien 20a, Drammen, Norway
</p>

</body>
</html>
