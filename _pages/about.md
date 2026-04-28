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

[**PDF**](https://arxiv.org/abs/2511.02481) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We propose Neural Operator Warm Starts (NOWS), a hybrid strategy that harnesses learned solution operators to accelerate classicaliterative solvers by producing high-quality initial guesse.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJMS</div><img src='images/MHNO.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Head Neural Operator for Modelling Interfacial Dynamics](https://doi.org/10.1016/j.ijmecsci.2026.111363)

Mohammad Sadegh Eshaghi, Cosmin Anitescu, Navid Valizadeh, **Yizheng Wang**, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2507.17763) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We introduce the Multi-Head Neural Operator (MHNO), a novel neural operator architecture built to handle long temporal dynamics. MHNO uses time-step-specific projections and message-passing-inspired connections to model full time evolution in a single forward pass.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/VINO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Variational Physics-informed Neural Operator (VINO) for Solving Partial Differential Equations](https://arxiv.org/abs/2411.06587)

**Mohammad Sadegh Eshaghi**, Cosmin Anitescu, Manish Thombre, Yizheng Wang, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://arxiv.org/pdf/2411.06587) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  VINO is a method for solving PDEs by integrating neural operators with variational principles and physics-informed learning. This framework can be trained without any labeled data, resulting in improved performance and accuracy compared to existing deep learning methods and conventional PDE solvers. By discretizing the domain into elements, the variational format allows VINO to overcome the key challenge in physics-informed neural operators, namely the efficient evaluation of the governing equations for computing the loss.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/PENCO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PENCO: A Physics-Energy-Numerical-Consistent Operator for 3D Phase Field Modeling](https://www.sciencedirect.com/science/article/pii/S0925231224018903)

Mostafa Bamdad, **Mohammad Sadegh Eshaghi**, Cosmin Anitescu, Navid Valizadeh, Timon Rabczuk

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Mechanics Reviews</div><img src='images/EAAI_AI4PDEs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Artificial intelligence for partial differential equations in computational mechanics: A review](https://asmedigitalcollection.asme.org/appliedmechanicsreviews/article/doi/10.1115/1.4071710/1232570/Artificial-Intelligence-For-Partial-Differential?searchresult=1)

**Yizheng Wang**, Jinshuai Bai, Zhongya Lin, Qimin Wang, Cosmin Anitescu, Jia Sun, Mohammad Sadegh Eshaghi, Yuantong Gu, Xi-Qiao Feng, Xiaoying Zhuang, Timon Rabczuk, and Yinghua Liu
[**PDF**](https://asmedigitalcollection.asme.org/appliedmechanicsreviews/article/doi/10.1115/1.4071710/1232570/Artificial-Intelligence-For-Partial-Differential?searchresult=1) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
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

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/DeepBeam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Applications of scientific machine learning for the analysis of functionally graded porous beams](https://www.sciencedirect.com/science/article/pii/S0925231224018903)

**Mohammad Sadegh Eshaghi**, Mostafa Bamdad, Cosmin Anitescu, Yizheng Wang, Xiaoying Zhuang, Timon Rabczuk

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
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

[Machine learning-based estimation of soil’s true air-entry value from GSD curves](https://www.sciencedirect.com/science/article/pii/S1342937X22001885)

**Mohammad Sadegh Eshaghi**, Mohammad Rezania, Meghdad Bagheri

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/MDMM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multicriteria decision-making methods in selecting seismic upgrading strategy of high-rise RC wall buildings](https://ascelibrary.org/doi/full/10.1061/%28ASCE%29ST.1943-541X.0003304)

**Mohammad Sadegh Eshaghi**, Mohammad Sadegh Barkhordari, Zhenyu Huang, Jianqiao Ye

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/ETL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhanced teacher-learning based algorithm in real size structural optimization](https://journals.vilniustech.lt/index.php/JCEM/article/view/16387)

**Mohammad Sadegh Eshaghi**, Alireza Salehi, Alfred Strauss

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/FFPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Factors and failure patterns analysis for undrained seismic bearing capacity of strip footing above void](https://ascelibrary.org/doi/full/10.1061/%28ASCE%29GM.1943-5622.0002166)

**Mohammad Sadegh Eshaghi**, Mohsen Abbaspour, Timon Rabczuk

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/Machine_Learning-Based_Prediction.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Machine learning-based prediction of the seismic bearing capacity of a shallow strip footing over a void in heterogeneous soils](https://www.mdpi.com/1999-4893/14/10/288)

**Mohammad Sadegh Eshaghi**, Mohsen Abbaspour, Hamidreza Abbasianjahromi, Stefano Mariani

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/IJE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Straightforward prediction for responses of the concrete shear wall buildings subject to ground motions using machine learning algorithms](https://www.ije.ir/article_132523.html)

Mohammad Sadegh Barkhordari, **Mohammad Sadegh Eshaghi**

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>


<div class='paper-box-text' markdown="1">

[Evaluation of a novel Asymmetric Genetic Algorithm to optimize the structural design of 3D regular and irregular steel frames](https://link.springer.com/article/10.1007/s11709-020-0643-2)

**Mohammad Sadegh Eshaghi**,  Aydin Shishegaran, Timon Rabczuk

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box-text' markdown="1">

[Combination of sensitivity and uncertainty analyses for sediment transport modeling in sewer pipes](https://www.sciencedirect.com/science/article/pii/S1001627918303810)

Isa Ebtehaj, Hossein Bonakdari, Mir Jafar Sadegh Safari, Bahram Gharabaghi, Amir Hossein Zaji, Hossien Riahi Madavar, Zohreh Sheikh Khozani, **Mohammad Sadegh Eshaghi**, Aydin Shishegaran, Ali Danandeh Mehr

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box-text' markdown="1">

[Design of a hybrid ANFIS–PSO model to estimate sediment transport in open channels](https://link.springer.com/article/10.1007/s40996-018-0218-9)

Isa Ebtehaj, Hossein Bonakdari, **Mohammad Sadegh Eshaghi** 

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>

<div class='paper-box-text' markdown="1">

[Sediment transport modeling in rigid boundary open channels using generalize structure of group method of data handling](https://www.sciencedirect.com/science/article/pii/S0022169419306717)

Mir Jafar Sadegh Safari, Isa Ebtehaj, Hossein Bonakdari, **Mohammad Sadegh Eshaghi** 

[**PDF**](https://Pdf Link) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  Explanation
</div>
</div>



# 📝 Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/XDEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Unified AI-Driven Fracture Mechanics: TheExtended Deep Energy Method (XDEM)](https://arxiv.org/abs/2511.05888)

**Yizheng Wang**, Yuzhou Lin, Somdatta Goswami, Luyang Zhao, Huadong Zhang, Jinshuai Bai, Cosmin Anitescu, Mohammad Sadegh Eshaghi, Xiaoying Zhuang, Timon Rabczuk, Yinghua Liu

[**PDF**](https://arxiv.org/abs/2511.05888) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We propose Extended Deep Energy Method (XDEM), a unified deep learning framework that incorporates both displacement discontinuities and crack-tip asymptotics in the discrete setting, while flexibly coupling displacement and phase fields in the continuous setting.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/PFEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pretrain Finite Element Method: A Pretraining and Warm-start Framework for PDEs via Physics-Informed Neural Operators](https://arxiv.org/abs/2601.03086)

**Yizheng Wang**, Zhongkai Hao, Mohammad Sadegh Eshaghi, Cosmin Anitescu, Xiaoying Zhuang, Timon Rabczuk, Yinghua Liu

[**PDF**](https://arxiv.org/abs/2601.03086) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-   We propose a Pretrained Finite Element Method (PFEM),a physics driven framework that bridges the efficiency of neural operator learning with the accuracy and robustness of classical finite element methods (FEM).
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/LMDEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Energy Method with Large Language Model assistance: an open-source Streamlit-based platform for solving variational PDEs](https://arxiv.org/abs/2602.07838)

**Yizheng Wang**, Cosmin Anitescu, Mohammad Sadegh Eshaghi,  Xiaoying Zhuang, Timon Rabczuk, Yinghua Liu

[**PDF**](https://arxiv.org/abs/2602.07838) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
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
