# nemabiome-validation
Validaiton of nemabiome studies, with a focus on primer validation, replication, post PCR pooling and sequencing depth. 

Each cow (n=5) was sampled once. For each sample, a PCR reaction was performed on three replicates, respectively called PCR1, 2, 3. The resultant PCRs are pooled, mixing: PCR1 and 2, PCR1 and 3, PCR 2 and 3 and PCR1, 2 and 3. The four pooled samples and the 3 replicate PCRs were all individually sequenced

NEMA1 and NEMA2 were the DADA2 pipelines for the two primers. The results of the 2 pipelines were assigned species within the manual assignment file due to issues with the assignSpecies function in R. The NEMA master file is the resultant file of the manual assignment, as well as data manipulation in excel. 
