# network-learning-via-ranking
This repository contains my Bachelor's thesis about "Network Learning via Ranking". I submitted my thesis in August 2017.

## Supervisors
* [Professor Dr. Stephan Günnemann, Technical University of Munich](http://www.kdd.in.tum.de/team/guennemann/)
* [Oleksandr Shchur](http://www.kdd.in.tum.de/team/oleksandr-shchur/)
* [Aleksandar Bojchevski](http://www.kdd.in.tum.de/team/bojchevski/)

## Abstract
Networks are used in a variety of scientific fields to model arbitrarily large and complex systems. Therefore many graph algorithms have been developed to solve tasks like clustering or link prediction. The outcome of many of these algorithms is influenced by edge weights. Unfortunately, these weights might often not be given which could lead to suboptimal performance. In many cases there is, however, some knowledge about a ranking which describes the importance of a certain node in the network.

This thesis aims to develop methods to recover edge weights for these cases. Essentially, we intend to solve an inverse ranking problem where an unweighted graph and a ranking are given and the goal is to find an edge weight assignment such that the ranking computed on the weighted graph corresponds to the given target ranking. We introduce algorithms which are able to solve this weight recovery task if they are either given the numerical ranking scores for nodes or even if only a ranking order is given. These algorithms also work if only a partial ranking consisting of the scores or the order of the k most important nodes is given.

We furthermore evaluate whether Network Learning can have a positive impact on Data Mining and Machine Learning algorithms on graphs by conducting experiments on the influence of edge weights on the performance of spectral clustering and link prediction.

