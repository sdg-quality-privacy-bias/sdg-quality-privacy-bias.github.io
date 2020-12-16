---
layout: page
title: Synthetic Data Generation
subtitle: Quality, Privacy, Bias
use-site-title: true
---

# Call for Papers
Data is the most valuable ingredient of machine learning models to help researchers and companies make informed decisions. However, access to rich, diverse, and clean datasets may not always be possible. One of the reasons for the lack of rich datasets is the substantial amount of time needed for data collection, especially when dealing with rare events or manual annotation is required. Another reason is the need for protecting privacy, whenever raw data contains sensitive information about individuals and hence cannot be shared directly.

A powerful solution that can address both of these challenging scenarios is generating synthetic data. Thanks to the recent advances in generative models, it is possible to create realistic synthetic samples that closely match the distribution of complex, real data. In the case of limited labeled data, synthetic data can be used to augment training data to mitigate overfitting \citep{chen2019faketables, wang2018high}. In the case of protecting privacy, data curators can share the synthetic data instead of the original data, where the utility of the original data is preserved but privacy is protected \citep{choi2017generating,chen2019faketables,hayes2019logan,neurips20chen,chen20ccs}.

Despite the substantial benefits from using synthetic data, the process of synthetic data generation is still an ongoing technical challenge \citep{tantipongpipat2019differentially, yoon2019time, jordon2018measuring, dieleman2018challenge, finance, zhao2019infovae, zhao2018bias,yu20eccv}. Although the two scenarios of limited data and privacy concerns share similar technical challenges such as quality and fairness, they are often studied separately. We invite researchers to submit papers that discuss challenges and advances in synthetic data generation, including but not limited to the following topics.
How can we evaluate the quality of synthetically generated datasets?
How can we handle mixed-type datasets such as tabular data with both categorical and continuous variables?
How can we generate synthetic samples to augment rare samples or limited labeled data?
How can we address privacy violations, measure privacy leakage, and provide probable privacy guarantees?
How can we retain semantic meaning of original samples in the synthetic data?
What are the right datasets/applications/benchmarks to propel this research area forward?
How can we measure and mitigate biases, and thereby ensure fairness in data synthesis?


### Important Dates 

<!--{% include dates.md %} <a href="{site.url}/2020/img/KR2ML2020_template.zip">NeurIPS paper format (adapted)</a>. -->
**Submission:** February 26, 2021 (Anywhere on Earth) <br>
**Notification:** March 26, 2021
 <br>
**Workshop:** May 8, 2021

### Submission Requirements

Submissions to KR2ML 2020 are limited to 4 pages of content, but may contain an unlimited number of pages for references and appendices. The latter may not necessarily be read by the reviewers. We request and recommend that authors rely on the supplementary material only to include minor details (e.g., hyperparameter settings, reproducibility information, etc.) that do not fit in the 4 pages. The submission process is double-blind.

All submissions must be formatted with LaTeX using the [NeurIPS paper format (adapted)](img/KR2ML2020_template.zip).

All accepted papers will be presented in a virtual poster session, and some will be selected for oral presentation. We welcome articles currently under review or papers planned for publication elsewhere. However, papers that have been published at an ML conference should not be submitted. Accepted papers will be published on the KR2ML homepage, but are to be considered non-archival. 

Submission Link: [XXX](XXX)

Please email any enquiries to [XXX](mailto:XXX)

### Best Paper Awards
Three best paper awards will selected, based on scientific merit, impact, and clarity. A $500.00 USD cash prize will be awarded to the 1st prize best paper. Best paper awards are nominated by program committee and judged by the Best Paper award committee. 

Award sponsor:<br>
<a href='https://www.amazon.science/'><img src="{{site.url}}/img/amazon_science.png" height="140px"></a>


