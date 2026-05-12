---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 5
---

<style>
  /* Make this page a bit wider so four courses can sit side by side */
  .post {
    max-width: 1500px;
  }

  .teaching-intro {
    font-size: 0.95em;
    line-height: 1.6;
    margin-bottom: 30px;
  }

  .teaching-grid {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 28px;
    width: 100%;
    max-width: 1500px;
    margin: 0 auto;
    align-items: start;
  }

  .teaching-section {
    min-width: 0;
    margin: 0;
    text-align: left;
  }

  .teaching-section h3 {
    font-size: 1.0em;
    text-align: center;
    margin-bottom: 20px;
    min-height: 48px;
    padding: 0 5px;
  }

  .teaching-section ol {
    padding-left: 22px;
    margin: 0;
  }

  .teaching-section li {
    font-size: 0.86em;
    line-height: 1.7em;
    margin-bottom: 4px;
  }

  @media (max-width: 1100px) {
    .teaching-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 700px) {
    .teaching-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<p class="teaching-intro">
  Welcome to my teaching webpage! I participated in teaching the following courses:
</p>

<div class="teaching-grid">

  <div class="teaching-section">
    <h3><a href="https://nusmods.com/courses/ST5201/statistical-foundations-of-data-science">Statistical Foundations of Data Science</a></h3>
    <ol>
      <li>Probability</li>
      <li>Random Variables</li>
      <li>Joint Distributions</li>
      <li>Expected Values</li>
      <li>Limit Theorems</li>
      <li>Parameter Estimation</li>
      <li>Hypothesis Testing</li>
      <li>Sign test</li>
      <li>Signed Rank Test</li>
      <li>Rank Sum Test</li>
    </ol>
  </div>

  <div class="teaching-section">
    <h3><a href="https://www.statslab.cam.ac.uk/Dept/People/djsteaching/teaching17.html">Statistics IB</a></h3>
    <ol>
      <li>Introduction and probability revision</li>
      <li>Estimation, bias and mean squared error</li>
      <li>Sufficiency</li>
      <li>Maximum Likelihood Estimator (MLE)</li>
      <li>Confidence Intervals</li>
      <li>Bayesian estimation</li>
      <li>Simple Hypotheses</li>
      <li>Composite hypotheses</li>
      <li>Tests of goodness-of-fit and independence</li>
      <li>Tests in contingency tables</li>
      <li>Multivariate normal theory</li>
      <li>The linear model</li>
      <li>The normal linear model</li>
      <li>Inference in the normal linear model</li>
      <li>Special cases of the linear model</li>
      <li>Hypothesis testing in the linear model</li>
    </ol>
  </div>

  <div class="teaching-section">
    <h3><a href="https://q-berthet.github.io/notes/princip_stat_complete.pdf">Principle of Statistics</a></h3>
    <ol>
      <li>Course overview</li>
      <li>Fisher information</li>
      <li>Cramer-Rao bound</li>
      <li>Stochastic convergence</li>
      <li>Central limit theorem</li>
      <li>Consistency of the MLE</li>
      <li>Asymptotic normality of MLE</li>
      <li>Plug-in MLE and Delta method</li>
      <li>Asymptotic inference with MLE</li>
      <li>Introduction to Bayesian statistics</li>
      <li>Between prior and posterior</li>
      <li>Frequentist analysis of Bayesian methods</li>
      <li>Decision theory &amp; Bayesian risk</li>
      <li>Minimax risk and admissibility</li>
      <li>Admissibility in the Gaussian model</li>
      <li>Risk of the James–Stein estimator</li>
      <li>Classification problems</li>
      <li>Multivariate analysis</li>
      <li>Principal component analysis</li>
      <li>Resampling principles &amp; the bootstrap</li>
      <li>Validity of the bootstrap</li>
      <li>Monte Carlo methods</li>
      <li>Markov chain Monte Carlo methods</li>
      <li>Introduction to Nonparametric statistics</li>
    </ol>
  </div>

  <div class="teaching-section">
    <h3><a href="https://www.statslab.cam.ac.uk/~rds37/machine_learning.html">Mathematics of Machine Learning</a></h3>
    <ol>
      <li>Review of conditional expectation</li>
      <li>Empirical risk minimisation</li>
      <li>Sub-Gaussianity and Hoeffding’s inequality</li>
      <li>Finite hypothesis classes</li>
      <li>Bounded difference inequality</li>
      <li>Rademacher complexity</li>
      <li>VC dimension</li>
      <li>Convex analysis</li>
      <li>Convex surrogates</li>
      <li>Rademacher complexity revisited</li>
      <li>Gradient descent</li>
      <li>Stochastic gradient descent</li>
      <li>Cross-validation</li>
      <li>Adaboost &amp; Gradient boosting</li>
      <li>Decision trees &amp; Random forests</li>
      <li>Feedforward neural networks</li>
    </ol>
  </div>

</div>