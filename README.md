# Thesis

Changes in 'Pathway Analysis- Main Script':
1. Genes' significance: the z-score is employed (threshold=1.96 corresponding to p-value's threshold 0.05)
2. SPIA: P_NDE code corrections
3. GraphiteWeb: adjustment step added
4. DEAP: replace rotation step with FDR correction 
5. MinePath: when matching sub-paths with gene expression profiles, instead of the mean value of the genes of a node, compute the node value using the OR boolean operator
6. DEAP: E calculation corrections
7. PRS: replace 2nd normalization step with FDR correction

Results Calculated (some files are too big for git):
1. MinePath
2. TAPPA
3. TEAK
4. HiPathia
5. PRS (without the 2nd normalization step - replaced with FDR correction)
6. GraphiteWeb: if I adjust using Benjamini and Hochberg method the accuracy reduces (generalisation)
7. DEAP: problems resolved, file too big for git

Results Calculating (files are compressed because of the size, must be unzipped before running code):
1. SPIA (0%): calculation time

