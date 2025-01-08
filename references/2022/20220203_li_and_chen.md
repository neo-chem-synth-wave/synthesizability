# Overview
**Title:** Prediction of Compound Synthesis Accessibility Based on Reaction Knowledge Graph<br>
**Authors:** Baiqing Li, Hongming Chen<br>
**Publication Date:** 2022/02/03<br>
**Publication Link:** [Molecules](https://www.mdpi.com/1420-3049/27/3/1039)

# Abstract
With the increasing application of deep-learning-based generative models for de novo molecule design, 
the quantitative estimation of molecular synthetic accessibility (SA) has become a crucial factor for 
prioritizing the structures generated from generative models. It is also useful for helping in the 
prioritization of hit/lead compounds and guiding retrosynthesis analysis. In this study, based on the 
USPTO and Pistachio reaction datasets, a chemical reaction network was constructed for the identification 
of the shortest reaction paths (SRP) needed to synthesize compounds, and different SRP cut-offs were then 
used as the threshold to distinguish a organic compound as either an easy-to-synthesize (ES) or 
hard-to-synthesize (HS) class. Two synthesis accessibility models (DNN-ECFP model and graph-based CMPNN model) 
were built using deep learning/machine learning algorithms. Compared to other existing synthesis accessibility 
scoring schemes, such as SYBA, SCScore, and SAScore, our results show that CMPNN (ROC AUC: 0.791) performs 
better than SYBA (ROC AUC: 0.76), albeit marginally, and outperforms SAScore and SCScore. Our prediction models 
based on historical reaction knowledge could be a potential tool for estimating molecule SA.