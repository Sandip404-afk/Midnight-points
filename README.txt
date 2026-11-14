MIDNIGHT 2.1

What's new:
- Four separate app sections: Home, Quests, Stats, Settings.
- Quest Board moved to its own page.
- Required descriptions for both adding and redeeming points.
- Redemption descriptions are saved in transaction history.
- One active quest at a time, with an abandon option.
- Each quest attempt expires 24 hours after it is started. Expired attempts award no points and can be retried.
- Theme choices: Midnight, Galaxy, Ocean, Forest, and Light.
- Theme choice is saved on the current device/browser.
- Existing points and quest storage keys are retained for compatibility.

GitHub Pages update:
1. Extract this ZIP.
2. In your existing midnight-points GitHub repository, upload/replace the files in the repository root.
3. Keep the icons folder and replace its two PNGs only if you intend to update the icons (these are included unchanged here).
4. Commit the changes to the main branch.
5. Open the installed app while online and refresh/reopen it after the update deploys. The service worker cache version has been updated to v4.

Important:
- Your existing local points and quest data are stored in this browser on this device. The update keeps the same localStorage keys and does not intentionally reset them.
- Export a backup from Settings before updating, as a precaution.
- Each quest attempt has a 24-hour deadline measured from when it is first started. Pausing the productivity timer does not pause the deadline.
- Only completed full productive minutes are credited when you finish a quest session before expiry.
