This Directory contains the following files:

* a script (__prep_wb_vcf.py__) for downloading the gff3 annotation file from wormbase and turning it into a variant caller file (VCF). 
* __WS245.vcf.gz__ The resulting VCF file that is generated using the aforementioned script.
* __WS245.vcf.gz.csi__ - An index for the VCF.
* __refFlat.ws245.txt__ - refFlat created by lifting over from ce10 (ws220) from ucsc genome browser.


This file contains all the variants labeled as single nucleotide polymorphisms (SNP) or point_mutation within the GFF file. It can be used to assess sample identity, accuracy, etc.