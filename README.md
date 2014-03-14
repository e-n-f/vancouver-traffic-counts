vancouver-traffic-counts
========================

Vancouver [publishes their traffic counts](http://data.vancouver.ca/datacatalogue/trafficCounts.htm)
as a KML file of links to HTML frames that link to HTML-formatted tables of
2-hour and peak-hour vehicle turning movements and
bicycle and pedestrian crossings.

This is a set of scripts to download all the linked files and parse out the numbers from them.

[counts.csv](counts.csv) is the output: a CSV file with one line per time period counted and
one column per type of movement counted. The columns are in the same order as
[Montreal uses](http://donnees.ville.montreal.qc.ca/dataset/comptage-vehicules-pietons)
for ease of comparison, even though the time periods are different.
