# Awesome-Recommendation-Systems-Preference-Profiling

## Top Recommendation Systems & Preference Profiling Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Personalization Engines, Collaborative Filtering, Ranking Models & User Preference Learning*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Recommendation Systems & Preference Profiling**. These systems learn user preferences from interactions and content—to rank products, media, content, and next-best actions.



**Examples** include Algolia Recommend, Amazon Personalize, Dynamic Yield, Bloomreach, Coveo, Crossing Minds, Constructor.io, Klevu, Clerk.io, Recombee, and community preference tooling such as **taste-skill** (`Leonxlnx/taste-skill`).



**Open-source emphasis**: Recommender research and production libraries are richly open. **RecBole**, **Implicit**, **LightFM**, **Surprise**, **Recommenders**, **TensorFlow Recommenders**, and **LensKit** cover classical CF through deep ranking. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Personalize, Algolia Recommend, Google Recommendations AI](https://aws.amazon.com/personalize/)**  

  Cloud personalization APIs—managed training and real-time ranking on your event and catalog data.



- **[Dynamic Yield, Bloomreach, Coveo, Constructor, Klevu, Clerk.io, Recombee](https://www.dynamicyield.com/)**  

  Commerce and site-search personalization platforms—product recommendations, merchandising rules, and on-site experiences.



- **[Crossing Minds and specialty recommend APIs](https://crossingminds.com/)**  

  API-first recommendation services for apps and media.



- **[Other commercial preference & ranking platforms](https://www.coveo.com/)**  

  Additional enterprise search-and-recommend and CDP-adjacent personalization products.



## Open-Source GitHub Projects



### Full Frameworks & Algorithm Suites



- **[RecBole](https://github.com/RUCAIBox/RecBole)**  

  Open PyTorch framework with a large library of recommendation algorithms and a unified config/eval pipeline for research comparison.



- **[Recommenders (Linux Foundation)](https://github.com/recommenders-team/recommenders)**  

  Open best-practice notebooks and utilities for building and evaluating recommender systems—from classics to deep models.



- **[TensorFlow Recommenders (TFRS)](https://github.com/tensorflow/recommenders)**  

  Open TensorFlow library for retrieval and ranking models—two-tower retrieval, ranking heads, and production-oriented patterns.



- **[Microsoft Recommenders lineage / community forks](https://github.com/recommenders-team/recommenders)**  

  Widely used open examples and library code that evolved into the LF AI & Data Recommenders project.



### Classical & Implicit Feedback Libraries



- **[Implicit](https://github.com/benfred/implicit)**  

  Fast open library for implicit-feedback collaborative filtering—ALS, BPR, and related models on CPU/GPU.



- **[LightFM](https://github.com/lyst/lightfm)**  

  Open hybrid recommendation library—factorization machines for implicit and explicit feedback with side features.



- **[Surprise](https://github.com/NicolasHug/Surprise)**  

  Open Python scikit for explicit-rating collaborative filtering—easy baselines and classic algorithms.



- **[LensKit](https://github.com/lenskit/lkpy)**  

  Open toolkit for recommender research—pipelines, evaluation, and reproducible experiments.



- **[Cornac](https://github.com/PreferredAI/cornac)**  

  Open multimodal recommender framework—comparative experiments across model families.



### Ranking, Serving & Preference Tooling



- **[NVIDIA Merlin (open components)](https://github.com/NVIDIA-Merlin)**  

  Open recommender training and inference libraries aimed at large-scale GPU pipelines (NVTabular, HugeCTR, Transformers4Rec, etc.).



- **[Feature-store + ranking stacks (Feast + custom models)](https://github.com/feast-dev/feast)**  

  Open feature infrastructure commonly paired with in-house recommenders for online preference signals.



- **[taste-skill and agent preference projects](https://github.com/Leonxlnx/taste-skill)**  

  Community tooling around taste/preference profiling—useful for agent and personalization prototypes; verify API fit and maintenance.



- **[OpenSearch / Elasticsearch Learning to Rank plugins](https://github.com/o19s/elasticsearch-learning-to-rank)**  

  Open learning-to-rank extensions that turn search engines into preference-aware rankers.



### Additional Strong Open-Source Options



- **Research benchmark suite**: RecBole.

- **Implicit CF at speed**: Implicit or LightFM.

- **Teaching / classic CF**: Surprise or LensKit.

- **Deep retrieval + ranking**: TensorFlow Recommenders or Merlin components.

- **Production notebooks & patterns**: Recommenders (LF).

- **Composable stacks**: Event log → feature pipeline → Implicit/TFRS/RecBole model → ANN retrieval (Faiss/pgvector) → ranker → A/B test.

- Commercial platforms still lead for turnkey merchandising UI, real-time APIs, and commerce integrations.



**Frameworks for building custom systems**:  

**Implicit**/**LightFM** for strong collaborative baselines; **TFRS** or **Merlin** for deep retrieval/ranking; **RecBole**/**Recommenders** for experimentation; pair with **vector search** for content and cold-start.  

Fully open recommendation stacks are production-viable when you own data pipelines and evaluation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Recommenders amplify historical behavior—monitor bias, popularity concentration, and privacy (especially under GDPR/CCPA). Preference data is personal data; minimize retention and secure event streams.

- Open-source libraries offer full model control. Managed personalization APIs shift training and serving to the vendor. Neither replaces offline metrics, online experiments, and human oversight of ranking outcomes.



---



**Made for ML engineers, product teams, and anyone building personalization with owned data.**  

Let's expand open recommendation and preference-profiling systems while recognizing the merchandising and ops depth that leading commercial personalization platforms deliver.
