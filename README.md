# UtahRedistricting

This repository has data used for analysis of redistricting in Utah, including
* Precinct-level election returns for the 2010 Senate race (Lee v Granato) and the special gubernatorial election (Herbert v Corroon).
* Shapefiles for the 2011 voting precincts.  These have been cleaned to remove some gaps and overlaps.  
* JSON Graph of the 2011 precincts (with rook adjacency) with population and voting data included.  This graph was built using the cleaned precinct shapefiles.  Precincts that were fully contained within another precinct have been merged with the larger precinct, since every contiguous district must have both or neither of the inner (contained) precinct and the outer (containing) precinct.  Precincts that were disconnected were merged with their neighbor to ensure that all precincts are connected.
To run MCMC chains using gerrychain(https://gerrychain.readthedocs.io/en/latest/), this graph should be sufficient.


