# ggtrevextra
Package preparation: for analysis visualization of phylogenetic trees, distances, phylogeography ...



## test data
- `data`folder
	- We used _Listeria monocytogenes_ data set that was used to define the cgMLST scheme [@moura2017] -  public isolates that are hosted in  BIGSDB ...
		- [ ] clean / add Script used for download
	- in `moura_test` folder: Lineage identification for the "Moura2017" was done with [MLST software]() using the Pasteur scheme, downloaded from BIGSDB 
			-[ ] clean / add script used for download
			Isolates belonging to lineage I? were selected from tree reconstruction 
			- [ ] R script
	- A phylogenetic tree was reconstructed using the pipeline [ALPPACA](https://github.com/NorwegianVeterinaryInstitute/ALPPACA) 

MLST software, and ALPPACA were run on the allocation for project nn9305k on the cluster SAGA 
[[SCRIPTS_languages/R/packages_prep/ggtrevextra/run_logs/Test_data_log]]

Note that no assessment of the quality of the assemblies provided (contiguity, eventual contamination) was performed, as our sole objective was to obtain a phylogenetic tree file that we could use as input for the sole purpose of functions and data format conversion testing. 

- [ ]  Citation for SAGA 





			
		
