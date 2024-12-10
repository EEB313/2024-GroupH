# 2024-GroupH


Final Dataset: FINALDATASET.csv file. Referred to as df_hostremoved in the code (.Rmd) file. Dataset featuring host orders and their associations with certain viruses, along with virus traits. Combined dataset from CLOVER's MammalVirusesAssociations and HP3's VirusInfo. 


Fields are defined as follows:

Virus - name of virus as givn in CLOVER datasets, edited for accordance w/ NCBI. 

HostOrder - order of species affected by virus. Note that the repeats are because each row was originally a species, and the taxonomy information downstream of host order was stripped for the analysis.

vSegmentedTF - TRUE/FALSE depending on if the virus affecting the mammal os segmented or not segmented. 

vCytopReplicTF - TRUE/FALSE depending on whether the virus replicates in the cytoplasm or not. 

vFamily

STATION - the sampling station within the replicate where the sample was taken. each replicate had 5 sampling stations

ADULTS - the number of adult fireflies on the trap, for that station-rep-treatment-date combination.
