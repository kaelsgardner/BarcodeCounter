# bioinformatics

An MMBio lab is experimenting with random peptides (8 amino acids in length) to see if any of them are toxic to E. coli. 
They artificially insert a gene that codes for a single peptide, with a corresponding identifying "barcode" (at the very 
beginning of the gene) into E. coli grow. After a period of time, they sequence the DNA of all the bacteria, and they need
a program that can read the FASTQ file they get and count the number of organisms that contain each of the barcodes. If 
none or very few of the surviving bacteria contain a certain barcode, the corresponding peptide might be toxic. The barcode 
may vary in length so the user must input the barcode length.
