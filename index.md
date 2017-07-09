## Cross Domain Recomendation

Recommender system makes recommendation for customers based on their history interest. 
Amazon recommend books, Netflix recommend movies and Facebook recommend friends, recommender system is everywhere nowadays. 

One crucial problem of recommender system is data sparsity. 
Data sparsity is raised from two aspects: first one is user-side sparsity, for most users, they have very few historical information; the second one is item-side sparisity, which means most of the attentions are focus on very few products, for the others, we do not have much feedback information.
( Notice this unbalance phenomenon is related to several basic rules of complex network theory: power-law distribution, Matthew effect, and others. ) 

Combine different data sources from different domain is one reasonable way to solve the data sparsity problem.


### Context-Adaptive Matrix Factorization

We present a new recommendation algorithm to combine the users' and items' information from different data sources. 
Based on the classical matrix factorization model, we propose a context-adaptive method for multi-context recommendation via simultaneously modeling context-specific factors and entity-intrinsic factors in a unified model.
We use a Gaussian-mixture model to combine the two information sources, and use a EM (Expectation-Maximization) method to infer the paramters of the model.
Experimental results demonstrate that our method consistently improves the prediction accuracy in both sce- narios on all the sparsity levels.

**_Authors_**: Tong Man, Huawei Shen, Junming Huang and Xueqi Cheng.

Published in **CIKM 2015 (Oral Presentation)**
[Paper](/papers/CIKM_2015.pdf)


### Cross-Domain Recommendation: An Embedding and Mapping Approach

In this work we presented an embedding-and-mapping framework for tackling cross-domain recommendation, called EMCDR. 
We first employed latent factor models to project users/items in both source and target domains into two different latent spaces. 
We then learned a mapping function between latent spaces to capture the coordinate relationship across the two domains. 
For a user/item in the target domain, we make recommendation by mapping its factor in the source domain into the target domain. 
Experiments conducted on two cross domain recommendation scenarios convincingly demonstrate that the proposed models can significantly improve the quality of cross-domain recommendation.
The framework of our model is shown as follow. 

<img src="images/CDCS.png" alt="CDCS" style="width: 300px;"/>

**_Authors_**: Tong Man, Huawei Shen, Xiaolong Jin and Xueqi Cheng

Published in **IJCAI 2017 (Oral Presentation)**
[Paper](/papers/IJCAI_2017.pdf)


