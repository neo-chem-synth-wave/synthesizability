# Overview
**Title:** Incorporating Synthetic Accessibility in Drug Design: Predicting Reaction Yields of Suzuki Cross-Couplings by Leveraging AbbVie’s 15-Year Parallel Library Data Set<br>
**Authors:** Priyanka Raghavan, Alexander J. Rago, Pritha Verma, Majdi M. Hassan, Gashaw M. Goshu, Amanda W. Dombrowski, Abhishek Pandey, Connor W. Coley, Ying Wang<br>
**Publication Date:** 2024/05/20<br>
**Publication Link:** [ACS Publications](https://pubs.acs.org/doi/10.1021/jacs.4c00098)

# Abstract
Despite the increased use of computational tools to supplement medicinal chemists’ expertise and intuition in drug design, 
predicting synthetic yields in medicinal chemistry endeavors remains an unsolved challenge. Existing design workflows could 
profoundly benefit from reaction yield prediction, as precious material waste could be reduced, and a greater number of relevant 
compounds could be delivered to advance the design, make, test, analyze (DMTA) cycle. In this work, we detail the evaluation of 
AbbVie’s medicinal chemistry library data set to build machine learning models for the prediction of Suzuki coupling reaction yields. 
The combination of density functional theory (DFT)-derived features and Morgan fingerprints was identified to perform better than 
one-hot encoded baseline modeling, furnishing encouraging results. Overall, we observe modest generalization to unseen reactant 
structures within the 15-year retrospective library data set. Additionally, we compare predictions made by the model to those made 
by expert medicinal chemists, finding that the model can often predict both reaction success and reaction yields with greater accuracy. 
Finally, we demonstrate the application of this approach to suggest structurally and electronically similar building blocks to replace 
those predicted or observed to be unsuccessful prior to or after synthesis, respectively. The yield prediction model was used to select 
similar monomers predicted to have higher yields, resulting in greater synthesis efficiency of relevant drug-like molecules.