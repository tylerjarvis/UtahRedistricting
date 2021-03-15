# UtahRedistricting

This repository has data used for analysis of redistricting in Utah, including
* Precinct-level election returns for the 2010 Senate race (Lee v Granato) and the special gubernatorial election (Herbert v Corroon).
* Shapefiles for the 2012 voting precincts.  These have been cleaned to remove some gaps and overlaps.  Precincts that were fully contained within another precinct have been merged with the larger precinct, since every contiguous district must have both or neither of the inner (contained) precinct and the outer (containing) precinct.  Precincts that were disconnected were merged with their neighbor to ensure that all precincts are connected.


