# Giant-Kelp-Associated-Microbiome-Metagenomics
This respository contains bash and R scripts for asembling and analyzing giant kelp microbiome metagenomes. Each file contains a specific step in the metagenomic assembly process. Those steps are organized as the following: 
  
    1. Raw read quality control using fastqcand bbtools (i.e., inspecting, trimming, and reinspecting reads).
    
    2. Assembly using megahit (this includes both coassembly and single sample assembly).
    
    3. Read mapping using bowtie2 and samtools. 
   
    4. Binning contigs using metabat2.
    
    5. Bin quality assessment using checkm.
    
    6. Categorizing bins based on quality (i.e., high, medium, and low).
    
    7. Taxonomic identification/classification using **gtdb-tk**. 
