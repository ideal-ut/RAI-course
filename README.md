# Spring 2019 - EE 381V - SPEC TPCS IN MACHINE LEARNING (16725)
--------------------------

**Course Outline**:
<!-- TOC -->
- [Prerequisites](#prerequisites)
- [Scope](#scope)
- [Instructors](#instructors)
- [Schedule and Format](#schedule_and_format)

<!-- /TOC -->

------------------------------

### Prerequisites 

Pre-reqs: At least one graduate course completed in Data Mining/Machine Learning. Online courses do not count. 

------------------------------

### Scope

This is an advanced, seminar-oriented course. We shall study recently published papers relevant to the development of responsible and trustworthy data driven automated decision systems. Solid background in pattern recognition/machine learning is assumed. Key topics include building explainable ML models, black-box explainability, algorithmic fairness, adversarial ML, robust statistical modeling, and privacy aware data mining. Coursework will mainly involve paper presentations, critiques and discussion, a mini coding-based project and a major term project on developing some aspects of a responsible ML system.

------------------------------

### Instructors

- Instructor: Dr. Joydeep Ghosh
- TA: Diego Garcia-Olano

------------------------------
### Schedule and Format

Tuesday/Thursday: 12:30 - 2 ECJ 1.312

- Overview		2 classes
- Explainability	 (P)	7 classes
- Fairness (P)		6 classes
- Assurance (P)		5 classes
- Guest Speaker	4 classes
- Minor project		1 class	 (mid March)
- Major project		3 classes (late April)

Topics marked by (P) are student-led presentations. Each such class will cover 2 papers, spending 35 minutes per paper as follows: lead group 20 mins, critiquing group, 5 minutes; discussion 10 mins.

Every alternate class marked (P) will include a 5 minute quiz at the beginning of the class.

------------------------------

### Explainability
| Presentation Order | Type | Reading | Year | Venue |
| -- | ---- | ------- | ---- | ----- |
|1a|interpretable models|[Distill-and-Compare: Auditing Black-Box Models Using Transparent Model Distillation](https://arxiv.org/abs/1710.06169)|2018|AAAI|
|1b|interpretable models|[Learning qualitatively diverse and interpretable rules for classification](https://arxiv.org/abs/1806.08716)|2018|arxiv|
|2a|black-box explainability|[Understanding Black-Box Predictions via Influence Functions](http://proceedings.mlr.press/v70/koh17a/koh17a.pdf)|2017|ICML|
|2b|black-box explainability|[Anchors: High-Precision Model Agnostic Explanations](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf)|2018|AAAI|
|3a|black-box explainability|[Explanations based on the Missing: Towards Contrastive Explanations with Pertinent Negatives](https://arxiv.org/abs/1802.07623)|2018|NIPS|
|3b|black-box explainability|[A Unified Approach to Interpreting Model Predictions](http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions)|2017|NIPS|
|4a|black-box explainability|[Local Rule-Based Explanations of Black Box Decision Systems](https://arxiv.org/abs/1805.10820)|2018|arxiv|
|4b|neural network oriented|[Deep Learning for Case-Based Reasoning through Prototypes: A Neural Network that Explains Its Predictions](https://arxiv.org/pdf/1710.04806)|2018|AAAI|
|5a|neural network oriented|[Layer-wise relevance propagation for neural networks with local renormalization layers](https://arxiv.org/pdf/1604.00825.pdf)|2016|ICANN|
|5b|neural network oriented|[Streaming Weak Submodularity: Interpreting Neural Networks on the Fly](https://github.com/eelenberg/streak)|2017|NIPS|
|6a|neural network oriented|[Rationalizing Neural Predictions](https://people.csail.mit.edu/taolei/papers/emnlp16_rationale.pdf)|2016|EMNLP|
|6b|recourse/causal|[Actionable Recourse in Linear Classification](https://arxiv.org/pdf/1809.06514.pdf)|2018|arxiv|
|7a|philosophy|[The mythos of model interpretability](https://arxiv.org/pdf/1606.03490)|2016|ICML|
|7b|philosophy|[Towards a rigorous science of interpretable machine learning](https://arxiv.org/pdf/1702.08608.pdf)|2017|arxiv|

### Fairness
| Presentation Order | Type | Reading | Year | Venue |
| -- | ---- | ------- | ---- | ----- |
|8a|toolkit|[AI FAIRNESS 360](https://arxiv.org/pdf/1810.01943.pdf)|2018|Arxiv|
|8b|bias detection|[Fast Threshold Tests for Detecting Discrimination](https://arxiv.org/pdf/1702.08536)|2018|AISTATS|
|9a|formalism|[On formalizing fairness in prediction with machine learning](http://www.fatml.org/media/documents/formalizing_fairness_in_prediction_with_ml.pdf)|2018|ICML|
|9b|pre-processing|[Optimized Pre-Processing for Discrimination Prevention](http://krvarshney.github.io/pubs/CalmonWVRV_nips2017.pdf)|2017|NIPS|
|10a|in-processing|[Mitigating Unwanted Biases with Adversarial Learning](https://arxiv.org/pdf/1801.07593.pdf)|2018|AAAI|
|10b|in-processing|[Classification with Fairness Constraints: A Meta-Algorithm with Provable Guarantees](https://arxiv.org/pdf/1806.06055.pdf)|2019|ACM|
|11a|post-processing|[Equality of Opportunity in Supervised Learning](https://papers.nips.cc/paper/6374-equality-of-opportunity-in-supervised-learning.pdf)|2016|NIPS|
|11b|post-processing|[On Fairness and Calibration](https://papers.nips.cc/paper/7151-on-fairness-and-calibration.pdf)|2017|NIPS|
|12a|causal|[Causal Reasoning for Algorithmic Fairness](https://arxiv.org/pdf/1805.05859.pdf)|2018|arxiv|
|12b|temporal|[Delayed Impact of Fair Machine Learning](https://arxiv.org/pdf/1803.04383.pdf)|2018|ICML|
|13a|ranking|[Fairness of Exposure in Rankings](https://arxiv.org/pdf/1802.07281.pdf)|2018|KDD|
|13b|ranking|[Towards a Fair Marketplace: Counterfactual Evaluation of the trade-off between Relevance, Fairness & Satisfaction in Recommendation Systems](http://fernando.diaz.nyc/CIKM2018-marketplace-mehrotra.pdf)|2018|ACM|
|14a||[Controlling Polarization in Personalization: An Algorithmic Framework](https://dl.acm.org/citation.cfm?doid=3287560.3287601)|2019|FATML|

### Assurance
| Presentation Order | Type | Reading | Year | Venue |
| -- | ---- | ------- | ---- | ----- |
|15a|data integrity|[Datasheets for Datasets](https://arxiv.org/pdf/1803.09010.pdf)|2018|PMLR|
|15b|data integrity|[Mitigating poisoning attacks on machine learning models: A data provenance based approach](https://dl.acm.org/citation.cfm?id=3140450)|2017|ACM|
|16a|overview|[Making Machine Learning Robust Against Adversarial Inputs](https://cacm.acm.org/magazines/2018/7/229030-making-machine-learning-robust-against-adversarial-inputs/fulltext)|2018|ACM|
|16b|causality|[Reliable Decision Support Using Counterfactual Models](https://arxiv.org/pdf/1703.10651.pdf)|2017|NIPS|
|17a|tool|[ART sec 1-5 Nicolae, Maria-Irina, et al. 2018. “Adversarial Robustness Toolbox v0.3.0.”](https://arxiv.org/pdf/1807.01069.pdf)|2018||
|17b|tool|[ART sec 6-10](https://arxiv.org/pdf/1807.01069.pdf)|2018||
|18a|DL specific|[Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/pdf/1706.06083.pdf)|2018|ICLR|
|18b|DL specific|[Decomposition of uncertainty in Bayesian deep learning for efficient and risk-sensitive learning](http://proceedings.mlr.press/v80/depeweg18a/depeweg18a.pdf)|2018|ICML|
|19a|outliers|[Generative Adversarial Active Learning for Unsupervised Outlier Detection](http://arxiv.org/abs/1809.10816)|2018|arxiv|
|19b|outliers|[Theoretical Foundations and Algorithms for Outlier Ensembles](https://www.kdd.org/exploration_files/Article4.pdf)|2015|SIGKDD|
|20a|bias mitigation|[Uncovering and Mitigating Algorithmic Bias through Learned Latent Structure](http://www.aies-conference.com/wp-content/papers/main/AIES-19_paper_220.pdf)|2019|AAAI|
|20b|bias mitigation|[Why is my classifier Discriminatory?](https://papers.nips.cc/paper/7613-why-is-my-classifier-discriminatory.pdf)|2018|NIPS|
|21a|security/privacy|[Model Reconstruction from Model Explanations](https://arxiv.org/pdf/1807.05185.pdf)|2019|FATML|
|21b|software process/evaluation|[Model Cards for Model Reporting](https://arxiv.org/pdf/1810.03993.pdf)|2019|FATML|
