---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 1
---
<style>
  /* Adjust only the content area */
  .content-area {
    justify-content: space-between; /* Distributes space between sections */
    max-width: 1500px;
    align-items: flex-start; /* Aligns items at the top of their containers */
    flex-wrap: wrap; /* Allows items to wrap on smaller screens */
    }
  
    .intro-text {
    font-size: 0.9em; /* Adjust the font size of the introductory text */
    line-height:  auto; /* Increase line height for better readability */
    margin-bottom: 20px; /* Add some space after the paragraph */
  }
  
    li {
    font-size: 0.86em;
    line-height: 2.1em;
  }
  
  nav{
      font-size: 1.1em;
  }
  
  
  ul {
   line-height: 1.6 px;
    padding-left: 25px;
    list-style: disc;
  }
    
    h1 {
    font-size: 1.8em;
    text-align: center;
    padding-top:5px;
  }
  
  h3 {
    font-size: 1.0em;
        text-align: center;
  }

  
  
  

  /* Style the horizontal lines to appear bolder */
  hr {
    border: none;
    height: 1.5px; /* Adjust thickness */
    background-color: black; /* Change color */
  }
    .center-asterisk {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 25px; /* Adjust width if needed */
  }
</style>

<div class="content-area" markdown="1">

<p class="intro-text">
Welcome to my research webpage!  Below, I list my publications and preprints, where 
 <img src="../assets/img/pdf-icon.png" width="20px" alt="PDF"> : paper, 
 <img src="../assets/img/github-icon.png" width="20px" alt="GitHub"> : software, 
 <img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"> : bibtex,
and * : equal contribution. 
</p>



---
### Statistics Papers
---
- **Y. Zhang** and E. Candès. **Posterior Conformal Prediction**. Submitted, 2024. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://arxiv.org/abs/2409.19712) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/yaozhang24/pcp) <a href="../assets/bibliography/pcp.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- **Y. Zhang** and Q. Zhao. **$$L^\infty$$- and $$L^2$$-Sensitivity Analysis for Causal Inference with Unmeasured Confounding**.  Under revision in *Biometrika*, 2024. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://arxiv.org/abs/2211.04697) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/yaozhang24/l2sa) <a href="../assets/bibliography/sa.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>



- **Y. Zhang** and Q. Zhao. **Multiple Conditional Randomization Tests for Lagged and Spillover Treatment Effects**. *Biometrika*, 2024. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://arxiv.org/abs/2104.10618) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/yaozhang24/mcrt) 
<a href="../assets/bibliography/mcrt.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- **Y. Zhang** and Q. Zhao. **What is a Randomization Test?**. *Journal of the American Statistical Association*, 118(544): 2928-2942, 2023. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://arxiv.org/abs/2203.10980) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/yaozhang24/randomization)
<a href="../assets/bibliography/what.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- **Y. Zhang\*** and Z. Gao\*. **Causal Subgroup Discovery with Error Control**. In preparation.

---

### Machine Learning Papers
---

- **Y. Zhang\***, J. Berrevoets\*, and M. van der Schaar. **Identifiable Energy-based Representations: An Application to Estimating Heterogeneous Causal Effects**. 
<br>
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, PMLR 151:4158--4177, 2022.  [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.mlr.press/v151/zhang22b) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/jeroenbe/ebm-for-cate) <a href="../assets/bibliography/ebm.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- T. Kyono\*, **Y. Zhang\***, A. Bellot, and M. van der Schaar. **MIRACLE: Causally-aware Imputation via Learning Missing Data Mechanisms**. 
<br>
*Advances in Neural Information Processing Systems (NeurIPS)*, 34:23806--23817, 2021.  [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper/2021/hash/c80bcf42c220b8f5c41f85344242f1b0-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/trentkyono/MIRACLE) <a href="../assets/bibliography/causality1.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>



- Z. Qian, **Y. Zhang**, I. Bica, A. Wood, and M. van der Schaar. **Synctwin: Treatment Effect Estimation with Longitudinal Outcomes**. 
<br>
*Advances in Neural Information Processing Systems (NeurIPS)*, 34:3178--3190, 2021. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper/2021/hash/19485224d128528da1602ca47383f078-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/ZhaozhiQIAN/SyncTwin-NeurIPS-2021) <a href="../assets/bibliography/twin.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- **Y. Zhang**, A. Bellot, and M. van der Schaar. **Learning Overlapping Representations for the Estimation of Individualized Treatment Effects**. 
<br>
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, PMLR 108:1005--1014, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.mlr.press/v108/zhang20c) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/vanderschaarlab/mlforhealthlabpub/tree/75beead341138094f89c1315ec3d722030d047cb/alg/dklite) <a href="../assets/bibliography/dklite.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- **Y. Zhang**, D. Jarrett, and M. van der Schaar. **Stepwise Model Selection for Sequence Prediction via Deep Kernel Learning**. 
<br>
*International Conference on Artificial Intelligence and Statistics (AISTATS)*, PMLR 108:2304--2314, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.mlr.press/v108/zhang20f) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/vanderschaarlab/mlforhealthlabpub/tree/75beead341138094f89c1315ec3d722030d047cb/alg/smsdkl) <a href="../assets/bibliography/step.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- **Y. Zhang** and M. van der Schaar. **Gradient Regularized $$V$$-Learning for Dynamic Treatment Regimes**. 
<br>
*Advances in Neural Information Processing Systems (NeurIPS)*, 33:2245--2256, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper/2020/hash/17b3c7061788dbe82de5abe9f6fe22b3-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/vanderschaarlab/mlforhealthlabpub/tree/75beead341138094f89c1315ec3d722030d047cb/alg/grv) <a href="../assets/bibliography/gradient.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- H. Lee\*, **Y. Zhang\***, W. Zame, C. Shen, J. Lee, and  M. van der Schaar. **Robust Recursive Partitioning for Heterogeneous Treatment Effects with Uncertainty Quantification**. 
*Advances in Neural Information Processing Systems (NeurIPS)*, 33:2282--2292, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper_files/paper/2020/hash/1819020b02e926785cf3be594d957696-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/vanderschaarlab/mlforhealthlabpub/tree/75beead341138094f89c1315ec3d722030d047cb/alg/r2p-hte) <a href="../assets/bibliography/r2p.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- T. Kyono\*,  **Y. Zhang\***, and M. van der Schaar. **CASTLE: Regularization via Auxiliary Causal Graph Discovery**. 
<br>
*Advances in Neural Information Processing Systems (NeurIPS)*, 33:1501--1512, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper/2020/hash/1068bceb19323fe72b2b344ccf85c254-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/vanderschaarlab/mlforhealthlabpub/tree/75beead341138094f89c1315ec3d722030d047cb/alg/castle) <a href="../assets/bibliography/castle.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>
   
- J. Yoon, **Y. Zhang**, J. Jordon, and M. van der Schaar. **VIME: Extending The Success of Self-and Semi-Supervised Learning to Tabular Domain**. 
<br>
*Advances in Neural Information Processing Systems (NeurIPS)*, 33:11033--11043, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper_files/paper/2020/hash/7d97667a3e056acab9aaf653807b4a03-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/jsyoon0823/VIME) <a href="../assets/bibliography/vime.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>



- J. Crabbe,  **Y. Zhang**, and M. van der Schaar. **Learning Outside the Black-box: the Pursuit of Interpretable Models**. 
<br>
*Advances in Neural Information Processing Systems (NeurIPS)*, 33:17838--17849, 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://proceedings.neurips.cc/paper/2020/hash/ce758408f6ef98d7c7a7b786eca7b3a8-Abstract.html) [<img src="../assets/img/github-icon.png" width="20px" alt="GitHub">](https://github.com/JonathanCrabbe/Symbolic-Pursuit) <a href="../assets/bibliography/box.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>

---

### Scientific Papers
---
- S. Becker, **Y. Zhang**, and A. A. Lee.  **Geometry of Energy Landscapes and the Optimizability of Deep Neural Networks**. *Physical Review Letters*, 124(10), 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.108301) <a href="../assets/bibliography/geometry.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>


- Y. Zhang, Q. Tang, **Y. Zhang**, J. Wang, U. Stimming, and A. A. Lee. **Identifying Degradation Patterns of Li-ion Batteries from Impedance Spectroscopy using Machine Learning**. 
*Nature Communications*, 11(1), 2020. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://www.nature.com/articles/s41467-020-15235-7) <a href="../assets/bibliography/battery.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>

- **Y. Zhang** and A. A. Lee. **Bayesian Semi-supervised Learning for Uncertainty-calibrated Prediction of Molecular Properties and Active Learning**. 
<br> *Chemical Science*, 10(35), 8154-8163, 2019. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://pubs.rsc.org/en/content/articlelanding/2019/sc/c9sc00616h) <a href="../assets/bibliography/drug.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>

-  **Y. Zhang**, A. M. Saxe, M. S. Advani, and A. A. Lee. **Energy–Entropy Competition and the Effectiveness of Stochastic Gradient Descent in Machine Learning**. 
<br>
*Molecular Physics*, 116(21-22), 3214-3223, 2018. [<img src="../assets/img/pdf-icon.png" width="20px" alt="PDF">](https://www.tandfonline.com/doi/full/10.1080/00268976.2018.1483535) <a href="../assets/bibliography/entropy.txt" target="_blank"><img src="../assets/img/bibtex-icon.png" width="20px" alt="BibTeX"></a>

</div>

