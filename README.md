# Bar music

Music for a bar that runs itself: the right playlist at the right time at the right volume, a
different one each day, volume held to a ceiling, and it stays off when someone turns it off by hand.
Runs for free on GitHub every fifteen minutes and reaches the speakers through Sonos's own service,
so nothing is installed in the building.

**Set it up with the starter pack.** This repository is meant to be used alongside a guided document
called `BAR_MUSIC__START_HERE.md`, which walks a non-technical owner through every step with Claude
as the guide. If you were sent that document, follow it. If not, ask whoever gave you this link.

`config.json` is the only file you edit. It holds your schedule. Everything else is the program.

Secrets (your Sonos keys and the connection to your speakers) live in GitHub's Settings, under
Secrets and variables, never in this repository. `.gitignore` makes sure of it.
