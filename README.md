# Gene expression and gene regulatory network analysis with statistical methods and machine learning algorithms
The code developed for a thesis on "Gene expression and gene regulatory network analysis with statistical methods and machine learning algorithms" is included in this project.

## About the project
The goal of this study was to compare the findings to earlier research in order to determine the most efficient method for pathway analysis using the technologies that are currently provided. A Decision Tree algorithm was used to evaluate the results after implementing the scoring method for various Pathway Analysis tools. TAPPA, PRS, TEAK, DEAP, GraphiteWeb, MinePath, and HiPathia were among the implementation tools chosen.

Changes in 'Pathway Analysis':
1. Genes' significance: the z-score is employed (threshold>=1.96 corresponding to p-value's threshold<=0.05)
2. GraphiteWeb: adjustment with Benjamini and Hochberg approach
3. DEAP: replace rotation step with FDR correction 
4. MinePath: when matching sub-paths with gene expression profiles, instead of the mean value of the genes of a node, compute the node value using the OR boolean operator
5. DEAP: E calculation corrections
6. PRS: replace 2nd normalization step with FDR correction

Results Calculated (some files are too big for git):
1. MinePath
2. TAPPA
3. TEAK
4. HiPathia
5. PRS 
6. GraphiteWeb: if I adjust using Benjamini and Hochberg method the accuracy reduces (generalisation)
7. DEAP

