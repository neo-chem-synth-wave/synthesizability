# Overview
**Title:** Integrating synthetic accessibility with AI-based generative drug design<br>
**Authors:** Maud Parrot, Hamza Tajmouati, Vinicius Barros Ribeiro da Silva, Brian Ross Atwood, Robin Fourcade, Yann Gaston-Mathé, Nicolas Do Huu, Quentin Perron<br>
**Publication Date:** 2023/09/19<br>
**Publication Link:** [BMC](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-023-00742-8)

# Abstract
Generative models are frequently used for de novo design in drug discovery projects to propose new molecules. However, 
the question of whether or not the generated molecules can be synthesized is not systematically taken into account 
during generation, even though being able to synthesize the generated molecules is a fundamental requirement for such 
methods to be useful in practice. Methods have been developed to estimate molecule “synthesizability”, but, so far, 
there is no consensus on whether or not a molecule is synthesizable. In this paper we introduce the Retro-Score (RScore), 
which computes a synthetic accessibility score of molecules by performing a full retrosynthetic analysis through our 
data-driven synthetic planning software Spaya, and its dedicated API: Spaya-API (https://spaya.ai). We start by comparing 
several synthetic accessibility scores to a binary “chemist score” as estimated by chemists on a bench of generated molecules, 
as a first experimental validation that the RScore is a reliable synthetic accessibility score. We then describe a pipeline 
to generate molecules that validate a list of targets while still being easy to synthesize. We further this idea by performing 
experiments comparing molecular generator outputs across a range of constraints and conditions. We show that the RScore can 
be learned by a Neural Network, which leads to a new score: RSPred. We demonstrate that using the RScore or RSPred as a 
constraint during molecular generation enables our molecular generators to produce more synthesizable solutions, 
with higher diversity. 