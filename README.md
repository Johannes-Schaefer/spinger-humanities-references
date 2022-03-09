References style which should create the Springer Humanties Style (https://resource-cms.springernature.com/springer-cms/rest/v1/content/40196/data/References+Humanities+Style).

changelog .bst file:
- started with chicago.bst from https://ctan.ebinger.cc/tex-archive/biblio/bibtex/contrib/chicago/
- renamed file to modchicago.bst
- removed parentheses around year in list of references
- removed comma from in-text citations ("(Nelson, 2005)" -> "(Nelson 2005)")
- with multiple authors: changed the English "and" to the German "und"
- changed "Eds."/"Ed." to "Hg."
- remove \em from journal volume, changed "," to ":" after number and removed space before pages
- removed "In" from booktitle formatting (for inproceedings/incollection)
- changed formatting of mentioned pages from "pp. " to ": "
- changed chapter+pages formatting from "Chapter <number>, <pages>" to "<number>: <pages>"
- added support for field url (also doi/arXiv/pubmed) using this script: https://nxg.me.uk/dist/urlbst/
- removed the string "URL: " in front of urls
- changed dot after authors only to be set if authors do not end with a dot already
- abbreviated all first names and removed spaces in entries with mutliple first names

