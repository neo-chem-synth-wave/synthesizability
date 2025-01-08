# Overview
**Title:** Critical assessment of synthetic accessibility scores in computer-assisted synthesis planning<br>
**Authors:** Grzegorz Skoraczyński, Mateusz Kitlas, Błażej Miasojedow, Anna Gambin<br>
**Publication Date:** 2023/01/14<br>
**Publication Link:** [BMC](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-023-00678-z)

# Abstract
Modern computer-assisted synthesis planning tools provide strong support for this problem. However, they are still limited 
by computational complexity. This limitation may be overcome by scoring the synthetic accessibility as a pre-retrosynthesis 
heuristic. A wide range of machine learning scoring approaches is available, however, their applicability and correctness 
were studied to a limited extent. Moreover, there is a lack of critical assessment of synthetic accessibility scores with 
common test conditions.In the present work, we assess if synthetic accessibility scores can reliably predict the outcomes 
of retrosynthesis planning. Using a specially prepared compounds database, we examine the outcomes of the retrosynthetic 
tool AiZynthFinder. We test whether synthetic accessibility scores: SAscore, SYBA, SCScore, and RAscore accurately predict 
the results of retrosynthesis planning. Furthermore, we investigate if synthetic accessibility scores can speed up 
retrosynthesis planning by better prioritizing explored partial synthetic routes and thus reducing the size of the search 
space. For that purpose, we analyze the AiZynthFinder partial solutions search trees, their structure, and complexity 
parameters, such as the number of nodes, or treewidth.We confirm that synthetic accessibility scores in most cases well 
discriminate feasible molecules from infeasible ones and can be potential boosters of retrosynthesis planning tools. 
Moreover, we show the current challenges of designing computer-assisted synthesis planning tools.