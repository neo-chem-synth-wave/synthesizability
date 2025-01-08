# Overview
**Title:** Organic Compound Synthetic Accessibility Prediction Based on the Graph Attention Mechanism<br>
**Authors:** Jiahui Yu, Jike Wang, Hong Zhao, Junbo Gao, Yu Kang, Dongsheng Cao, Zhe Wang, Tingjun Hou<br>
**Publication Date:** 2022/06/08<br>
**Publication Link:** [ACS Publications](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00038)

# Abstract
Accurate estimation of the synthetic accessibility of small molecules is needed in many phases of drug discovery. 
Several expert-crafted scoring methods and descriptor-based quantitative structure–activity relationship (QSAR) 
models have been developed for synthetic accessibility assessment, but their practical applications in drug discovery 
are still quite limited because of relatively low prediction accuracy and poor model interpretability. In this study, 
we proposed a data-driven interpretable prediction framework called GASA (Graph Attention-based assessment of 
Synthetic Accessibility) to evaluate the synthetic accessibility of small molecules by distinguishing compounds 
to be easy- (ES) or hard-to-synthesize (HS). GASA is a graph neural network (GNN) architecture that makes self-feature 
deduction by applying an attention mechanism to automatically capture the most important structural features related to 
synthetic accessibility. The sampling around the hypothetical classification boundary was used to improve the ability of 
GASA to distinguish structurally similar molecules. GASA was extensively evaluated and compared with two descriptor-based 
machine learning methods (random forest, RF; eXtreme gradient boosting, XGBoost) and four existing scores 
(SYBA: SYnthetic Bayesian Accessibility; SCScore: Synthetic Complexity score; RAscore: Retrosynthetic Accessibility score; 
SAscore: Synthetic Accessibility score).