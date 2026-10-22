---
layout: single
title: "Research"
permalink: /research-interests/
author_profile: true
---

We use mathematical and statistical models to understand infectious disease outbreaks while they are still unfolding, so that public health agencies can act on timely evidence. Much of this work is done with the Epidemic Intelligence Center of [Taiwan Centers for Disease Control](https://www.cdc.gov.tw/En) (Taiwan CDC) and with long-standing collaborators in Japan, South Korea, the United Kingdom and Canada. A second line of work applies the same statistical toolkit to non-communicable diseases.

## Real-time outbreak analytics and forecasting

Since 2020 we have provided analyses to Taiwan CDC as epidemics developed. During the COVID-19 surge of 2021 we prepared weekly assessments of the epidemic, and our real-time forecasts informed decisions of the Central Epidemic Command Center, including an early warning in May 2021 of the date range in which Taiwan would reach 10,000 cases ([Akhmetzhanov et al., 2022](https://doi.org/10.3201/eid2810.220456)). In 2023–2025, Taiwan CDC projects combined vaccination records with blood-donor serosurveys to estimate the evolving immune landscape and the fraction of infections that were ascertained.

Current projects develop these tools further: a National Science and Technology Council (NSTC) project on forecasting emerging and re-emerging infectious diseases (2024–2027) and an NTU Higher Education Sprout project on ensemble and AI-based methods for infectious disease forecasting (2026). We also work towards a collaborative scenario-modeling hub for respiratory viruses with partners in Taiwan, Japan, South Korea and the United States.

## Transmission dynamics and epidemiological time intervals

How quickly does a pathogen spread, and how long between infection and symptoms, or between successive cases? We estimate reproduction numbers, incubation periods, serial intervals and generation times from outbreak data, paying particular attention to the biases that arise in real time: right truncation, interval censoring and the correlation between delays. Examples include best-practice guidance for estimating and reporting delay distributions ([Charniga et al., 2024](https://doi.org/10.1371/journal.pcbi.1012520)), a meta-analysis of the incubation period of Omicron subvariants ([Akhmetzhanov et al., 2025](https://doi.org/10.1111/irv.70171)), serial interval and intervention efficiency in the 2024 pertussis outbreak in South Korea ([Akhmetzhanov et al., 2026](https://doi.org/10.3201/eid3205.251304)), and the transmission potential of a hospital outbreak of the Epsilon variant in Taiwan ([Akhmetzhanov et al., 2021](https://doi.org/10.1016/j.ijid.2021.06.028)).

## Emerging and re-emerging infections

We study outbreaks of pathogens for which data are scarce and decisions are urgent:

- **Mpox:** the 2022 global outbreak ([Ponce et al., 2024](https://doi.org/10.3201/eid3006.231095); [Akhmetzhanov et al., 2022](https://doi.org/10.1016/j.ijid.2022.07.044)), the 2023 epidemic in mainland China ([Akhmetzhanov & Wu, 2024](https://doi.org/10.7717/peerj.16908)) and transmission in Taiwan in 2023–2024 (Taiwan CDC project).
- **Filoviruses and other high-consequence pathogens:** the 2022 Sudan virus disease outbreak in Uganda ([de Padua et al., 2025](https://doi.org/10.1016/S2214-109X(24)00555-2)), Bundibugyo virus ([de Padua & Akhmetzhanov, 2026](https://doi.org/10.3201/eid3210.261175)), Ebola and Marburg virus outbreaks in Africa, and the transmission potential of Andes virus ([Akhmetzhanov et al., 2026](https://doi.org/10.1016/j.lanmic.2026.101549)).
- **Outbreaks in Taiwan and the region:** the 2023 dengue outbreak in southern Taiwan, the first documented outbreak of bongkrekic acid food poisoning in Taiwan ([Akhmetzhanov et al., 2026](https://doi.org/10.1016/j.jiph.2025.103056)), and African swine fever in China ([Akhmetzhanov et al., 2024](https://doi.org/10.1017/S0950268824000086)).

## Beyond infectious diseases

The same statistical methods help answer questions in other areas of public health: delay-adjusted excess mortality in the United States ([Akhmetzhanov, 2021](https://doi.org/10.1017/S0950268821001527)) and in mainland China after the end of the zero-COVID policy ([Fung et al., 2026](https://doi.org/10.1017/S0950268826101022)), the efficacy of immunotherapy for advanced hepatocellular carcinoma ([Shao & Akhmetzhanov, 2025](https://doi.org/10.1159/000542576)), and the burden of chronic kidney disease ([Wu et al., 2024](https://doi.org/10.1136/bmjopen-2023-082959)). Earlier work covered cancer prevention dynamics, evolutionary biology, optimal control and differential games.

## Methods

Bayesian inference with Stan, survival analysis under truncation and censoring, renewal-equation and compartmental models, systematic reviews and meta-analysis, and forecasting with ensemble methods. Analyses are written in R, Python and Stan, and code for published work is shared on [GitHub](https://github.com/aakhmetz).

## Funding

- National Science and Technology Council (NSTC), forecasting of emerging and re-emerging infectious diseases, principal investigator, 2024–2027
- NTU Higher Education Sprout Project, ensemble and AI-based methods for infectious disease forecasting, principal investigator, 2026
- Taiwan CDC commissioned projects on COVID-19 modeling (2023–2025) and mpox transmission in Taiwan (2024), principal investigator
- NSTC, COVID-19 transmission in Taiwan, principal investigator, 2022–2023
- NSTC, genomic epidemiology of tuberculosis in Kaohsiung, co-principal investigator, 2023–2026

## Collaborators

Hiroshi Nishiura (Kyoto University), Sung-mok Jung (South Korea), Robin N. Thompson (University of Oxford), Jonathan Dushoff (McMaster University), Hao-Yuan Cheng (Taiwan CDC), and colleagues at the NTU College of Public Health and National Taiwan University Hospital.
