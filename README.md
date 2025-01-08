# Synthesizability
![Static Badge](https://img.shields.io/badge/synthesizability-2025.1.1--alpha-%23FFFFFF?logo=github&style=flat)
![Static Badge](https://img.shields.io/badge/Elix%2C%20Inc.-%235EB6B3?style=flat)
![Static Badge](https://img.shields.io/badge/Institute%20of%20Science%20Tokyo-%231C3177?style=flat)

Welcome to the computer-assisted **synthesizability** research project !!!


## Installation
A standalone environment can be created using the [git](https://git-scm.com) and [conda](https://conda.io) commands as
follows:

```shell
git clone https://github.com/neo-chem-synth-wave/synthesizability.git

cd synthesizability

conda env create -f environment.yaml

conda activate synthesizability-env
```

The [synthesizability](/synthesizability) package can be installed using the [pip](https://pip.pypa.io) command as follows:

```shell
pip install --no-build-isolation -e .
```


## License Information
The contents of this repository are published under the [MIT](/LICENSE) license. Please refer to individual references
for more details regarding the license information of external resources utilized within this repository.


## Contact
If you are interested in contributing to this repository by reporting bugs, suggesting improvements, or submitting
feedback, feel free to use [GitHub Issues](https://github.com/neo-chem-synth-wave/synthesizability/issues).


## References
**[[1]](/references/2009/20090610_ertl_p_and_schuffenhauer_a.md)** Ertl, P. and Schuffenhauer, A. **Estimation of
Synthetic Accessibility Score of Drug-like Molecules based on Molecular Complexity and Fragment Contributions**. _J.
Cheminform._, 2009, 1, 8.

**[[2]](/references/2018/20180108_coley_c_w_et_al.md)** Coley, C.W., Rogers, L., Green, W.H., and Jensen, K.F.
**SCScore: Synthetic Complexity Learned from a Reaction Corpus**. _J. Chem. Inf. Model._, 2018, 58, 2, 252-261.

**[[3]](/references/2020/20200520_vorsilak_colar_cmelo_and_svozil.md)** Voršilák, M., Kolář, M., Čmelo, I. and Svozil, D. 
**SYBA: Bayesian estimation of synthetic accessibility of organic compounds**. _J. Cheminform._, 2020, 12, 35.

**[[4]](/references/2021/20210307_thakkar_chadimova_bjerrum_engkvist_reymond.md)** Thakkar, A., Chadimová, V., Bjerrum, E.J., Engkvist, O. and Reymond, J.L.
**Retrosynthetic accessibility score (RAscore) – rapid machine learned synthesizability classification from AI driven retrosynthetic planning**. _Chem. Sci._, 2021,12, 3339-3349.

**[[5]](/references/2022/20220203_li_and_chen.md)** Baiqing, L. and Hongming, C. **Prediction of Compound Synthesis Accessibility Based on Reaction Knowledge Graph**. _Molecules._, 2022, 27, 1039.

**[[6]](/references/2022/20220422_liu_korablyov_jastrzebski_pruszynski_bengio_segler.md)** Cheng-Hao, L., Korablyov, M., Jastrzębski, S., Włodarczyk-Pruszyński, P., Bengio, Y., and Segler, M.
**RetroGNN: Fast Estimation of Synthesizability for Virtual Screening and De Novo Design by Learning from Slow Retrosynthesis Software**. _J. Chem. Inf. Model._, 2022, 62, 10, 2293-2300.

**[[7]](/references/2022/20220608_yu_wang_zhao_gao_kang_cao_wang_hou.md)** Yiahui, Y., Wang, J., Zhao, H., Gao, J., Kang, Y., Cao, D., Wang, Z. and Hou, T.
**Organic Compound Synthetic Accessibility Prediction Based on the Graph Attention Mechanism**. _J. Chem. Inf. Model._, 2022, 62, 12, 2973-2986.

**[[8]](/references/2023/20230831_kim_lee_kim_lim_kim.md)** Hyeongwoo, K., Kyunghoon, L., Chansu, K., Jaechang, L. and Kim, W.Y.
**DFRscore: Deep Learning-Based Scoring of Synthetic Complexity with Drug-Focused Retrosynthetic Analysis for High-Throughput Virtual Screening**. _J. Chem. Inf. Model._, 2023, 64, 7, 2432-2444.

**[[9]](/references/2023/20230919_parrot_tajmouati-dasilva_atwood_fourcade_mathe_huu_perron.md)** Parrot, M., Tajmouati, H., Ribeiro da Silva, V.B., Atwood, B.R., Fourcade, R., Gaston-Mathé, Y., Do Huu, N., and Perron, Q.
**Integrating synthetic accessibility with AI-based generative drug design**. _J. Cheminform._, 2023, 15, 83.

**[[10]](/references/2023/20231102_s.wang_l.wang_li_bai.md)** Wang, S., Wang, L., Fenglei, L. and Bai, F.
**DeepSA: a deep-learning driven predictor of compound synthesis accessibility**. _J. Cheminform._, 2023, 15, 103.

**[[11]](/references/2024/20240723_chen_jung.md)** Chen, S., and Jung, Y. 
**Estimating the synthetic accessibility of molecules with building block and reaction-aware SAScore**. _J. Cheminform._, 2024, 16, 83.

**[[12]](/references/2024/20241018_neeser_correia_schwaller.md)** Neeser, R.M., Correia, B., Schwaller, P.
**FSscore: A Personalized Machine Learning-Based Synthetic Feasibility Score**. _Chem. Methods_, 2024, 4, e202400024.

**[[13]](/references/2023/20230114_skoraczynski_kitlas_miasojedow_gambin.md)** Skoraczyński, G., Kitlas, M., Miasojedow, B., and Gambin, A. 
**Critical assessment of synthetic accessibility scores in computer-assisted synthesis planning**. _J. Cheminform._, 2023, 15, 6.

**[[14]](/references/2024/20240520_raghavan_rago_verma_hassan_goshu_dombrowski_pandey_coley_wang.md)** Raghavan, P., Rago, A.J., Verma, P., Hassan, M.M., Goshu, G.M., Dombrowski, A.W., Pandey, A., Coley, C.W., and Wang, Y. 
**Incorporating Synthetic Accessibility in Drug Design: Predicting Reaction Yields of Suzuki Cross-Couplings by Leveraging AbbVie’s 15-Year Parallel Library Data Set**. _J. Am. Chem. Soc._, 2024, 146, 22, 15070-15084.