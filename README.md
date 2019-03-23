# Database_Mytilus
Database of Mytilus sp. data

# Mytilus_genotypes

* ind:
* pop:
* seq:
* then one marker per column:
	NG = not genotyped in the experiment;
	NA = missing data;
	format allele1/allele2.

# Mytilus loci


* number:
* name:
* alt_name: Multiple alternative names for the marker, separated by "/".
	Use grep style functions to search.
* sequence:
* SNP:
* LGC_SNPNum: LGC company internal SNP id for KASParray genotyping.
	A SNP can have multiple ids, separated by "/".
* LGC_AlleleX: LGC company Allele for X fluorescence.
* LGC_AlleleY: LGC company Allele for Y fluorescence.
* LGC_Sequence: LGC company internal sequence around the SNP.
* contig: Contig name from Fraïsse et al. 2016 paper.
* position: Position on the previous contig.
* ancestry_info:
* func:
* subfunc:
* gene:
* comment:


# Mytilus populations

* pop
* lat
* long
* sea_code
* iso_country
* locality_code
* locality
* source
* collection_date
* dna_extraction
* seq: in which sequencing or genotyping experiment the population was present.
Can be multiple experiments separated by "/".
* N
* num
* old_num
* old_name
* commentary
