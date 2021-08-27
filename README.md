# Experimental-evolution-pipeline

A notebook for mutation analysis in experimental evolution data (morbidostat). Created for using with pacbio long-reads sequences
For now it can create some SV files (using cuteSV, sniffles and SURVIVOR) and annotated SNP's file (list of mutated genes) on the output.

How to use:
1) Install all requirements
2) Create file named "labels" (barcode_number ref.fasta annotation.gff on each next line for every sample you want to use) in the same directory as the notebook.ipynb file
3) Configure data folder and name of .bam file in the first cell
4) Configure tools paths and SURVIVOR settings in the second cell
5) Run notebook
