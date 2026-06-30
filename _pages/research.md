---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}


## Job Market Paper
- ***Causal Inference on Quantiles in High Dimensions: A Bayesian Approach.***

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="../files/BADRQTE-DuongTrinh.pdf">pdf</a> 
  <div class="collapsible-content">
    <p style="text-align:justify;font-size:80%;">
      This paper proposes a novel approach, Bayesian Analog of Doubly Robust (BADR) estimation, to estimate unconditional Quantile Treatment Effects (QTEs) in observational studies. By augmenting the proposed estimator with shrinkage priors, this framework can account for high-dimensional covariates and feature a flexible Bayesian modeling strategy with favorable frequentist properties in finite samples, even when either the treatment assignment or outcome models are misspecified. The proposed approach offers a straightforward and adaptable implementation for incorporating probabilistic machine learning techniques to fit the propensity score and conditional cumulative distribution function, followed by combining posterior draws. This enables the effective handling of high-dimensional covariate spaces or nonlinear relationships to achieve better accuracy and appropriate uncertainty quantification. The simulation results show that BADR estimators yield a substantial improvement in bias reduction for QTE estimates compared with popular alternative estimators found in the literature. We revisit the role of microcredit expansion and loan access on Moroccan household outcomes, demonstrating how the new method adds value in characterizing heterogeneous distributional impacts on outcomes and detecting changes in overall economic inequality, which is also appealing to other applied contexts.
    </p>
  </div>
  </div>

## Research Projects

- ***Heterogeneous Peer Effects with Endogenous Network Formation*** (joint with Santiago Montoya-Blandon)

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
    <a class="button-4" href="https://arxiv.org/pdf/2606.24850">pdf</a> 
  <div class="collapsible-content" style="max-height: 80%">
    <p style="text-align:justify;font-size:80%;">
      This paper introduces a new econometric framework for modeling social interactions with heterogeneous responses to peers while addressing the endogenous formation of links. Our proposed Selection-corrected Heterogeneous Spatial Autoregressive (SCHSAR) model overcomes the limitations inherent in the spatial autoregressive (SAR) specification by achieving these dual objectives. This framework jointly models link formation and outcome determination within a unified structure. We incorporate a finite mixture structure to capture rich heterogeneity in peer effects and explicitly account for unobserved individual-specific factors driving both network formation and outcome equations, thereby addressing the network endogeneity for credible estimation of spillover effects. Standard likelihood-based methods are not well suited for the two-stage problem; therefore, for estimation and inference, we propose a fully Bayesian data augmentation approach to handle computational challenges and complex latent structure. We present a simulation study that validates our proposed approach. Our empirical application to an innovation network among U.S. firms reveals significant positive, yet heterogeneous, peer effects on corporate R\&D investments, after accounting for endogenous network formation. The findings highlight different firm behaviors and uncover notable transmitters and absorbers in response to exogenous R\&D policy shocks. This framework enables quantification of firm-level direct and spillover effects, providing valuable insights for evidence-based and targeted policy design.
    </p>
  </div>
  </div>


- ***Endogenous Selection and Spillovers: Bayesian Inference for Policy-Relevant Causal Effects***

  <div class="collapsible"> 
    <button class="button-4 collapsible-btn">abstract</button>
  <div class="collapsible-content">
    <p style="text-align:justify;font-size:80%;">
    This paper develops a new econometric framework to identify and estimate policy-relevant causal effects in contexts with endogenous selection into treatment and spillovers in single large networks or spatial settings. In such scenarios, the assumptions of unconfoundedness and the Stable Unit Treatment Value Assumption (SUTVA), commonly maintained in causal inference, are often violated. We introduce a Spillover Roy model that jointly models endogenous treatment selection and outcome determination while allowing spillovers in a form of a low-dimensional exposure mapping to neighbors’ treatment status. This structure captures heterogeneity in treatment responses across latent resistance to treatment and across exposure levels. Within this structure, we define policy-relevant effects as contrasts in outcomes across feasible policy regimes and show that total policy impacts decompose into direct effects from own participation and spillover effects from changes in neighbors’ treatment exposure. For estimation and inference, we develop Bayesian data-augmentation algorithms that enable efficient computation and coherent uncertainty quantification for causal quantities and policy counterfactuals. We demonstrate the finite-sample performance of the proposed method through Monte Carlo simulations and apply it to evaluate the Opportunity Zones (OZ) program, a U.S. place-based policy designed to stimulate economic development in distressed communities. OZ designation increases housing development directly, but spillover benefits to neighboring non-designated tracts are limited. Counterfactual policy analysis reveals diminishing, and eventually negative, marginal direct gains under large program expansions, while spillover benefits remain insufficient to offset declining direct returns. These findings highlight the importance of accounting for endogenous selection and spillovers in evaluating and redesigning of place-based policies.    </p>
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
