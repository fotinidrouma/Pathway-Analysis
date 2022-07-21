# Thesis
File 'Pathway Analysis': contains all methods in their primary implementation.
File 'Pathway Analysis- Main Script': the 'Pathway Analysis' file with corrections.
Results: GraphiteWeb is still computing, must be unzipped

Changes in 'Pathway Analysis- Main Script':
1. For genes' significance the z-score is employed (threshold=1.96 corresponding to p-value's threshold 0.05)

Idea:
1. For MinePath: when matching sub-paths with gene expression profiles, instead of the mean value of the genes of a node, compute the node value using the OR boolean operator.

Implementation Completed:
1. MinePath
2. TAPPA
3. TEAK
4. HiPathia 
5. PRS
6. GraphiteWeb
7. DEAP
8. SPIA

Results Calculated (some files are too big for git):
1. MinePath
2. TAPPA
3. TEAK
4. HiPathia
5. PRS (without the 2nd normalization step)

Results Calculating (files are compressed because of the size, must be unzipped before running code):
1. GraphiteWeb (50%) 
2. DEAP (0%)
3. SPIA (0%)

