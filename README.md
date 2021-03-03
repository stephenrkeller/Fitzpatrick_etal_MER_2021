# Fitzpatrick_etal_MER_2021
 Data files accompanying:
 Fitzpatrick, M.C., V.E. Chhatre, R. Soolanayakanahally, and S.R. Keller. Experimental support for genomic prediction of climate maladaptation using the machine learning approach Gradient Forests. In press at Molecular Ecology Resources. Authorea preprint: https://doi.org/10.22541/au.159863198.86187354

## List of files and brief explanation:

- **balsam_core336inds_42pops.vcf.gz:** *bgzipped vcf file containing SNP genotypes for 336 Populus balsamifera from the core ancesty deme*
- **GF_GBS_predict_gardens.R:** *R script for analysis of height grwoth as a function of gnetic and climate offsets*
- **core336.bayenv.gardenOffset.csv:** *Genetic offset predictions based on outliers identified by Bayenv2*
- **core336.Bayenv-lfmm.gardenOffset.csv:** *Genetic offset predictions based on outliers identified by Bayenv2 and LFMM*
- **core336.bf.pc1.emp.txt:** *List of outlier SNPs with empirical p-values from Bayenv2 analysis using climate PC1*
- **core336.bf.pc2.emp.txt:** *List of outlier SNPs with empirical p-values from Bayenv2 analysis using climate PC2*
- **core336.gf.allOls.gardenOffset.csv:** *Genetic offset predictions based on outliers identified by all outlier methods (Bayenv2, LFMM, GF-X, GF-Raw)*
- **core336.gf.rawFreqs.gardenOffset.csv:** *Genetic offset predictions based on outliers identified by GF-Raw*	
- **core336.gf.stdFreqs.gardenOffset.csv:** *Genetic offset predictions based on outliers identified by GF-X*
- **core336.lfmm.gardenOffset.csv:** *Genetic offset predictions based on outliers identified by LFMM*
- **core336.500_RANDOM.gardenOffset.csv:** *Genetic offset predictions based on 999 bootstrap replicates of 500 randomly sampled SNPs*
- **core336.mahal.gardenOffset.csv:** *Mahalanobis multivariate climate distances between populations and common garden sites*
- **gardenQuery.RData:** *Vermont common garden data*
- **IH_phenology_2015.csv:** *Indian Head common garden data*
- **manhattan_data_core_pc1.txt** *List of outlier SNPs with empirical p-values from LFMM analysis using climate PC1*
- **manhattan_data_core_pc2.txt** *List of outlier SNPs with empirical p-values from LFMM analysis using climate PC2*
- **snpR2.csv:** *GF R^2 values for modeled SNPs*
