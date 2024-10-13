---
layout: about
title: About
permalink: /

social: true  # Includes social icons at the bottom of the page
---
<style>
  /* Overall content container setup */
  .content-area {
   justify-content: space-between; /* Distributes space between sections */
    max-width: 820px;
    margin-left:168px;
  }

  /* Text block settings */
  .text-block {
    flex: 1 0 100%; /* Text takes available space */
    text-align: justify;
    padding-right: 20px; /* Right padding to avoid touching the image */
  }

  /* Image styling */
  .profile-pic {
    float: right; /* Image floats to the right */
    max-width: 35%; /* Maximum width of the image */
    margin-left: 22px; /* Space between the image and text */
     margin-right: 34px;
     margin-top: 11px;
      margin-bottom: 1px;
      height: auto; /* Maintain aspect ratio */
  }

  /* Typography and readability improvements */
  p, li {
    font-size: 0.88em;
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
     padding-bottom:10px;
  }
  
  
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

<div class="content-area">
  <img src="./assets/img/prof_pic2.jpg" alt="Profile Picture" class="profile-pic">

 <div class="text-block">
    <p>
      I am currently a postdoctoral researcher in the Statistics Department at Stanford University, advised by Prof. <a href="https://candes.su.domains/">Emmanuel Candès</a>.  I received my Ph.D. from the Mathematics Department at the University of Cambridge, supervised by Prof. <a href="https://www.vanderschaar-lab.com/prof-mihaela-van-der-schaar/">Mihaela van der Schaar</a>. I also collaborated with Prof. <a href="http://www.statslab.cam.ac.uk/~qz280/">Qingyuan Zhao</a> on several projects related to causal inference. Prior to my Ph.D., I worked with  Dr. <a href="https://www.alpha-lee.com/alphalee">Alpha Lee</a> on  lithium-ion battery diagnosis and  low-data drug discovery.
    </p>
    <p>
Over the years, my research has spanned statistics, machine learning, and their scientific applications. In statistics, I focus on developing assumption-lean methods to analyze complex data and models. These methods can maintain statistical validity while making weaker assumptions about the data and models. Moreover, my work seeks to improve statistical power by leveraging the unique structures within each problem. Please see my related research in three different areas:
</p>
    <ul>
     <li>Uncertainty quantification for black-box models (<a href="https://arxiv.org/abs/2409.19712">link</a>).</li>
      <li>Conditional randomization tests for complex experiments (<a href="https://arxiv.org/abs/2104.10618">link</a>).</li>
      <li>Optimization-based sensitivity analysis for unmeasured confounding (<a href="https://arxiv.org/abs/2211.04697">link</a>).</li>
    </ul>
  <p>
In machine learning, I develop statistical methods to improve the performance of black-box models in prediction tasks and beyond. These methods cover model selection, learning, regularization and calibration:
</p>
    <ul>
    <li>Step-wise selection for time-series models (<a href="https://proceedings.mlr.press/v108/zhang20f">link</a>).</li>
      <li>Noise contrastive learning for data embeddings (<a href="https://proceedings.mlr.press/v151/zhang22b.html">link</a>).</li>
      <li>Data-adaptive regularization for causal inference (<a href="https://proceedings.mlr.press/v108/zhang20c.html">link1</a>, <a href="https://proceedings.neurips.cc/paper/2020/hash/17b3c7061788dbe82de5abe9f6fe22b3-Abstract.html">link2</a>).</li> 
      <li>Level-adaptive calibration for conformal prediction sets (<a href="https://arxiv.org/abs/2409.19712">link</a>).</li>
    </ul>
    <p>
In addition to my primary research areas, I enjoy exploring basic sciences and their application of statistics and machine learning. You can find my multidisciplinary work in physics and chemistry (<a href="https://www.tandfonline.com/doi/abs/10.1080/00268976.2018.1483535">link1</a>, <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.108301">link2</a>, <a href="https://pubs.rsc.org/en/content/articlehtml/2019/sc/c9sc00616h">link3</a>, <a href="https://www.nature.com/articles/s41467-020-15235-7">link4</a>).
</p>
    </div>
</div>




