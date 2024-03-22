---
title: "Temporal Metrics Based Aggregated Graph Convolution Network for traffic forecasting"
collection: Neurocomputing

excerpt: 'Traffic flow forecasting, Spatio-Temporal convolution network, Intelligent Transportation System, Reachable region Temporal metric'
date: 2023-08-22
venue: 'Neurocomputing'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0925231223007853'
citation: 'Fangshu Chen, Yanqiang Qi, Jiahui Wang, Lu Chen, Yufei Zhang, Linxiang Shi. Temporal metrics based aggregated graph convolution network for traffic forecasting[J]. Neurocomputing, 2023, 556: 126662.'
---

Traffic forecasting is one of the most well-studied problems in the Intelligent Transportation Systems (ITS). However, existing studies mainly utilize Euclidean distance or road network distance as the metrics at the spatial level, where the distance between two points is calculated based on the GPS coordinates. When using the spatial level metrics to construct the road network’s topological and indexing structure, two completed unrelated road segments such as the upper and lower levels of the viaduct will be contiguous in the adjacent matrix and consequently be indexed in the same block. However, it may taking a long time to drive through these two road segments, which makes the spatial proximity meaningless, and this is pretty common during the morning and evening rush hours. Thus, it is very important to take into consideration of the temporal metric along with the spatial distance metric when dealing with the traffic forecasting problem. Motivated by the above observation, we propose a novel Temporal Metrics Based Aggregated Graph Convolution Network (TMAGCN), which utilize the time reachability based road network weight metric, and reveal its unique characteristics. TMAGCN mainly consists of three components: spatio-temporal reachability calculation, region clustering(road segments aggregating), and traffic flow forecasting. We explore the cluster of road segments and the reconstruction of the spatio-temporal reachability graph with temporal-level information rather than spatial-level information for better capturing the latent region information. To the best of our knowledge, this paper is the first attempt on this problem. The comprehensive experiments indicate that TMAGCN achieves higher accuracy and efficiency than other off-the-shelf models.
