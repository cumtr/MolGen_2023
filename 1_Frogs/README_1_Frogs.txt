Information about files in Project: 1_Frogs/

Data/Phylo/:
	MMEE_2023_CO1/
		# A directory with the forward and reverse reads from the sequencing center for YOUR samples
	Hyla_mtDNA_References.fasta
		# fasta formatted Sequences for many Hyla species that you can use as outgroup

Data/RADphylo/:
	# You don’t need this file in the actual version of the practical

Data/RADpopgen/:
	hyla_FSTAT.dat
		# Data for population analyses in fstat format
	populations_numeric_codes.txt
		#File with a numeric code for each population. You have to use this file to change the population column in the R object created when you read hyla_FSTAT.dat file.

Data/RADstructure/:
	Hyla.struct.geno 
		# data for Structure like analyses in geno fromat, ready for sNMF analyses.
	PopId.txt 
		# Population Id (from 1 to 12) of each induvial in the geno file. Line_3 = individual_3 = Population_1

