---

title: "Practical Multi-fidelity Machine Learning: Fusion of Deterministic and Bayesian Models"
collection: publications
category: manuscripts
permalink: /publication/2024-07-21-practical-multi-fidelity-ml
excerpt: "A practical multi-fidelity strategy for problems spanning low- and high-dimensional domains, integrating a non-probabilistic regression model for the low-fidelity with a Bayesian model for the high-fidelity. "
date: 2024-07-21
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2407.15110"
bibtexurl: "https://arxiv.org/bibtex/2407.15110"
citation: "Yi, J., Cheng, J., & Bessa, M. (2024). “Practical multi-fidelity machine learning: fusion of deterministic and Bayesian models.” *arXiv preprint arXiv:2407.15110*."

---

Multi-fidelity machine learning methods address the accuracy-efficiency trade-off by integrating scarce, resource-intensive high-fidelity data with abundant but less accurate low-fidelity data. We propose a practical multi-fidelity strategy for problems spanning low- and high-dimensional domains, integrating a non-probabilistic regression model for the low-fidelity with a Bayesian model for the high-fidelity. The models are trained in a staggered scheme, where the low-fidelity model is transfer-learned to the high-fidelity data and a Bayesian model is trained to learn the residual between the data and the transfer-learned model. This three-model strategy -- deterministic low-fidelity, transfer-learning, and Bayesian residual -- leads to a prediction that includes uncertainty quantification for noisy and noiseless multi-fidelity data. The strategy is general and unifies the topic, highlighting the expressivity trade-off between the transfer-learning and Bayesian models (a complex transfer-learning model leads to a simpler Bayesian model, and vice versa). We propose modeling choices for two scenarios, and argue in favor of using a linear transfer-learning model that fuses 1) kernel ridge regression for low-fidelity with Gaussian processes for high-fidelity; or 2) deep neural network for low-fidelity with a Bayesian neural network for high-fidelity. We demonstrate the effectiveness and efficiency of the proposed strategies and contrast them with the state-of-the-art based on various numerical examples and two engineering problems. The results indicate that the proposed approach achieves comparable performance in both mean and uncertainty estimation while significantly reducing training time for machine learning modeling in data-scarce scenarios. Moreover, in data-rich settings, it outperforms other multi-fidelity architectures by effectively mitigating overfitting.