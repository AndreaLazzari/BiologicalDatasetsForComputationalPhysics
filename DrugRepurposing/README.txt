The following files are necessary for working on network proximity

ng_ppi.txt  -  PPI network
sarscov_disease_genes.csv   -  disease genes
match_uni_drug2.txt   -  drugs and their targets

Output file:
proximity.csv   -  results of network proximity are stored here. Only the results of first 100 drugs are stored here for the purpose of demonstration of the method and code. Remaining ~ 25000 drugs have to be done.  
Columns:
d: proximal distance between drug targets of a single drug to all disease targets
z_score: Network proximity, computed from d, mean_d_random, sd_random
mean_d_random and sd_random: are mean and std. deviation of the reference distance distribution. They are used to convert observed distance 𝑑𝑐(𝑆,𝑇) to normalized distance 𝑧(𝑆,𝑇)





