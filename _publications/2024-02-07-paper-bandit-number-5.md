---
title: "Hierarchize Pareto Dominance in Multi-Objective Stochastic Linear Bandits"
collection: publications
category: conference
permalink: /publication/2024-02-hierarchize-pareto-dominance
excerpt: "This paper introduces mixed Pareto-lexicographic orders for multi-objective stochastic linear bandits, allowing algorithms to capture both Pareto and lexicographic preferences via the Grossone methodology."
date: 2024-02-27
venue: "Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI-24)"
paperurl: "https://ojs.aaai.org/index.php/AAAI/article/view/29030"
bibtexurl: "https://research.tudelft.nl/en/publications/hierarchize-pareto-dominance-in-multi-objective-stochastic-linear"
citation: "Cheng, J., Xue, B., Yi, J., & Zhang, Q. (2024). “Hierarchize Pareto Dominance in Multi-Objective Stochastic Linear Bandits.” *Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI-24)*, pp. 11489–11497."
---

Multi-objective Stochastic Linear bandit (MOSLB) plays a critical role in the sequential decision-making paradigm, however, most existing methods focus on the Pareto dominance among different objectives without considering any priority. In this paper, we study bandit algorithms under mixed Pareto-lexicographic orders, which can reflect decision makers' preferences. We adopt the Grossone approach to deal with these orders and develop the notion of Pareto-lexicographic optimality to evaluate the learners' performance. Our work represents a first attempt to address these important and realistic orders in bandit algorithms. To design algorithms under these orders, the upper confidence bound (UCB) policy and the prior free lexicographical filter are adapted to approximate the optimal arms at each round. Moreover, the framework of the algorithms involves two stages in pursuit of the balance between exploration and exploitation. Theoretical analysis as well as numerical experiments demonstrate the effectiveness of our algorithms.