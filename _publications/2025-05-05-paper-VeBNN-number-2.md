---
title: "Cooperative Bayesian and Variance Networks Disentangle Aleatoric and Epistemic Uncertainties"
collection: publications
category: conference
permalink: /publication/2025-05-XX-cooperative-bayesian-variance-networks
excerpt: "A simple yet effective cooperative training strategy that integrates a Variance estimation network with a Bayesian neural network, achieving accurate mean prediction while disentangling aleatoric and epistemic uncertainties."
date: 2025-05-05
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2505.02743"
bibtexurl: "https://arxiv.org/bibtex/2505.02743"
citation: "Yi, J. & Bessa, M. (2025). “Cooperative Bayesian and Variance Networks Disentangle Aleatoric and Epistemic Uncertainties.” arXiv preprint arXiv:2505.02743."
---

---

Real-world data contains aleatoric uncertainty - irreducible noise arising from imperfect measurements or from incomplete knowledge about the data generation process. Mean variance estimation (MVE) networks can learn this type of uncertainty but require ad-hoc regularization strategies to avoid overfitting and are unable to predict epistemic uncertainty (model uncertainty). Conversely, Bayesian neural networks predict epistemic uncertainty but are notoriously difficult to train due to the approximate nature of Bayesian inference. We propose to cooperatively train a variance network with a Bayesian neural network and demonstrate that the resulting model disentangles aleatoric and epistemic uncertainties while improving the mean estimation. We demonstrate the effectiveness and scalability of this method across a diverse range of datasets, including a time-dependent heteroscedastic regression dataset we created where the aleatoric uncertainty is known. The proposed method is straightforward to implement, robust, and adaptable to various model architectures.