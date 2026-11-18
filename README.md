# Vinyl Vault

A live gallery for a Discogs record collection, in one HTML file.

**Open it:** https://nofuture2077.github.io/vinyl-vault/

Paste a Discogs collection link (`discogs.com/user/NAME/collection`) or just a username. The collection has to be public. Share a collection with `?user=NAME`.

- Each sleeve has its record peeking out. The disc is drawn from the Discogs format text: black or colored, clear, picture disc and CD, plus pressing effects (marble, splatter, color-in-color, galaxy, haze, half and half, tri-color, quad, butterfly, starburst). Effects are painted per record and seeded by the release, so every copy looks a little different.
- The detail view spins the record at 33⅓ or 45 and shows the tracklist, release date, community rating and your rating.
- Values are optional and off by default. Without a login, each record shows its lowest current marketplace listing. With a personal access token from Discogs → Settings → Developers, your own collection shows Discogs' own median value, and private collections open. The token stays in the browser.

Discogs allows 25 API requests a minute (60 with a token). The page paces itself, so pricing a big collection takes a while. Data provided by Discogs.
