### Hi, I studied at Guangdong Technion-Israel Institute of Technology and I am taking Berkeley courses now. I have started to deposite my works publically in Github since 2022 June 10 for some PNAS papers.

There are six papers and codes deposited here. I introduced them in a time series. 

The first one is "Infer metabolic directions from moment differences of mass-weighted intensity distributions". It proposed a method to infer the metabolic directions by analyzing the metabolomics dataset without requiring annotating the structures of spectra. Two new metabolic directions, duobolic and centrabolic, are deduced by estimating the second central moment of the mass-weighted intensity distributions.

This work was finished two years ago after a thought about how to address the replicability issue in biology, and later I shared to some professors. I registered the domain, http://directome.org and http://biomathematics.org in January, 2022. It is prepared for a PNAS brief report but later I realized the mean and moment estimators are critical in this method, so I started to develop robust moment estimators and found that Hodges-Lehamnn estimator and median standard deviation proposed by Bickel and Lehmann are the best in this case. Therefore this work was posponed to this stage. https://www.researchgate.net/publication/377974502_Infer_metabolic_directions_from_moment_differences_of_mass-weighted_intensity_distributions

The second one is "Matrix dissimilarity from the differences of moments and sparsity". It classified current dissimilarity measures into two groups: mean dissimilarities and sparisity dissimilarities, and proposed a new class of dissimilarity measures call standard deviation dissimilarity. This method can delineate the key factors underlying group differences. For example, in biology, mean dissimilarity indicates differences driven by up/down-regulated gene expressions, standard deviation dissimilarity reflects the heterogeneity of response to treatment, and sparsity dissimilarity corresponds to differences prompted by the activation/silence of genes.

This work was also initiated two years ago, and I shared to some professors for collaboration. It is also prepared for PNAS. Later I realized the moment estimator is also critical in this method, so I started to develop robust moment estimators. Therefore this work was posponed to this stage. https://www.researchgate.net/publication/377974505_Matrix_dissimilarities_based_on_differences_in_moments_and_sparsity

The third one is "Robust estimations from distribution structures: I. Mean." This work has been publically deposited in this Github since one year ago for a PNAS paper (I hidden some previous versions after updated new versions, https://github.com/tubanlee/SRM16). It introduced a new semiparametric method to classify distributions based on the asymptotic orderliness of quantile combinations. From that, it can explain why the Winsorized mean, Hodges-Lehmann estimator, and median of means often has better performance compared to the trimmed mean in terms of bias. Also, a serious of new robust location estimators were deduced, while nearly all common nonparametric robust location estimators were found to be special cases thereof. https://www.researchgate.net/publication/377973944_Robust_estimations_from_distribution_structures_I_Mean

The fourth one is "Robust estimations from distribution structures: II. Central Moments." This work has been publically deposited in this Github since one year ago for another PNAS paper (I hidden some previous versions after updated new versions, https://github.com/tubanlee/NRS3333, the traffics were very high when I deposited, but I removed the stars later according to the requirement of PNAS). Besides the above reasons, it was also partial inspired by Lindquist and Rachev (2021)'s PNAS comment to Brown et al’s paper: "What are the proper measures for the location, spread, asymmetry, and dependence (association) for random samples with infinite mean?" It revisited Hodges and Lehmann's pioneering work about the pairwise difference distribution. It showed that the kth central moment kernel distribution (the U-statistics structure of the central moment) has a nice structure that if it is generated from a unimodal distribution, it is always nearly unimodal with mode and median close to zero. Also, it has another nice structure that it is nearly congruent, i.e., all its symmetric weighted averages (symmetric L-estimators) will change in the same direction as the parameter of the original distribution changed. https://www.researchgate.net/publication/377974264_Robust_estimations_from_distribution_structures_II_Central_Moments 

The fifth one is "Robust estimations from distribution structures: III. Invariant Moments." This work has been publically deposited in this Github since one year ago also for the same PNAS as Central Moments, but later I was suggested to split the paper into two different papers. It introduced a parametric method to develop estimators that are consistent not only for a parametric distribution, but also for a semiparametric distribution, e.g., the recombined mean is developed as a robust mean estimator that is not only consistent for the symmetric distribution, but also consistent for a skewed distribution, therefore, it has nice property for nearly all common unimodal distributions, even when the distribution has a heavy tailed, especially if the skewed distribution is the exponential distribution. It also developed methods for constructing estimators that are consistent for one or even multiple shape-scale distributions, and how to select the optimal estimator in terms of root mean square errors. It further introduced a new way to measure robustness to departures/distributional shift. 
https://www.researchgate.net/publication/377974419_Robust_estimations_from_distribution_structures_III_Invariant_Moments

The sixth one is "Robust estimations from distribution structures: V. Non-asymptotic." This work has been publically deposited in this Github since one year ago for a PNAS brief report (I hidden some previous versions after updated new versions, e.g., https://github.com/tubanlee/FiniteSampleBias, the traffic is also very high, but I later removed the stars and watchers according to the requirement of PNAS). It decomposited the finite sample distribution of the uniform distribution into several highly ordered sequences, including arithematic sequence, beta sequence with different shapes (from beta distribution), and their mixtures. It was found that such decomposition is valid with relatively high accuracy (when the sample size is 16, the accuracy is about 95%). It reveals the underlying ordered structure of randomness and can greatly reduce the computational cost in finite sample bias correction. https://www.researchgate.net/publication/377974622_Robust_estimations_from_distribution_structures_V_Non-Asymptotic

I am introducing all these works in YouTube and Quora, if you are interested, please visit: https://www.youtube.com/@Iobiomathematics or https://www.quora.com/profile/Tuobang-Li-1/answers . 

Also, they have been deposited in Zenodo and Researchgate, 

Tuobang Li. (2023). Infer metabolic momentum from moment differences of mass-weighted intensity distributions. Zenodo. https://doi.org/10.5281/zenodo.10616979

Tuobang Li. (2023). Matrix dissimilarities based on differences in moments and sparsity. Zenodo. https://doi.org/10.5281/zenodo.10406288 

Tuobang Li. (2023). Robust estimations for semiparametric models: Mean. https://doi.org/10.5281/zenodo.6629988

Tuobang Li. (2022). Robust estimations for semiparametric models: Moments. https://doi.org/10.5281/zenodo.8127703

Tuobang Li. (2023). Robust estimations from distribution structures: V. Non-asymptotic. https://doi.org/10.5281/zenodo.10616689 

Feel free to share it or contact tl@biomathematics.org, for more materials available by request.

view counts since 2024, February, 7th
![Visitor Count](https://profile-counter.glitch.me/{tubanlee}/count.svg)

<!--
**tubanlee/tubanlee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
