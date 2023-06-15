# Quality Assesment
Quality assessment is vital in your metagenomic assembly pipeline. 
Assembling contigs with poor quality reads leads to a variety of downstream issues including: poor assembly, poor binning, and poor results. 
Filtering out poor quality reads increases the production of meaningful assemblies, bins, and taxonomic identification, for your microbiome samples.
The following example will analyze and filter the reads from a NovaSeq paired-end (PE150) sequencing run. 

First, you need to download and/or upload your sequences to the folder that you will call upon in your directory. If you have large files (e.g., > 1Gb), use:
**wget <copy/paste your html link here>**
