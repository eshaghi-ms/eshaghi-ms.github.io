---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Mohammad Sadegh Eshaghi is currently a Ph.D. candidate in Computational Physics and Scientific Machine Learning, at Leibniz University Hannover. He completed his bachelor’s degree at Amirkabir University of Technology and earned his master’s degree in engineering at K. N. Toosi University of Technology. He has worked as a researcher at the International Center for Numerical Methods in Engineering [(CIMNE)](https://cimne.com/) in Spain and in [Prof. Rabczuk](https://scholar.google.ca/citations?user=3CBuGosAAAAJ&hl=en)’s group at the Institute of Structural Mechanics in Germany. His research interests include the integration of Deep Learning and Computational Mechanics (AI4Science).

His research interests include AI4Science and Scientific Machine Learning. He has since been involved in research combining machine learning and computational physics, contributing to publications in areas such as Operator Learning and Scientific Machine Learning.

His work aims to develop efficient and scalable computational models for complex physical systems using modern AI-based approaches.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/NOWS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NOWS: Neural Operator Warm Starts for Accelerating Iterative Solvers](https://arxiv.org/abs/2511.02481)

Mohammad Sadegh Eshaghi, Cosmin Anitescu, Navid Valizadeh, **Yizheng Wang**, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2511.02481) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We propose Neural Operator Warm Starts (NOWS), a hybrid strategy that harnesses learned solution operators to accelerate classical iterative solvers by producing high-quality initial guesses for Krylov methods such as conjugate gradient and GMRES. NOWS integrates seamlessly with existing discretizations (finite-difference, finite-element, isogeometric analysis, finite volume method, etc.), consistently reducing iteration counts and computational time by up to 90%, while preserving the stability and convergence guarantees of traditional numerical algorithms.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJMS</div><img src='images/MHNO.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Head Neural Operator for Modelling Interfacial Dynamics](https://doi.org/10.1016/j.ijmecsci.2026.111363)

Mohammad Sadegh Eshaghi, Cosmin Anitescu, Navid Valizadeh, **Yizheng Wang**, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2507.17763) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We introduce the Multi-Head Neural Operator (MHNO), a novel neural operator architecture specifically designed to address temporal challenges in solving time-dependent PDEs governing interfacial dynamics. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/VINO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Variational Physics-informed Neural Operator (VINO) for Solving Partial Differential Equations](https://www.sciencedirect.com/science/article/pii/S004578252500057X)

**Mohammad Sadegh Eshaghi**, Cosmin Anitescu, Manish Thombre, Yizheng Wang, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2411.06587) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We propose the Variational Physics-Informed Neural Operator (VINO), a deep learning method designed for solving PDEs by minimizing the energy formulation of PDEs through the integration of neural operators with variational principles. This framework can be trained without any labeled data, significantly reducing computational costs.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/PENCO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PENCO: A Physics-Energy-Numerical-Consistent Operator for 3D Phase Field Modeling](https://www.sciencedirect.com/science/article/pii/S0045782526001362)

Mostafa Bamdad, **Mohammad Sadegh Eshaghi**, Cosmin Anitescu, Navid Valizadeh, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2512.04863) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We propose PENCO, a hybrid operator-learning framework that integrates physical laws with data-driven neural operators for solving spatiotemporal PDEs in phase-field modeling. PENCO introduces an enhanced H¹ Gauss–Lobatto collocation residual for robust enforcement of governing dynamics, a Fourier-space numerical consistency term capturing semi-implicit discretization behavior, and an energy-dissipation constraint ensuring thermodynamic consistency.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Mechanics Reviews</div><img src='images/EAAI_AI4PDEs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Artificial intelligence for partial differential equations in computational mechanics: A review](https://asmedigitalcollection.asme.org/appliedmechanicsreviews/article/doi/10.1115/1.4071710/1232570/Artificial-Intelligence-For-Partial-Differential?searchresult=1)

**Yizheng Wang**, Jinshuai Bai, Zhongya Lin, Qimin Wang, Cosmin Anitescu, Jia Sun, Mohammad Sadegh Eshaghi, Yuantong Gu, Xi-Qiao Feng, Xiaoying Zhuang, Timon Rabczuk, and Yinghua Liu
[**PDF**](https://arxiv.org/pdf/2410.19843) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We review AI for PDEs in computational mechanics, including solid mechanics, fluid mechanics, and biomechanics.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CMAME</div><img src='images/KINN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Kolmogorov Arnold Informed neural network: A physics-informed deep learning framework for solving PDEs based on Kolmogorov Arnold Networks](https://www.sciencedirect.com/science/article/pii/S0045782524007722)

**Yizheng Wang**, Jia Sun, Jinshuai Bai, Cosmin Anitescu, Mohammad Sadegh Eshaghi, Xiaoying Zhuang, Timon Rabczuk, and Yinghua Liu

[**PDF**](https://arxiv.org/pdf/2406.11045) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We propose different PDE forms based on KAN instead of MLP, termed Kolmogorov-Arnold-Informed Neural Network (KINN). We systematically compare MLP and KAN in various numerical examples of PDEs, including multi-scale, singularity, stress concentration, nonlinear hyperelasticity, heterogeneous, and complex geometry problems. Our results demonstrate that KINN significantly outperforms MLP in terms of accuracy and convergence speed for numerous PDEs in computational solid mechanics, except for the complex geometry problem. This highlights KINN's potential for more efficient and accurate PDE solutions in AI for PDEs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/DT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Methods for enabling real-time analysis in digital twins: A literature review](https://www.sciencedirect.com/science/article/pii/S0045794924000713)

**Mohammad Sadegh Eshaghi**, Cosmin Anitescu, Timon Rabczuk

[**PDF**](https://www.researchgate.net/profile/Mohammad-Eshaghi-3/publication/381548272_Methods_for_enabling_real-time_analysis_in_digital_twins_A_literature_review/links/66735f57d21e220d89c08f4e/Methods-for-enabling-real-time-analysis-in-digital-twins-A-literature-review.pdf?origin=publicationDetail&_sg%5B0%5D=fuM4YBsIkJ_zEd-sM1WbttaHWGN-abD5p0E9FhgZIJdTq8DxVIVr-EfzjumClIBcwqLxznUPNlNUxDUJKueJPA.14LLozdU3mI_LwTLM9TKCUfWVEsD22onTGsAGJRoT3Ee4vKHdf5gWyxSIN8xIf8tL06OVGnK9QFTcyM9qEIMPw&_sg%5B1%5D=nJXph7BxHlTd6TGEzl4ySY2q_dmC1uzDP71PG3LQPGYGAfzAnZcX1c7eKoaaFi1376RHW47wGtUCgMuE7m1xh1HlffaCFcfrf_iZ6GA1YDnx.14LLozdU3mI_LwTLM9TKCUfWVEsD22onTGsAGJRoT3Ee4vKHdf5gWyxSIN8xIf8tL06OVGnK9QFTcyM9qEIMPw&_iepl=&_rtd=eyJjb250ZW50SW50ZW50IjoibWFpbkl0ZW0ifQ%3D%3D&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIiwicG9zaXRpb24iOiJwYWdlSGVhZGVyIn19) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  This paper presents a comprehensive literature review on methods for enabling real-time analysis in digital twins—virtual models of physical systems. We systematically review and categorize methods and tools for reducing computational demands, accelerating the modeling of physical phenomena, and addressing challenges such as real-time data analysis, resource limitations, and data uncertainty to support cost reduction, risk mitigation, efficiency enhancement, and decision-making in digital twin implementations.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/DeepBeam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Applications of scientific machine learning for the analysis of functionally graded porous beams](https://www.sciencedirect.com/science/article/pii/S0925231224018903)

**Mohammad Sadegh Eshaghi**, Mostafa Bamdad, Cosmin Anitescu, Yizheng Wang, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2408.02698) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We investigate and compare different SciML approaches for analyzing functionally graded porous beams with arbitrary continuous material property variations. We implement three formulations: (a) the vector approach leading to Physics-Informed Neural Networks (PINNs), (b) the energy approach resulting in the Deep Energy Method (DEM), and (c) the data-driven approach yielding Neural Operator methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJMSD</div><img src='images/transfer_learning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Transfer Learning in Physics-Informed Neural Networks: Full Fine-Tuning, Lightweight FineTuning, and Low-Rank Adaptation](https://onlinelibrary.wiley.com/doi/10.1002/msd2.70030)

**Yizheng Wang**, Jinshuai Bai, Mohammad Sadegh Eshaghi, Cosmin Anitescu, Xiaoying Zhuang, Timon Rabczuk, and Yinghua Liu

[**PDF**](https://onlinelibrary.wiley.com/doi/epdf/10.1002/msd2.70030) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We explore the generalization capability of transfer learning in the strong and energy form of PINNs across different boundary conditions, materials, and geometries. The transfer learning methods we employ include full finetuning, lightweight finetuning, and Low-Rank Adaptation (LoRA).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/GSD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Machine learning-based estimation of soil's true air-entry value from GSD curves](https://www.sciencedirect.com/science/article/pii/S1342937X22001885)

**Mohammad Sadegh Eshaghi**, Mohammad Rezania, Meghdad Bagheri

[**PDF**](https://www.sciencedirect.com/science/article/pii/S1342937X22001885/pdfft?md5=ad0026d1bad218fbf658a6070769694c&pid=1-s2.0-S1342937X22001885-main.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We develop a machine learning predictive model for estimating the true air-entry value (AEV) of soils from grain size distribution (GSD) curves using the UNSODA database of 790 soil samples. The model incorporates bulk density and GSD parameters to predict true AEV from water content-based soil water retention curves (SWRCs), achieving high accuracy and reliability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/MDMM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multicriteria decision-making methods in selecting seismic upgrading strategy of high-rise RC wall buildings](https://ascelibrary.org/doi/full/10.1061/%28ASCE%29ST.1943-541X.0003304)

**Mohammad Sadegh Eshaghi**, Mohammad Sadegh Barkhordari, Zhenyu Huang, Jianqiao Ye

[**PDF**](https://ascelibrary.org/doi/epdf/10.1061/%28ASCE%29ST.1943-541X.0003304) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This study investigates retrofitting strategies for high-rise reinforced concrete (RC) buildings with shear walls subjected to seismic loads. Four buildings were equipped with passive energy dissipation devices and analyzed under far-field and near-field earthquake records from FEMA P-695. Using validated numerical models, structural responses were evaluated and ranked through Multicriteria Decision Making methods.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/ETL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhanced teacher-learning based algorithm in real size structural optimization](https://journals.vilniustech.lt/index.php/JCEM/article/view/16387)

**Mohammad Sadegh Eshaghi**, Alireza Salehi, Alfred Strauss

[**PDF**](https://journals.vilniustech.lt/index.php/JCEM/article/view/16387/11042) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We propose an Enhanced Teacher-Learning Based Optimization algorithm for optimizing large-scale space frame structures. The algorithm improves upon the original TLBO method by incorporating a machine learning-based crossover operation between new solutions and the best solution during the teacher phase, enabling the algorithm to escape local minima and achieve faster convergence with better solution quality. This enhancement makes ETLBO particularly suitable for practical large-scale structural optimization problems such as halls, hangars, and passenger stations, where computational efficiency and accuracy are crucial.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/FFPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Factors and failure patterns analysis for undrained seismic bearing capacity of strip footing above void](https://ascelibrary.org/doi/full/10.1061/%28ASCE%29GM.1943-5622.0002166)

**Mohammad Sadegh Eshaghi**, Mohsen Abbaspour, Timon Rabczuk

[**PDF**](https://ascelibrary.org/doi/epdf/10.1061/%28ASCE%29GM.1943-5622.0002166) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This study employs finite-element limit analysis to predict the undrained seismic bearing capacity and failure mechanisms of shallow strip footings on cohesive soils placed above unsupported rectangular voids. The research computes upper and lower bounds across comprehensive ranges of geometries, horizontal earthquake accelerations, material properties, and void configurations. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/Machine_Learning-Based_Prediction.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Machine learning-based prediction of the seismic bearing capacity of a shallow strip footing over a void in heterogeneous soils](https://www.mdpi.com/1999-4893/14/10/288)

**Mohammad Sadegh Eshaghi**, Mohsen Abbaspour, Hamidreza Abbasianjahromi, Stefano Mariani

[**PDF**](https://www.mdpi.com/1999-4893/14/10/288/pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This paper presents a machine learning framework for predicting the seismic bearing capacity of shallow strip footings positioned above voids in heterogeneous soil. Using a dataset of 38,000 finite element limit analysis simulations, various ML techniques were compared: multilayer percep. The study accounts for variations in soil properties (undrained shear strength and internal friction angle), horizontal earthquake accelerations, and void characteristics (position, shape, and size). Results demonstrated that all ML techniques performed well, with the multilayer perceptron achieving the highest accuracy (R² = 0.9955, RMSE = 0.0158), offering a robust alternative to complex analytical models for this challenging geotechnical problem.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/IJE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Straightforward prediction for responses of the concrete shear wall buildings subject to ground motions using machine learning algorithms](https://www.ije.ir/article_132523.html)

Mohammad Sadegh Barkhordari, **Mohammad Sadegh Eshaghi**

[**PDF**](https://www.ije.ir/article_132523_33dd0188d8540b90707e424a9afbba4e.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This study evaluates machine learning and hybrid models for predicting seismic responses of reinforced concrete shear walls under strong ground motions. Using OpenSees, four buildings (15, 20, 25, and 30 stories) with concrete shear walls were analyzed with 150 seismic records to create a comprehensive database linking record characteristics to structural responses. The models' accuracy in predicting shear wall responses was compared, and sensitivity analysis identified key input variables influencing seismic demand.

</div>
</div>


<div class='paper-box-text' markdown="1">

[Evaluation of a novel Asymmetric Genetic Algorithm to optimize the structural design of 3D regular and irregular steel frames](https://link.springer.com/article/10.1007/s11709-020-0643-2)

**Mohammad Sadegh Eshaghi**,  Aydin Shishegaran, Timon Rabczuk

[**PDF**](https://link.springer.com/content/pdf/10.1007/s11709-020-0643-2.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We propose a novel Asymmetric Genetic Algorithm (AGA) for optimizing steel frame structures by minimizing total weight under AISC ultimate load constraints. AGA employs a developed penalty function to find optimal population generations and selects cross-sectional areas from AISC side-flange shape steel sections using finite element analysis. Applied to a 15-storey three-bay steel planar frame and five additional numerical examples, AGA outperforms existing algorithms.

</div>
</div>

<div class='paper-box-text' markdown="1">

[Combination of sensitivity and uncertainty analyses for sediment transport modeling in sewer pipes](https://www.sciencedirect.com/science/article/pii/S1001627918303810)

Isa Ebtehaj, Hossein Bonakdari, Mir Jafar Sadegh Safari, Bahram Gharabaghi, Amir Hossein Zaji, Hossien Riahi Madavar, Zohreh Sheikh Khozani, **Mohammad Sadegh Eshaghi**, Aydin Shishegaran, Ali Danandeh Mehr

[**PDF**](https://www.sciencedirect.com/science/article/pii/S1001627918303810/pdfft?md5=5ac5f3951bf5b85953802d7be3f0b9d1&pid=1-s2.0-S1001627918303810-main.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This study addresses sediment deposition in lined open channels by developing a novel methodology that combines sensitivity and uncertainty analyses with machine learning to model sediment transport under non-deposition conditions in sewer and drainage systems. Using 127 models with one to seven dimensionless parameters and four evaluation strategies, the research identifies that a model with volumetric sediment concentration (CV) and relative particle size (d/R) as independent parameters best predicts the densimetric Froude number (Fr).

</div>

<div class='paper-box-text' markdown="1">

[Design of a hybrid ANFIS–PSO model to estimate sediment transport in open channels](https://link.springer.com/article/10.1007/s40996-018-0218-9)

Isa Ebtehaj, Hossein Bonakdari, **Mohammad Sadegh Eshaghi** 

[**PDF**](https://link.springer.com/content/pdf/10.1007/s40996-018-0218-9.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We present a hybrid ANFIS-PSO model to estimate the minimum densimetric Froude number for sediment transport in channel pipes without deposition. The PSO algorithm optimizes fuzzy membership function parameters while the ANFIS framework models the complex relationship between input parameters and sediment transport conditions. Tested on three independent datasets across varying conditions, the ANFIS-PSO approach significantly outperforms standard ANFIS and existing regression-based equations from literature, demonstrating superior accuracy and reliability for predicting sediment transport thresholds in sewer and drainage systems.

</div>

<div class='paper-box-text' markdown="1">

[Sediment transport modeling in rigid boundary open channels using generalize structure of group method of data handling](https://www.sciencedirect.com/science/article/pii/S0022169419306717)

Mir Jafar Sadegh Safari, Isa Ebtehaj, Hossein Bonakdari, **Mohammad Sadegh Eshaghi** 

[**PDF**](https://www.sciencedirect.com/science/article/pii/S0022169419306717/pdfft?md5=960438ba08ce567a113a6bb3fb603fb3&pid=1-s2.0-S0022169419306717-main.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- We develop predictive models using machine learning techniques to estimate sediment transport in open channels. Using four comprehensive datasets covering wide ranges of pipe sizes, sediment characteristics, channel slopes, and flow conditions, the machine learning approaches demonstrate superior performance over conventional regression models. The GS-GMDH model achieves the best results due to its generalized structure, with a practical MATLAB implementation provided for engineering applications. This data-driven approach addresses the complexity of sediment transport phenomena by incorporating fundamental characteristics of fluid, flow, sediment, and channel parameters.

</div>


# 📝 Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/EDEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Unified AI-Driven Fracture Mechanics: TheExtended Deep Energy Method (XDEM)](https://arxiv.org/abs/2511.05888)

**Yizheng Wang**, Yuzhou Lin, Somdatta Goswami, Luyang Zhao, Huadong Zhang, Jinshuai Bai, Cosmin Anitescu, Mohammad Sadegh Eshaghi, Xiaoying Zhuang, Timon Rabczuk, Yinghua Liu

[**PDF**](https://arxiv.org/pdf/2511.05888) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We propose Extended Deep Energy Method (XDEM), a unified deep learning framework that incorporates both displacement discontinuities and crack-tip asymptotics in the discrete setting, while flexibly coupling displacement and phase fields in the continuous setting.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/PFEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pretrain Finite Element Method: A Pretraining and Warm-start Framework for PDEs via Physics-Informed Neural Operators](https://arxiv.org/abs/2601.03086)

**Yizheng Wang**, Zhongkai Hao, Mohammad Sadegh Eshaghi, Cosmin Anitescu, Xiaoying Zhuang, Timon Rabczuk, Yinghua Liu

[**PDF**](https://arxiv.org/pdf/2601.03086) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We propose a Pretrained Finite Element Method (PFEM),a physics driven framework that bridges the efficiency of neural operator learning with the accuracy and robustness of classical finite element methods (FEM).
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/LMDEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Energy Method with Large Language Model assistance: an open-source Streamlit-based platform for solving variational PDEs](https://arxiv.org/abs/2602.07838)

**Yizheng Wang**, Cosmin Anitescu, Mohammad Sadegh Eshaghi,  Xiaoying Zhuang, Timon Rabczuk, Yinghua Liu

[**PDF**](https://arxiv.org/pdf/2602.07838) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We present LM-DEM(Large-Model-assisted Deep Energy Method), an open-source, Streamlit-based platform for solving variationalpartial differential equations (PDEs) in computational mechanics.
</div>
</div>



{% comment %}
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

{% endcomment %}
