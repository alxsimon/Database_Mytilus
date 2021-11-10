# Database_Mytilus
Database of Mytilus sp. genotyping data.

# Mytilus_genotypes

* ind: name of the individual.
* pop: population of origin.
* seq: in which sequencing or genotyping experiment the individual was genotyped.
* then one marker per column:
	NG = not genotyped in the experiment;
	NA = missing data;
	format allele1/allele2.

# Mytilus loci

* number: numeric id of the SNP.
* name: name of the SNP.
* alt_name: multiple alternative names for the marker in case this was used in older experiments, separated by "/".
	Use grep style functions to search.
* sequence: flanking sequence with SNP information, e.g. [A/T].
* SNP: variants of the SNP, e.g. [A/T].
* LGC_SNPNum: LGC company internal SNP id for KASParray genotyping.
	A SNP can have multiple ids, separated by "/".
* LGC_AlleleX: LGC company Allele for X fluorescence.
* LGC_AlleleY: LGC company Allele for Y fluorescence.
* LGC_Sequence: LGC company internal sequence around the SNP.
* contig: Contig name from Fraïsse et al. 2016 paper.
* position: position on the contig.
* ancestry_info: see Fraïsse et al. 2016, populations this SNP differentiate.
* func: functional annotation from Fraïsse et al. 2016.
* subfunc: fubfunctional annotation from Fraïsse et al. 2016.
* gene: gene annotation from Fraïsse et al. 2016.
* comment: additional comment.


# Mytilus populations

* pop: population name.
* lat: latitude.
* long: longitude.
* locality: details on the locality of the population.
* source: providers of the samples.
* collection_date: collection date when available.
* dna_extraction: DNA extraction method used.
* seq: in which sequencing or genotyping experiment the population was present.
Can be multiple experiments separated by "/".
* num: number associated with population in the Beadxpress experiment.
* old_num: old number of population in the Beadxpress experiment.
* old_name: old name of population in the Beadxpress experiment.
* notes: additional notes.
* publication: in which publication this population was first used.


---------------------------------------
Fraïsse, C., Belkhir, K., Welch, J. J., & Bierne, N. (2016). Local interspecies introgression is the main cause of extreme levels of intraspecific differentiation in mussels. Molecular Ecology, 25(1), 269–286. [https://doi.org/10.1111/mec.13299](https://doi.org/10.1111/mec.13299)
