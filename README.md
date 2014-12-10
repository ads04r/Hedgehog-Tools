Hedgehog-Tools
==============

Additional tools for data-crunching, designed to be used by Hedgehog.

csv2json
--------
A tool that takes CSV on STDIN and outputs JSON on STDOUT. First line of CSV
must be column headers, and currently only supports comma seperation, no
tabs.

ics2rdf
-------
A tool that converts an ICS file into RDF, using the event and timeline
ontologies. The script requires a namespace passed on the command line
which is simply the namespace of the URIs which are assigned to the
events in the feed.
