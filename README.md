# Evergreen mating calculator

Evergreen internal. Not for anyone outside Evergreen.

Ranks every stallion standing in 2026 for a chosen mare by likely Karaka 2029 yearling price, value against the fee,
chance of selling and racing outlook, with a full profile of each mare (pedigree, foals, siblings, family as printed).
The sale companion tab (open it directly with #sale on the address) replays the 2026 Karaka Book 1: every lot's
expected price, racing score and family news as at the eve of the sale, a shortlist with notes, then the results.

The site is one static page (`index.html`) with all its data inside. There is nothing to build: Vercel serves the
file as it is. The page is rebuilt from the analysis scripts and pushed here; edit the scripts, not this file.

Keep Vercel Authentication on for all deployments. The page holds Evergreen's analysis and data drawn from NZB,
Inglis, Magic Millions, Gavelhouse and TTR AusNZ, whose terms limit use outside Evergreen.
