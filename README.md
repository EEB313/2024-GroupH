# 2024-GroupH


Final Dataset: FINALDATASET.csv file. Referred to as df_hostremoved in the code (.Rmd) file. Dataset featuring host orders and their associations with certain viruses, along with virus traits. Combined dataset from CLOVER's MammalVirusesAssociations and HP3's VirusInfo. 


Fields are defined as follows:

Virus - name of virus as given in CLOVER datasets, edited for accordance w/ NCBI. 

vFamily - family of given virus species. 

HostOrder - order of species affected by virus. Note that the repeats are because each row was originally a species, and the taxonomy information downstream of host order was stripped for the analysis.

vSegmentedTF - TRUE/FALSE depending on if the virus affecting the mammal os segmented or not segmented. 

vCytopReplicTF - TRUE/FALSE depending on whether the virus replicates in the cytoplasm or not. 

vEnvelope - 1 if a virus is enveloped, 0 if a virus in non-enveloped. 

vSSoDS - 1 if a virus is single stranded RNA, 0 is a virus is double stranded RNA

isZoonotic - if a virus is known to be zoonotic: to have originated from animals and infected humans.