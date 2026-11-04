# Privacy policy update for Play Games (1.0.0), 2026-11-04

Owner approved 2026-11-04. File changed: `privacy/index.html` (EN + ES, the languages the page already has).

## Changes (both languages)
- "Last updated" -> 4 November 2026 / 4 de noviembre de 2026.
- NEW section "Google Play Games (optional, Android)": player ID / gamer profile, achievements + incremental progress,
  leaderboard best times (visible to other players per profile settings), cloud save (Saved Games: progress JSON incl. the cat's name).
  Purpose, stored by Google under the player's account, Google Privacy Policy link, deletion (Play Games app / myaccount, uninstall, contact email).
- Short version: no accounts of our own, never location/contacts; progress also backed up to Google if signed in; data not sold,
  shared only with SDK providers (Google), encrypted in transit.
- Removed the "Copying your save" paragraph (COPY MY SAVE / PASTE A SAVE are gone in the game, dev/play-games-cloud).
- "Not sent to anyone" for local data now says "unless you sign in with Play Games".
- AdMob: added the Settings > MORE > PRIVACY CHOICES entry (UMP). The data list was plain "- " text in a `<p>` (ran together
  on one line); now a real `<ul>`.
- Purchases: added that the Android rating window is Google Play's in-app review (`com.google.play.review` is in the game).
- Your rights: mentions Play Games data held by Google.

## Verified against the game (origin/dev/play-games-cloud)
docs/PLAY_GAMES.md, docs/play-games-cloud/NOTES.md (12 permissions, no location/Bluetooth/Wi-Fi), docs/release/DATA_SAFETY.md,
Packages/manifest.json (no Firebase / analytics / crash SDK; Unity Services off).

## Flags (not changed)
- The page mentions iOS / App Store; 1.0.0 is Android (iOS release is on the roadmap). Left as is.
- The game has 6 languages now (DE/FR/IT/PT-BR too) but the policy has only EN + ES; kept as instructed.
- docs/release/DATA_SAFETY.md says the Play Games answers must be added to the Play Data safety form too.
