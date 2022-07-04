# Thesis
File 'Pathway Analysis': contains all methods in their primary implementation.
File 'Pathway Analysis- Main Script': the 'Pathway Analysis' file with corrections.
Files in 'Results' directory must be unzipped.

Changes in 'Pathway Analysis- Main Script':
1. MinePath discretization method corrections
2. One sub-path and one sample at a time for each method's functions
3. Get final results in DataFrame form for a specific sample and each sub-path
4. For genes' significance the z-score is employed
5. Calculated the scores for each sample and sub-path for MinePath

Completed:
1. MinePath
2. TAPPA
3. HiPathia
4. TEAK
5. DEAP
6. PRS
7. HiPathia
8. SPIA

Concerns:
1. PRS, SPIA, SubSPIA and GraphiteWeb: P-values and fold-changes return one value for each gene. How to use the expression values of each sample and get different sub-paths' scores? (Z-score)
