# Spin Raiders website

The public pages of Spin Raiders, served by GitHub Pages at https://and-games-studio.github.io/spinraiders/

- `index.html`: home page ("Coming soon" until the game is on the stores).
- `privacy/`: privacy policy (linked from the store listings, AdMob's consent message and the game's Settings).
- `terms/`: terms of service.
- `delete/`: how to delete the data the game keeps (the Play Console data safety form links it).

Plain HTML and CSS, no build step, in the game's night blue and gold. The font is Fredoka (SIL Open Font License
1.1, in `fonts/` with its licence), served from here, so the site makes no requests to other servers.

The pages describe the game as it will ship: the game server (Nakama on Oracle Cloud), raids and the raid log,
friends and gifts, notifications through Firebase Cloud Messaging, purchases of spins and coins validated by the
server, AdMob rewarded videos with Google's consent form, GameAnalytics only with the player's opt-in, and the
statistics kept on our server. When the build changes, they change with it. Before the first store review, check
that these still hold, or change the pages:

- the server runs in an EU region of Oracle Cloud;
- server logs are kept at most 14 days;
- backups are encrypted and overwritten within 5 weeks (7 daily + 4 weekly);
- the store build really has AdMob, Unity IAP, Firebase and GameAnalytics (or the pages drop what it doesn't have);
- the age (18+, since 2026-11-16: the IARC ratings gave PEGI 18 for the simulated casino slot) matches the rating.
