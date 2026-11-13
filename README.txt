MIDNIGHT 2.0 — Productivity Quests

FILES
- index.html: app interface and logic
- manifest.webmanifest: installable app details
- sw.js: offline app shell and update cache
- icons/: app icons

DEPLOYMENT
Upload/replace the files in the existing GitHub Pages repository. Keep the icons folder and its two PNG files. GitHub Pages should remain configured for main / (root).

DATA & UPGRADE
The app keeps the existing localStorage key midnight-points-v1, so the current balance and transaction history from MIDNIGHT 1.0 are retained on the same browser/device. Quest progress uses a separate local key. Do not clear browser/site data during the upgrade. Export a backup first from Settings.

POINTS
- Manual Add Points requires a description.
- Quest sessions award 1 point for each complete minute of running timer time.
- Paused time is not counted. A session must run for at least one full minute to earn points.
- Finish a session to receive its points. Quest sessions are recorded in activity history.
- Daily random quest is selected from all 10 fixed quests and remains the same for that local calendar day.
- Streak counts consecutive calendar days with at least one completed quest session.

PRIVACY
All data is stored locally in the browser on this device. It is not synced between devices or shared with other people. Export backups regularly.
