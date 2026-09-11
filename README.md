# Bar music

Music for a bar that runs itself: the right playlist at the right time at the right volume, a
different one each day, volume held to a ceiling, and if someone turns it off by hand it is back on within fifteen minutes.
Runs for free on GitHub every fifteen minutes and reaches the speakers through Sonos's own service,
so nothing is installed in the building.

**Set it up with the starter pack.** `BAR_MUSIC__START_HERE.md` in this repository walks a
non-technical owner through every step, with Claude as the guide. Open it, read Part One, and do
the three steps there. That is the whole way in.

`config.json` is the only file you edit. It holds your schedule. Everything else is the program.

Secrets (your Sonos keys and the connection to your speakers) live in GitHub's Settings, under
Secrets and variables, never in this repository. `.gitignore` makes sure of it.
