This script was written to assist researchers analyzing Mass Spectrometry data.

This script load all Mass Spectrometry excell files in the the same directory containing 'Byonic' suffix.

A heatmap will be formed for all the data combined.

It will do both basic data cleaning and gene annotation:

Data cleaning:
- The script finds separate entries that refers to the same gene (for example gene isoforms) and combine it together based on the gene name.
- Common contaminants and proteins of reverse database are being removed.

Gene annotation:
- For each gene, a full description from is being add to the list using the Uniprot API (Info column).
- For each gene, the subcellular localization is being add (column Locations) using the Uniprot API.


--- optimized to Byonic output file format, but can be modified to work with other formats ----


Written by Niv Dobzinski, PhD
niv.dob@gmail.com
