# MOFS_Resource
整理的部分关于多目标特征选择的算法源代码，文件名格式[算法简称]-[编程语言]-[依赖平台]，代码均为作者发布的源代码，未作更改，使用时应自当更改实验环境。代码来源包括但不限于:
1. https://github.com/HandingWangXDGroup
2. https://github.com/penfwang?tab=repositories
3. https://www5.zzu.edu.cn/cilab/Code.htm
4. https://github.com/BIMK/PlatEMO
5. https://github.com/ehancer06
6. https://toyamaailab.github.io/

tips:
1. 部分基于PlatEMO的算法，建议自己编写FS测试问题，可参考Ruwang Jiao提出的MFFS中的[FeatureSelectionNoisy.m](https://github.com/RuwangJiao/MFFS/blob/main/FeatureSelectionNoisy.m "FeatureSelectionNoisy.m"),  Zhenzhou Song提出的TAEFS中的[MOFS.m](https://github.com/HandingWangXDGroup/TAEFS-Matlab/blob/main/TAEFS/Problems/MOFS.m "MOFS.m"), 以及Baohang Zhang 提出的IGEA中的FS.m.  
2. 更建议根据平台提供的源码改写到本地运行环境中,运行效率更高。

# List
| Algorithm | Journal | Year | Paper                                                                                                                          |
| --------- | ------- | ---- | ------------------------------------------------------------------------------------------------------------------------------ |
| MOFS-MST  | TSMC    | 2024 | A Space Transformation-Based Multiform Approach for Multiobjective Feature Selection in High-Dimensional Classification        |
| TAEFS     | TEVC    | 2024 | Balancing Different Optimization Difficulty Between Objectives in Multi-Objective Feature Selection                            |
| FPPFS     | TEVC    | 2024 | Learning to Preselection: A Filter-Based Performance Predictor for Multiobjective Feature Selection in Classification          |
| BSOEA     | EC      | 2024 | A Tri-Objective Method for Bi-Objective Feature Selection in Classification                                                    |
| IGEA      | IS      | 2024 | Information gain-based multi-objective evolutionary algorithm for feature selection                                            |
| SCGP      | EC      | 2024 | Genetic Programming for Automatically Evolving Multiple Features to Classification                                             |
| DDFS      | SCIS    | 2024 | An evolutionary multiobjective method based on dominance and decomposition for feature selection in classification             |
| FS-DOS    | ASOC    | 2023 | Multiobjective optimization algorithm with dynamic operator selection for feature selection in high-dimensional classification |
| MODENCA   | KBS     | 2023 | An evolutionary filter approach to feature selection in classification for both single- and multi-objective scenarios          |
| DMBDE     | IS      | 2023 | Feature Selection Using Diversity-Based Multi-objective Binary Differential Evolution                                          |
| PRDH      | TEVC    | 2022 | Solving Multiobjective Feature Selection Problems in Classification via Problem Reformulation and Duplication Handling         |
| MFFS      | TCYB    | 2022 | Benefiting From Single-Objective Feature Selection to Multiobjective Feature Selection: A Multiform Approach                   |
| SM-MOEA   | TCYB    | 2021 | A Steering-Matrix-Based Multiobjective Evolutionary Algorithm for High-Dimensional Feature Selection                           |
| DAEA      | TEVC    | 2020 | A Duplication Analysis-Based Evolutionary Algorithm for Biobjective Feature Selection                                          |
