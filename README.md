# RMAB

Dynamic Optimization Approach to Proportional Recommendation Systems via Restless Bandits

Keywords: Whittle Index; Restless Multi-armed Bandits; MPI Policy; Recommender System

In the dynamic landscape of the use of recommendation systems in video platforms, the quest for effective personalization strategies remains paramount, we need to identify what each user is really interested in. This paper delves into the intricate realm of recommendation algorithms, centering on the utilization of Restless Multi-Armed Bandits model to enhance adaptive personalization. Based on the inherent interests of each user and immediate behavioral history, gradually explore the potential interests. We consider different content pushed to users as an arm in RMAB and show the model is indexable, then formulate the Whittle index. Moreover, with the wide-scale application of today’s recommendation algorithms, the "Information Cocoon" effect is gradually exposed, for expanding the users’ more possible interests, in order for recommendation algorithms to be sustainable in the long term, we have developed a proportional strategy. Also we present an idea of cluster in optimizing running speed and retrieving relevant information according to user needs.

We want to “tailor” a recommendation algorithm for each user, centred on their interests. Furthermore, we not only need to push the content of the user’s known preferences, but also gradually develop the user’s new interests, push brand-new content, observe the user’s acceptance and then continue to repeat the process, so that the user will always keep a sense of freshness, to engage users. In addition, under the existing recommendation system framework, we want to maximise the range of user’s interests, so as to balance the breadth and depth.

We introduce the Restless Multi-Armed Bandits model (RMAB) to the recommendation system, since its inception in a seminal paper by Whittle in the late 1980s, it has been widely investigated, researched and applied, and the variety of papers and applications has evolved to the present day. 

RMAB has been known to be PSPACE-hard, due to its huge storage capacity and the computations that even a supercomputer cannot perform, we consider the use of heuristic algorithms.

The approach we are presenting in this paper is a polyhedral approach to compute the index, known as marginal productivity index policy, based on partial conservation laws (PCLs). Under the PCL framework, we could imply the sub-optimality of index policies, and obtain sufficient conditions for the existence of Whittle index (indexability), and also an adaptive-greedy index algorithm.

Let's do it.
