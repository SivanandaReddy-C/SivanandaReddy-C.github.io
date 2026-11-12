---
title: "Sensitivity of Threshold Value ‘r’in Approximate Entropy Based Brain-Computer Interface"
collection: publications
category: conferences
permalink: /publication/2025-06-08-paper-title-number-5
excerpt: ''
date: 2023-10-27
venue: 'IEEE'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10455140/'
citation: 'C. S. Reddy and M. Ramasubba Reddy, "Sensitivity of Threshold Value ‘r’ in Approximate Entropy based Brain-Computer Interface," 2023 7th International Conference on Computer Applications in Electrical Engineering-Recent Advances (CERA), Roorkee, India, 2023, pp. 1-6, doi: 10.1109/CERA59325.2023.10455140.'
---

Approximate entropy(ApEN) is an algorithm to determine complexity in a data series based on the existence of patterns. Its calculation requires the determination of two unknown parameters, m, and r. Even though the r recommended in the range of 0.1 to 0.2 times standard deviation works well for a variety of applications, in certain cases, it causes misinterpretation as the largest possible complexity in a data series may not always comes with this range of r. It led to motivating another recommendation for r, choosing the one that gives maximum ApEN. This paper addresses the implementation of motor imagery (MI) classification with ApEN as a method of feature extraction. While assessing the classification accuracy by varying r from 0.1 to 0.4, it has been shown that neither of the two recommendations for r leads to the best result. The hypothesis behind this is, in the MI classification problem, beyond the maximum ApEN, it is the ApEN discrimination between classes during the MI activity that decides its performance. Therefore, r is recommended to be the one with large ApEN discrimination during MI activity. Results show the highest accuracy at this r. To trace out the time interval of maximum MI activity, another feature extraction strategy based on auto-regressive (AR) modeling coefficients is implemented. Finally, a combined feature extraction strategy based on AR and ApEN is evaluated, and improved accuracy over individual AR or ApEN strategies can be observed only for r from the proposed recommendation.
