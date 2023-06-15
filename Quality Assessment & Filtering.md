# Quality Assesment
Quality assessment is vital in your metagenomic assembly pipeline. 
Assembling contigs with poor quality reads leads to a variety of downstream issues including: poor assembly, poor binning, and poor results. 
Filtering out poor quality reads increases the production of meaningful assemblies, bins, and taxonomic identification, for your microbiome samples.
The following example will analyze and filter the reads from a NovaSeq paired-end (PE150) sequencing run. 

First, you need to download and/or upload your sequences to the folder that you will call upon in your directory. If you have large files (e.g., > 1Gb), use:
**wget <copy/paste your html link here>**

After downloading all of your desired files, double check that you have paired reads per sample. For example, I had 10 giant kelp microbiome samples with paired-end reads per sample, resulting in 20 total fastq files. These files were from Juvenile (5 samples) and Mature (5 samples) giant kelp microbiomes. The Juvenile files were sample numbers 58, 59, 60, 62, and 63. The mature files were sample numbers 138, 139, 140, 141, and 142. Use the following nomenclature for your file labelling: (Example) Juvenile_58_rawreads_unfiltered.fastq

