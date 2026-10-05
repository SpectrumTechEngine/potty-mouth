# PottyMouthPocket

The swear jar with a difference. Catch your friends swearing, they accept or dispute (the group votes), and at the end of the round the cleanest mouth collects the jar.

Live at https://thespectrumtechengine.com/potty-mouth/

## How it works
- Start a jar, choose what's at stake (money, a forfeit, or bragging rights), and share the invite link or 6-letter code.
- Heard a swear? Tap **I heard a swear!**, pick who and how bad.
- They accept, or dispute it and the rest of the group votes (in a 2-person jar, the accuser stands by it or withdraws it).
- When the round ends, the cleanest mouth wins and you can share the result picture.

The app never takes or holds money. It only keeps score; groups pay outside the app (a shared wallet, cash, or settle up at the end).

## Files
- `index.html`: the whole app.
- `firestore.rules`: who can read and change what in the online storage (paste into Firebase, Firestore, Rules).
- `manifest.webmanifest`, `sw.js`, `icon-*.png`: let it install as an app and open offline.

Away from the website (or before `FIREBASE_CONFIG` is set) it runs as a practice copy kept on the device, with pretend friends to try it out.

Created by The Spectrum Tech Engine. Contact: support@thespectrumtechengine.com, privacy@thespectrumtechengine.com
