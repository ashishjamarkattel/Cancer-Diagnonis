### ABOUT

Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers).

Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.

We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

### Problem statement :

Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

The problem contain the zip file of testing and training data.

### Business Constrain.

   - No latency require but should not take long hours.
   - Errors are highly considered.
   - Should be interpretibility.
   - Probability can provide higher evaluation of the model for the further analysis
    
### Technique.

For Categorical data various techinique were followed :
  - One hot encoding.
  - Responce encoding.
 
### MOdel used.

Constrain contain interpetability so. 

  - Naive bayes.- Probability gives interpretable,
  - Knn. -  Highly interpetable given by distance .
  - Random forest. - No interpetability but decision tree gives interpetablity
  - Logistic regression. - weight gives interpetability
 
 also Feature importance was calculated.
 
