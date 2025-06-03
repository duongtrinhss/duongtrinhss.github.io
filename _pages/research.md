---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}


## Job Market Paper
- ***Causal Inference on Quantiles in High Dimensions: A Bayesian Approach.*** (2024).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="../files/BADRQTE-DuongTrinh.pdf">pdf</a> 
    <a class="button-4" href="../files/BADRQTEslides.pdf">slides</a> 
  <div class="collapsible-content">
    <p style="text-align:justify;font-size:80%;">
      This paper proposes a novel approach, Bayesian Analog of Doubly Robust (BADR) estimation, to estimate unconditional Quantile Treatment Effects (QTEs) in observational studies. By augmenting the proposed estimator with shrinkage priors, this framework can account for high-dimensional covariates and feature a flexible Bayesian modeling strategy with favorable frequentist properties in finite samples, even when either the treatment assignment or outcome models are misspecified. The proposed approach offers a straightforward and adaptable implementation for incorporating probabilistic machine learning techniques to fit the propensity score and conditional cumulative distribution function, followed by combining posterior draws. This enables the effective handling of high-dimensional covariate spaces or nonlinear relationships to achieve better accuracy and appropriate uncertainty quantification. The simulation results show that BADR estimators yield a substantial improvement in bias reduction for QTE estimates compared with popular alternative estimators found in the literature. We revisit the role of microcredit expansion and loan access on Moroccan household outcomes, demonstrating how the new method adds value in characterizing heterogeneous distributional impacts on outcomes and detecting changes in overall economic inequality, which is also appealing to other applied contexts.
    </p>
  </div>
  </div>

## Research Projects

- ***Modeling Interactions with Heterogeneous Effects and Endogeneous Network Formation*** (joint with Santiago Montoya-Blandon) (2025).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      This paper introduces a new econometric framework for modeling network interactions with heterogeneous effects, while addressing the issue of network endogeneity. Our proposed Selection-corrected Heterogeneous Spatial Autoregressive (SCHSAR) model overcomes the limitations inherent in the standard spatial autoregressive (SAR) specification by achieving these dual objectives. We incorporate a finite mixture structure to capture rich heterogeneity in network interaction effects and explicitly model link formation, with latent variables playing a crucial role. For estimation and inference, our fully Bayesian approach effectively handles the computational challenges arising from the complex likelihood function and latent structure. We present a simulation study that validates the proposed approach. Our empirical application to an innovation network among American firms reveals significant positive, yet heterogeneous, interaction effects on corporate R\&D investments, after accounting for endogenous network formation. The findings highlight different firm behaviors and uncover notable transmitters and absorbers in response to exogenous R\&D policy shocks. This framework enables quantification of firm-level direct and spillover effects, providing valuable insights for evidence-based and targeted policy design.
    </p>
  </div>
  </div>


- ***Bayesian Causal Inference in the Presence of Endogenous Selection into Treatment and Spillovers.*** (2024).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="../files/BayesianCIESslides.pdf">slides</a> 
  <div class="collapsible-content">
    <p style="text-align:justify;font-size:80%;">
      This paper proposes a new approach utilizing network or spatial data to identify and estimate direct and indirect causal effects amid selection-on-unobservables and spillovers. This situation occurs due to the violation of unconfoundedness and SUTVA assumptions, typically assumed in causal inference literature but often implausible in many economic scenarios. Our devised framework nests the Generalized Roy Model to explicitly account for endogenous selection into treatment, while capturing spillovers through exposure mapping to neighbors' treatment. This allows for heterogeneous effects across individuals and enables the exploration of various causal estimands beyond the mean. We develop Bayesian estimators based on data augmentation methods, offering efficient computation and proper uncertainty quantification. We design a simulation study to assess the performance of the proposed approach using both  calibrated synthetic data and real friendship network data from the Add-Health study. Finally, we apply our method to evaluate the Opportunity Zones (OZ) program, which aims to stimulate economic growth in distressed U.S. census tracts through tax incentives. Our results show both direct and indirect positive impacts on housing unit growth in designated Qualified Opportunity Zones (QOZs), but unselected tracts (non-QOZs) experience no beneficial spillovers, remaining at a disadvantage. The differences between QOZs and non-QOZs imply extending the positive effects to non-QOZs seems unlikely. Moreover, our model predicts that offering investment tax credits to non-QOZs would even lead to negative outcomes, making the program's expansion to these areas ineffective.
    </p>
  </div>
  </div>

- ***A Comparative Review of Bayesian Shrinkage and Variable Selection in Econometrics.*** (joint with Dimitris Korobilis, Kenichi Shimizu) (2022).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="/research/kst">notes</a> 
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      Despite the abundance of shrinkage and variable selection priors proposed in statistics, large-scale comparisons of their performance in econometric applications remain limited. This study aims to investigate the robustness of Bayesian prior configurations across different settings, including high-dimensional scenarios that deviate from the benchmark linearity and Gaussian assumptions. We consider 10 hierarchical priors and tackle computation using  the Gibbs sampler. Our focus is on prediction, and we explore whether theoretical guarantees for Bayesian priors hold in time-series models with conditionally dependent likelihoods. Furthermore, we are interested in if Bayesian priors can serve as data-driven mechanisms in problems with large parameter spaces where case-by-case prior elicitation is impractical. Methodologically, this study contributes to the existing literature through two exercises. The first setting examines models with multiple structural breaks. We transform an inherently nonlinear problem into a linear high-dimensional one and assess the performance of approaches utilizing shrinkage and variable selection priors. An application on the forecasts of country-level Covid-19 infections is considered. In the second exercise, we investigate the forecasting performance as we move from a small vector autoregression (VAR) model with shrinkage to larger dimensions, wherein these priors facilitate automatic or minimal tuning. Our findings aim to provide insights into the robustness and applicability of Bayesian priors in diverse settings.
    </p>
  </div>
  </div>
  
- ***Inference on Treatment Effects with High-dimensional Controls: Frequentist and Bayesian Approaches.*** M.Res. Dissertation (2021).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="../files/MResDissertation-DuongTrinh.pdf">pdf</a> 
    <a class="button-4" href="../files/MResDissertation-slides.pdf">slides</a> 
  <div class="collapsible-content">
    <p style="text-align:justify;font-size:80%;">
      Causal inference in observational studies is particularly challenging when the number of potential control variables is large relative to the sample size. The dissertation examines Frequentist and Bayesian regularization-based methods for inference on treatment effects in high-dimensional settings. We focus on a linear outcome regression model under the Unconfoundedness assumption, comparing Post-Double-Selection Lasso (PDSLasso) method from the frequentist perspective with a generalized High-dimensional Confounding Adjustment (HDCA) framework which incorporates different Bayesian shrinkage priors. Through extensive Monte Carlo simulations and an empirical illustration, the study investigates the finite-sample performance of these methods across various data-generating processes. Key findings include: 1. Regularization-based methods outperform traditional approaches using OLS estimation in high-dimensional settings; 2. PDSLasso shows superior performance in high-sparsity designs but struggles in low-sparsity scenarios; 3. Among HDCA methods, performance varies across the choice of Bayesian shrinkage priors and hyperparameters; 4.There is a link between variable selection and causal inference performance in the Bayesian approach. 
    </p>
  </div>
  </div>

- ***Government disclosure in the pandemic.*** (2020).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="../files/GovernmentDisclosure-DuongTrinh.pdf">pdf</a> 
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      Motivated by the pandemic Covid-19, this paper aims to explore the optimal policy for public information release during an epidemic by employing the framework of Information Design and Bayesian Persuasion. The paper formulates a model of government information disclosure to the public and, based on theoretical analysis, predicts that when the Government possesses commitment power, any partial information disclosure with a partition structure is better than no information disclosure but not as good as full information disclosure, in terms of ex-ante social welfare.
    </p>
  </div>
  </div>

- ***Early career gender wage gap: First evidence in Vietnam.*** (joint with Anh Nguyen Ngoc, Hai Doan Ma, Thuc Hoang Kim). Paper presented at *11th Vietnam Economist Annual Meeting* (2018).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      This paper examines the gender wage gap during the transition from school to work period in Vietnam, utilizing the Oaxaca decomposition method and the Heckman sample selection procedure. Leveraging the unique data from the Vietnam School-to-Work Transition Surveys 2015 (VSWTS 2015) for youngsters, we uncover some meaningful findings about early career wages. Firstly, some determinants of early career wages are confirmed, consistent with human capital theory. Actual working experience, highest level of education, and job tenure significantly impact hourly wages. In line with job shopping theory, the level of job mobility has a negative effect on wages in several cases. Secondly, the analysis reveals a wage gap between young males and females. Although young female workers tend to possess advantageous endowments that positively impact earnings, their average wage is lower than that of their male counterparts. The wage gap even widens when work characteristics are considered. This unexplained wage gap is typically implied as gender discrimination in the literature. Lastly, there is evidence that two gender groups self-select differently into the wage employment sector. Nonemployed women might possess higher productivity-related characteristics versus employed counterparts, and if they worked as salaried employees, they would earn more than actual wage workers on average. Taking this into account slightly reduces the wage gap.
    </p>
  </div>
  </div>

## Published Papers (predoc)
- ***Firm export and the impact of foreign ownership in Vietnam: A micro-data analysis.*** (joint with Vinh Nguyen Thi Thuy), *Journal of Economic Development* (2020), 45(1).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="https://jed.cau.ac.kr/archives/45-1/45-1-7.pdf">pdf</a> 
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      This paper investigates the impact of foreign ownership on firm exports in Vietnam and analyzes how export participation and export intensity vary with ownership status by comparing Foreign Direct Investment enterprises (FDI enterprises) versus domestic firms, and wholly-foreign-owned enterprises (WFs) versus foreign joint ventures (JVs). Using data from 2010-2015 Vietnamese Enterprise Survey (VES), we document that after controlling for firm characteristics, industry, and region, FDI enterprises have higher export participation and higher export intensity than local firms. The finding supports the hypothesis that FDI enterprises inherit from foreign firms competitive advantages and therefore become superior in exports. We also find that while export participation is similar between JVs and WFs, export intensity is significantly higher for WFs than for JVs. This suggests that export-oriented foreign investors tend to establish 100% foreign-owned companies to exploit advantages of labor costs or natural resources, while domestic-oriented firms tend to form joint ventures to penetrate the domestic market.
    </p>
  </div>
  </div>

- ***The impact of exchange rate volatility on exports in Vietnam: A bounds testing approach.*** (joint with Vinh Nguyen Thi Thuy), *Journal of Risk and Financial Management* (2019), 12(1).

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="https://www.mdpi.com/1911-8074/12/1/6">pdf</a> 
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      This paper investigates the impact of exchange rate volatility on exports in Vietnam, using data spanning from the opening quarter of 2000 to the final quarter of 2014. The paper applies the autoregressive distributed lag (ARDL) bounds testing approach to the analysis of level relationships between effective exchange rate volatility and exports. Employing the demand function of exports, the paper also considers the effect of depreciation and foreign income on exports in Vietnam. The results unveil that exchange rate volatility negatively affects the export volume in the long run, as anticipated. A depreciation of the domestic currency affects exports negatively in the short run, but positively in the long run, which aligns with the J curve effect. Surprisingly, an increase in the real income of a foreign country actually leads to a decrease in Vietnamese export volume. These findings suggest some policy implications in managing the exchange rate system and promoting exports in Vietnam.
    </p>
  </div>
  </div>
