# Evergreen mating calculator

Evergreen internal. Not for anyone outside Evergreen.

Ranks every stallion standing in 2026 for a chosen mare by likely Karaka 2029 yearling price, value against the fee,
chance of selling and racing outlook, with a full profile of each mare (pedigree, foals, siblings, family as printed).
The sale companion tab (open it directly with #sale on the address) replays the 2026 Karaka Book 1: every lot's
expected price, racing score and family news as at the eve of the sale, a shortlist with notes, then the results.
The fillies tab (#fillies) scores every filly and mare racing in NZ or Australia as a broodmare prospect.
The farm analytics tab (#farm) breaks down each NZB vendor's yearling draft since 2016: where its value came from and
where it leaked, price in the ring, book placement, foaling dates, the broodmare band and who buys.
The race ratings tab (#ratings) rates every NZ and Australian run since January 2023 on a TopRate-style scale, with
search by horse, meetings by day and the top-rated horses now.

The site is one static page (`index.html`) with all its data inside, except the race ratings, which are too big for the
page and sit in `ratings/` beside it (fetched when that tab opens). There is nothing to build: Vercel serves the files
as they are. The page is rebuilt from the analysis scripts and pushed here; edit the scripts, not these files.

Keep Vercel Authentication on for all deployments. The page holds Evergreen's analysis and data drawn from NZB,
Inglis, Magic Millions, Gavelhouse, TTR AusNZ, TAB race results and Betfair, whose terms limit use outside Evergreen.
