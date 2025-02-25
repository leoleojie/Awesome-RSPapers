Awesome-RSPapers
================

Included Conferences: SIGIR 2020, SIGKDD 2020, RecSys 2020, CIKM 2020,
AAAI 2021, WSDM 2021, WWW 2021, SIGIR 2021



-   [Task](#task)
    -   [Collaborative Filtering](#collaborative-filtering)
    -   [Sequential/Session-based
        Recommendations](#sequentialsession-based-recommendations)
    -   [Knowledge-aware
        Recommendations](#knowledge-aware-recommendations)
    -   [Feature Interactions](#feature-interactions)
    -   [Conversational Recommender
        System](#conversational-recommender-system)
    -   [Social Recommendations](#social-recommendations)
    -   [News Recommendation](#news-recommendation)
    -   [Text-aware Recommendations](#text-aware-recommendations)
    -   [POI](#poi)
    -   [Online Recommendations](#online-recommendations)
    -   [Group Recommendation](#group-recommendation)
    -   [Multi-task/Multi-behavior/Cross-domain
        Recommendations](#multi-taskmulti-behaviorcross-domain-recommendations)
    -   [Other Task](#other-task)
-   [Topic](#topic)
    -   [Debias in Recommender
        System](#debias-in-recommender-system)
    -   [Fairness in Recommender
        System](#fairness-in-recommender-system)
    -   [Attack in Recommender
        System](#attack-in-recommender-system)
    -   [Explanation in Recommender
        System](#explanation-in-recommender-system)
    -   [Long-tail/Cold-start in
        Recommendations](#long-tailcold-start-in-recommendations)
    -   [Diversity in Recommendations](#diversity-in-recommendations)
    -   [Evaluation](#evaluation)
-   [Technique](#technique)
    -   [Pre-training in Recommender
        System](#pre-training-in-recommender-system)
    -   [Reinforcement Learning in
        Recommendations](#reinforcement-learning-in-recommendations)
    -   [Knowledge Distillation in
        Recommendations](#knowledge-distillation-in-recommendations)
    -   [NAS in Recommendations](#nas-in-recommendations)
    -   [Federated Learning in
        Recommendations](#federated-learning-in-recommendations)
    -   [GNN in Recommendations](#gnn-in-Recommendations)
-   [Analysis](#analysis)
-   [Other](#other)

Task
----

### Collaborative Filtering

-   HCFRec: Hash Collaborative Filtering via Normalized Flow with Structural
Consensus for Efficient Recommendation. IJCAI 2022 [为hash-CF学习最优哈希码]

-   LightGCN: Simplifying and Powering Graph Convolution Network for
    Recommendation. SIGIR 2020

-   Deep Critiquing for VAE-based Recommender Systems. SIGIR 2020

-   Neighbor Interaction Aware Graph Convolution Networks for
    Recommendation. SIGIR 2020

-   A Framework for Recommending Accurate and Diverse Items Using
    Bayesian Graph Convolutional Neural Networks. KDD 2020

-   Dual Channel Hypergraph Collaborative Filtering. KDD 2020

-   Probabilistic Metric Learning with Adaptive Margin for Top-K
    Recommendation. KDD 2020

-   Content-Collaborative Disentanglement Representation Learning for
    Enhanced Recommendation. RecSys 2020

-   Neural Collaborative Filtering vs. Matrix Factorization Revisited.
    RecSys 2020

-   Bilateral Variational Autoencoder for Collaborative Filtering. WSDM
    2021

-   Learning User Representations with Hypercuboids for Recommender
    Systems. WSDM 2021

-   Local Collaborative Autoencoders. WSDM 2021

-   A Scalable, Adaptive and Sound Nonconvex Regularizer for Low-rank
    Matrix Completion. WWW 2021

-   HGCF: Hyperbolic Graph Convolution Networks for Collaborative
    Filtering. WWW 2021

-   High-dimensional Sparse Embeddings for Collaborative Filtering. WWW
    2021

-   Collaborative Filtering with Preferences Inferred from Brain
    Signals. WWW 2021

-   Interest-aware Message-Passing GCN for Recommendation. WWW 2021

-   Neural Collaborative Reasoning. WWW 2021

-   Sinkhorn Collaborative Filtering. WWW 2021

-   Disentangling User Interest and Conformity for Recommendation with
    Causal Embedding. WWW 2021
    
-   Bootstrapping User and Item Representations for One-Class Collaborative 
    Filtering. SIGIR 2021

-   When and Whom to Collaborate with in a Changing Environment: A Collaborative Dynamic Bandit Solution. SIGIR 2021

-   Neural Graph Matching based Collaborative Filtering. SIGIR 2021

-   Enhanced Graph Learning for Collaborative Filtering via Mutual Information Maximization. SIGIR 2021


### Sequential/Session-based Recommendations

-   MLP4Rec: A Pure MLP Architecture for Sequential Recommendations. IJCAI 2022 [利用MLP捕捉商品特征中的序列关系]

-   Enhancing Sequential Recommendation with Graph Contrastive Learning. IJCAI 2022 [用于序列推荐的图对比学习]

-   Disentangling Long and Short-Term Interests for Recommendation. WWW 2022 [利用自监督对比学习解耦长短期兴趣]

-   Efficient Online Learning to Rank for Sequential Music Recommendation. WWW 2022 [将搜索空间限制在此前表现不佳的搜索方向的正交补上]

-   Filter-enhanced MLP is All You Need for Sequential Recommendation. www 2022 [通过可学习滤波器对用户序列进行编码]

-   Generative Session-based Recommendation. WWW 2022 [构建生成器来模拟用户序列行为，从而改善目标序列推荐模型]

-   GSL4Rec: Session-based Recommendations with Collective
Graph Structure Learning and Next Interaction Prediction. WWW 2022 [图结构学习+推荐]

-   Intent Contrastive Learning for Sequential Recommendation. WWW 2022 [利用用户意图来增强序列推荐]

-   Learn from Past, Evolve for Future: Search-based Time-aware Recommendation with Sequential Behavior Data. WWW 2022 [检索相关历史行为并融合当前序列行为]

-   Sequential Recommendation via Stochastic Self-Attention. WWW 2022 [通过随机高斯分布和Wasserstein自注意力模块来引入不确定性]

-   Sequential Recommendation with Decomposed Item Feature Routing. WWW 2022 [解耦item特征，并分别利用软硬模型来路由最有特征序列]
  
-   Towards Automatic Discovering of Deep Hybrid Network Architecture for Sequential Recommendation. WWW 2022 [通过NAS来搜索每一层使用注意力/卷积模块]

-   Unbiased Sequential Recommendation with Latent Confounders. WWW 2022 [去除潜在混淆变量来实现无偏序列推荐]

-   Re4: Learning to Re-contrast, Re-attend, Re-construct for Multi-interest Recommendation. WWW 2022 [通过re-contrast,re-attend,re-construct来增强解耦用户多兴趣表示]

-   Sequential Recommendation with Self-attentive Multi-adversarial
    Network. SIGIR 2020

-   KERL: A Knowledge-Guided Reinforcement Learning Model for Sequential
    Recommendation. SIGIR 2020

-   Modeling Personalized Item Frequency Information for Next-basket
    Recommendation. SIGIR 2020

-   Incorporating User Micro-behaviors and Item Knowledge into
    Multi-task Learning for Session-based Recommendation. SIGIR 2020

-   GAG: Global Attributed Graph Neural Network for Streaming
    Session-based Recommendation. SIGIR 2020

-   Next-item Recommendation with Sequential Hypergraphs. SIGIR 2020

-   A General Network Compression Framework for Sequential Recommender
    Systems. SIGIR 2020

-   Make It a Chorus: Knowledge- and Time-aware Item Modeling for
    Sequential Recommendation. SIGIR 2020

-   Global Context Enhanced Graph Neural Networks for Session-based
    Recommendation. SIGIR 2020

-   Self-Supervised Reinforcement Learning for Recommender Systems.
    SIGIR 2020

-   Time Matters: Sequential Recommendation with Complex Temporal
    Information. SIGIR 2020

-   Controllable Multi-Interest Framework for Recommendation. KDD 2020

-   Disentangled Self-Supervision in Sequential Recommenders. KDD 2020

-   Handling Information Loss of Graph Neural Networks for Session-based
    Recommendation. KDD 2020

-   Contextual and Sequential User Embeddings for Large-Scale Music
    Recommendation. RecSys 2020

-   FISSA:Fusing Item Similarity Models with Self-Attention Networks for
    Sequential Recommendation. RecSys 2020

-   From the lab to production: A case study of session-based
    recommendations in the home-improvement domain. RecSys 2020

-   Recommending the Video to Watch Next: An Offline and Online
    Evaluation at YOUTV.de. RecSys 2020

-   SSE-PT:Sequential Recommendation Via Personalized Transformer.
    RecSys 2020

-   Improving End-to-End Sequential Recommendations with Intent-aware
    Diversification. CIKM 2020

-   Quaternion-based self-Attentive Long Short-term User Preference
    Encoding for Recommendation. CIKM 2020

-   Sequential Recommender via Time-aware Attentive Memory Network. CIKM
    2020

-   Star Graph Neural Networks for Session-based Recommendation. CIKM
    2020

-   Dynamic Memory Based Attention Network for Sequential
    Recommendation. AAAI 2021

-   Noninvasive Self-Attention for Side Information Fusion in Sequential
    Recommendation. AAAI 2021

-   Self-Supervised Hypergraph Convolutional Networks for Session-based
    Recommendation. AAAI 2021

-   An Efficient and Effective Framework for Session-based Social
    Recommendation. WSDM 2021

-   Sparse-Interest Network for Sequential Recommendation. WSDM 2021

-   Dynamic Embeddings for Interaction Prediction. WWW 2021

-   Session-aware Linear Item-Item Models for Session-based
    Recommendation. WWW 2021

-   RetaGNN: Relational Temporal Attentive Graph Neural Networks for
    Holistic Sequential Recommendation. WWW 2021

-   Adversarial and Contrastive Variational Autoencoder for Sequential
    Recommendation. WWW 2021

-   Future-Aware Diverse Trends Framework for Recommendation. WWW 2021

-   DeepRec: On-device Deep Learning for Privacy-Preserving Sequential
    Recommendation in Mobile Commerce. WWW 2021

-   Linear-Time Self Attention with Codeword Histogram for Efficient
    Recommendation. WWW 2021
    
-   Category-aware Collaborative Sequential Recommendation. SIGIR 2021

-   Sequential Recommendation with Graph Convolutional Networks. SIGIR 2021

-   Dual Attention Transfer in Session-based Recommendation with Multi Dimensional Integration. SIGIR 2021

-   Unsupervised Proxy Selection for Session-based Recommender Systems. SIGIR 2021

-   StackRec: Efficient Training of Very Deep Sequential Recommender Models by Iterative Stacking. SIGIR 2021

-   Counterfactual Data-Augmented Sequential Recommendation. SIGIR 2021

-   CauseRec: Counterfactual User Sequence Synthesis for Sequential Recommendation. SIGIR 2021

-   The World is Binary: Contrastive Learning for Denoising Next Basket Recommendation. SIGIR 2021

-   Motif-aware Sequential Recommendation. SIGIR 2021

-   Lighter and Better: Low-Rank Decomposed Self-Attention Networks for Next-Item Recommendation. SIGIR 2021


### Knowledge-aware Recommendations

-   CKAN: Collaborative Knowledge-aware Attentive Network for
    Recommender Systems. SIGIR 2020

-   Attentional Graph Convolutional Networks for Knowledge Concept
    Recommendation in MOOCs in a Heterogeneous View. SIGIR 2020

-   MVIN: Learning multiview items for recommendation. SIGIR 2020

-   Jointly Non-Sampling Learning for Knowledge Graph Enhanced
    Recommendation. SIGIR 2020

-   Joint Item Recommendation and Attribute Inference: An Adaptive Graph
    Convolutional Network Approach. SIGIR 2020

-   Leveraging Demonstrations for Reinforcement Recommendation Reasoning
    over Knowledge Graphs. SIGIR 2020

-   SimClusters Community-Based Representations for Heterogenous
    Recommendations at Twitter. KDD 2020

-   Multi-modal Knowledge Graphs for Recommender Systems. CIKM 2020

-   DisenHAN Disentangled Heterogeneous Graph Attention Network for
    Recommendation. CIKM 2020

-   Genetic Meta-Structure Search for Recommendation on Heterogeneous
    Information Network. CIKM 2020

-   TGCN Tag Graph Convolutional Network for Tag-Aware Recommendation.
    CIKM 2020

-   Knowledge-Enhanced Top-K Recommendation in Poincaré Ball. AAAI 2021

-   Graph Heterogeneous Multi-Relational Recommendation. AAAI 2021

-   Knowledge-Enhanced Hierarchical Graph Transformer Network for
    Multi-Behavior Recommendation. AAAI 2021

-   Alleviating Cold-Start Problems in Recommendation through
    Pseudo-Labelling over Knowledge Graph. WSDM2021

-   Decomposed Collaborative Filtering Modeling Explicit and Implicit
    Factors For Recommender Systems. WSDM 2021

-   Temporal Meta-path Guided Explainable Recommendation. WSDM 2021

-   Learning Intents behind Interactions with Knowledge Graph for
    Recommendation. WWW 2021

### Feature Interactions

-   APG: Adaptive Parameter Generation Network for Click-Through Rate Prediction. NIPS 2022 [点击率预测的自适应参数生成网络]


-   Detecting Beneficial Feature Interactions for Recommender Systems.
    AAAI 2021

-   DeepLight: Deep Lightweight Feature Interactions for Accelerating
    CTR Predictions in Ad Serving. WSDM 2021

-   Multi-Interactive Attention Network for Fine-grained Feature
    Learning in CTR Prediction. WSDM 2021

-   FM\^2: Field-matrixed Factorization Machines for CTR Prediction. WWW
    2021

### Conversational Recommender System

-   Towards Question-based Recommender Systems. SIGIR 2020

-   Improving Conversational Recommender Systems via Knowledge Graph
    based Semantic Fusion. KDD 2020

-   Interactive Path Reasoning on Graph for Conversational
    Recommendation. KDD 2020

-   A Ranking Optimization Approach to Latent Linear Critiquing for
    Conversational Recommender Systems. RecSys 2020

-   What does BERT know about books, movies and music： Probing BERT for
    Conversational Recommendation. RecSys 2020

-   Adapting User Preference to Online Feedback in Multi-round
    Conversational Recommendation. WSDM 2021

-   A Workflow Analysis of Context-driven Conversational Recommendation.
    WWW 2021
    
-   Unified Conversational Recommendation Policy Learning via Graph-based Reinforcement Learning. SIGIR 2021

-   Learning to Ask Appropriate Questions in Conversational Recommendation. SIGIR 2021

-   Comparison-based Conversational Recommender System with Relative Bandit Feedback. SIGIR 2021

### Social Recommendations

-   Partial Relationship Aware Influence Diffusion via a Multi-channel
    Encoding Scheme for Social Recommendation. CIKM 2020

-   Random Walks with Erasure: Diversifying Personalized Recommendations
    on Social and Information Networks. WWW 2021

-   Dual Side Deep Context-aware Modulation for Social Recommendation.
    WWW 2021

-   Self-Supervised Multi-Channel Hypergraph Convolutional Network for
    Social Recommendation. WWW 2021

### News Recommendation

-   FeedRec: News Feed Recommendation with Various User Feedbacks. WWW 2022 [融入各类显示/隐式反馈来建模用户兴趣]

-   KRED:Knowledge-Aware Document Representation for News
    Recommendations. RecSys 2020

-   News Recommendation with Topic-Enriched Knowledge Graphs. CIKM 2020

-   The Interaction between Political Typology and Filter Bubbles in
    News Recommendation Algorithms. WWW 2021
    
-   Personalized News Recommendation with Knowledge-aware News Interactions. SIGIR 2021

-   Joint Knowledge Pruning and Recurrent Graph Convolution for News Recommendation. SIGIR 2021


### Text-aware Recommendations

-   TAFA: Two-headed Attention Fused Autoencoder for Context-Aware
    Recommendations. RecSys 2020

-   Set-Sequence-Graph A Multi-View Approach Towards Exploiting Reviews
    for Recommendation. CIKM 2020

-   TPR: Text-aware Preference Ranking for Recommender Systems. CIKM
    2020

-   Leveraging Review Properties for Effective Recommendation. WWW 2021

### POI

-   Modeling Spatio-temporal Neighbourhood for Personalized Point-of-interest Recommendation. IJCAI 2022 [融入知识图谱和时域信息，实现个性化POI推荐]

-   Next Point-of-Interest Recommendation with Inferring Multi-step Future Preferences.IJCAI 2022 [考虑用户未来偏好]

-   HME: A Hyperbolic Metric Embedding Approach for Next-POI
    Recommendation. SIGIR 2020

-   Spatial Object Recommendation with Hints: When Spatial Granularity
    Matters. SIGIR 2020

-   Geography-Aware Sequential Location Recommendation. KDD 2020

-   Learning Graph-Based Geographical Latent Representation for
    Point-of-Interest Recommendation. CIKM 2020

-   STP-UDGAT Spatial-Temporal-Preference User Dimensional Graph
    Attention Network for Next POI Recommendation. CIKM 2020

-   STAN: Spatio-Temporal Attention Network for next Point-of-Interest
    Recommendation. WWW 2021

-   Incremental Spatio-Temporal Graph Learning for Online Query-POI
    Matching. WWW 2021

### Online Recommendations

-   Gemini: A novel and universal heterogeneous graph information fusing
    framework for online recommendations. KDD 2020

-   Maximizing Cumulative User Engagement in Sequential Recommendation
    An Online Optimization Perspective. KDD 2020

-   Exploring Clustering of Bandits for Online Recommendation System.
    RecSys 2020

-   Contextual User Browsing Bandits for Large-Scale Online Mobile
    Recommendation. RecSys 2020

-   A Hybrid Bandit Framework for Diversified Recommendation. AAAI 2021

### Group Recommendation

-   GAME: Learning Graphical and Attentive Multi-view Embeddings for
    Occasional Group Recommendation. SIGIR 2020

-   GroupIM: A Mutual Information Maximizing Framework for Neural Group
    Recommendation. SIGIR 2020

-   Group-Aware Long- and Short-Term Graph Representation Learning for
    Sequential Group Recommendation. SIGIR 2020

### Multi-task/Multi-behavior/Cross-domain Recommendations

-   Collaborative Filtering with Attribution Alignment for Review-based Non-overlapped Cross Domain Recommendation. WWW 2022 [通过属性对齐实现基于评论的跨域推荐]

-   Differential Private Knowledge Transfer for Privacy-Preserving Cross-Domain Recommendation. WWW 2022 [通过可微隐私知识迁移实现源域隐私保护的跨域推荐]

-   MetaBalance: Improving Multi-Task Recommendations via Adapting Gradient Magnitudes of Auxiliary Tasks. WWW 2022 [动态保持辅助任务和目标任务的梯度在同一个量级]

-   A Contrastive Sharing Model for Multi-Task Recommendation. WWW 2022 [使用对比掩码来解决多任务中的参数冲突问题]

-   Transfer Learning via Contextual Invariants for One-to-Many
    Cross-Domain Recommendation. SIGIR 2020

-   CATN: Cross-Domain Recommendation for Cold-Start Users via Aspect
    Transfer Network. SIGIR 2020

-   Multi-behavior Recommendation with Graph Convolution Networks. SIGIR
    2020

-   Parameter-Efficient Transfer from Sequential Behaviors for User
    Modeling and Recommendation. SIGIR 2020

-   Web-to-Voice Transfer for Product Recommendation on Voice. SIGIR
    2020

-   Jointly Learning to Recommend and Advertise. KDD 2020

-   Progressive Layered Extraction (PLE) A Novel Multi-Task Learning
    (MTL) Model for Personalized Recommendations. RecSys 2020

-   Whole-Chain Recommendations. CIKM 2020

-   Personalized Approximate Pareto-Efficient Recommendation. WWW 2021

-   Federated Collaborative Transfer for Cross-Domain Recommendation. SIGIR 2021

-   Learning Domain Semantics and Cross-Domain Correlations for Paper Recommendation. SIGIR 2021

-   Graph Meta Network for Multi-Behavior Recommendation with Interaction Heterogeneity and Diversity. SIGIR 2021

### Other Task

-   Hierarchical Fashion Graph Network for Personalized Outfit
    Recommendation. SIGIR 2020

-   Octopus: Comprehensive and Elastic User Representation for the
    Generation of Recommendation Candidates. SIGIR 2020

-   Goal-driven Command Recommendations for Analysts. RecSys 2020

-   MultiRec: A Multi-Relational Approach for Unique Item Recommendation
    in Auction Systems. RecSys 2020

-   PURS: Personalized Unexpected Recommender System for Improving User
    Satisfaction. RecSys 2020

-   RecSeats: A Hybrid Convolutional Neural Network Choice Model for
    Seat Recommendations at Reserved Seating Venues. RecSys 2020

-   Live Multi-Streaming and Donation Recommendations via Coupled
    Donation-Response Tensor Factorization. CIKM 2020

-   Learning to Recommend from Sparse Data via Generative User Feedback.
    AAAI 2021

-   Real-time Relevant Recommendation Suggestion. WSDM 2021

-   Heterogeneous Graph Augmented Multi-Scenario Sharing Recommendation
    with Tree-Guided Expert Networks. WSDM 2021

-   FINN: Feedback Interactive Neural Network for Intent Recommendation.
    WWW 2021

-   Drug Package Recommendation via Interaction-aware Graph Induction.
    WWW 2021

-   Large-scale Comb-K Recommendation. WWW 2021

-   Variation Control and Evaluation for Generative Slate
    Recommendations. WWW 2021

-   Diversified Recommendation Through Similarity-Guided Graph Neural
    Networks. WWW 2021

-   Clicks can be Cheating: Counterfactual Recommendation for Mitigating Clickbait Issue. SIGIR 2021

-   UGRec: Modeling Directed and Undirected Relations for Recommendation. SIGIR 2021

-   Learning Recommender Systems with Implicit Feedback via Soft Target Enhancement. SIGIR 2021

-   PreSizE: Predicting Size in E-Commerce using Transformers. SIGIR 2021

-   Path-based Deep Network for Candidate Item Matching in Recommenders. SIGIR 2021

-   A Study of Defensive Methods to Protect Visual Recommendation Against Adversarial Manipulation of Images. SIGIR 2021


Topic
-----

### Debias in Recommender System

-   Trading Hard Negatives and True Negatives: A Debiased Contrastive Collaborative Filtering Approach. IJCAI 2022 [探索正确的负样本]

-   Towards Resolving Propensity Contradiction in Offline Recommender Learning. IJCAI 2022 [倾向无关的泛化误差边界，并通过对抗学习最小化理论边界]

-   Debiased, Longitudinal and Coordinated Drug Recommendation through Multi-Visit Clinic Records. NIPS 2022 [去偏药物推荐]


-   Causal Representation Learning for Out-of-Distribution Recommendation. WWW 2022 [利用因果模型解决用户特征变化问题]

-   A Model-Agnostic Causal Learning Framework for Recommendation using Search Data. WWW 2022 [将搜索数据作为工具变量，解耦推荐中的因果部分和非因果部分]
 
-   Causal Preference Learning for Out-of-Distribution Recommendation. WWW 2022 [从观察数据可用的正反馈中联合学习具有因果结构的不变性偏好，再用发现的不变性偏好继续做预测]
  
-   Learning to Augment for Casual User Recommendation. WWW 2022 [通过数据增强来增强对随机用户的推荐性能]

-   CBR: Context Bias aware Recommendation for Debiasing User Modeling and Click Prediction. WWW 2022 [去除由丰富交互造成的上下文偏差]

-   Cross Pairwise Ranking for Unbiased Item Recommendation. WWW 2022 [利用交叉成对损失来去偏]

-   Rating Distribution Calibration for Selection Bias Mitigation in Recommendations. WWW 2022 [通过校准评分分布来缓解选择偏差]

-   UKD: Debiasing Conversion Rate Estimation via Uncertainty-regularized Knowledge Distillation. WWW 2022

-   A General Knowledge Distillation Framework for Counterfactual
    Recommendation via Uniform Data. SIGIR 2020

-   Measuring and Mitigating Item Under-Recommendation Bias in
    Personalized Ranking Systems. SIGIR 2020

-   Attribute-based Propensity for Unbiased Learning in Recommender
    Systems Algorithm and Case Studies. KDD 2020

-   Counterfactual Evaluation of Slate Recommendations with Sequential
    Reward Interactions. KDD 2020

-   Debiasing Item-to-Item Recommendations With Small Annotated
    Datasets. RecSys 2020

-   Keeping Dataset Biases out of the Simulation : A Debiased Simulator
    for Reinforcement Learning based Recommender Systems. RecSys 2020

-   Unbiased Ad Click Prediction for Position-aware Advertising Systems.
    RecSys 2020

-   Unbiased Learning for the Causal Effect of Recommendation. RecSys
    2020

-   E-commerce Recommendation with Weighted Expected Utility. CIKM 2020

-   Popularity-Opportunity Bias in Collaborative Filtering. WSDM 2021

-   Combating Selection Biases in Recommender Systems with a Few
    Unbiased Ratings. WSDM 2021

-   Leave No User Behind Towards Improving the Utility of Recommender
    Systems for Non-mainstream Users. WSDM 2021

-   Non-Clicks Mean Irrelevant Propensity Ratio Scoring As a Correction.
    WSDM 2021

-   Diverse User Preference Elicitation with Multi-Armed Bandits. WSDM
    2021

-   Unbiased Learning to Rank in Feeds Recommendation. WSDM 2021

-   Cross-Positional Attention for Debiasing Clicks. WWW 2021

-   Debiasing Career Recommendations with Neural Fair Collaborative
    Filtering. WWW 2021
    
-   AutoDebias: Learning to Debias for Recommendation. SIGIR 2021

-   Mitigating Sentiment Bias for Recommender Systems. SIGIR 2021

-   Causal Intervention for Leveraging Popularity Bias in Recommendation. SIGIR 2021

-   Enhanced Doubly Robust Learning for Debiasing Post-Click Conversion Rate Estimation. SIGIR 2021

### Fairness in Recommender System
-   Link Recommendations for PageRank Fairness. WWW 2022 [PageRank算法链接预测中的公平性]
-   FairGAN: GANs-based Fairness-aware Learning for Recommendations with Implicit Feedback. WWW 2022 [将物品曝光公平性问题映射为隐式反馈数据中缺乏负反馈的问题]

-   Fairness-Aware Explainable Recommendation over Knowledge Graphs.
    SIGIR 2020

-   Ensuring Fairness in Group Recommendations by Rank-Sensitive
    Balancing of Relevance. RecSys 2020

-   Fairness-Aware News Recommendation with Decomposed Adversarial
    Learning. AAAI 2021 news

-   Practical Compositional Fairness Understanding Fairness in
    Multi-Component Recommender Systems. WSDM 2021

-   Towards Long-term Fairness in Recommendation. WSDM 2021

-   Learning Fair Representations for Recommendation: A Graph-based
    Perspective. WWW 2021

-   User-oriented Group Fairness In Recommender Systems. WWW 2021

-   Personalized Counterfactual Fairness in Recommendation. SIGIR 2021

-   TFROM: A Two-sided Fairness-Aware Recommendation Model for Both Customers and Providers. SIGIR 2021

-   Fairness among New Items in Cold Start Recommender Systems. SIGIR 2021


### Attack in Recommender System

-   Revisiting Injective Attacks on Recommender Systems. NIPS 2022 [重新审视对推荐系统的注入式攻击]

-   Revisiting Adversarially Learned Injection Attacks Against
    Recommender Systems. RecSys 2020

-   Attacking Recommender Systems with Augmented User Profiles. CIKM
    2020

-   A Black-Box Attack Model for Visually-Aware Recommenders. WSDM 2021

-   Denoising Implicit Feedback for Recommendation. WSDM 2021

-   Adversarial Item Promotion: Vulnerabilities at the Core of Top-N
    Recommenders that Use Images to Address Cold Start. WWW 2021

-   Graph Embedding for Recommendation against Attribute Inference
    Attacks. WWW 2021
    
-   Fight Fire with Fire: Towards Robust Recommender Systems via Adversarial Poisoning Training. SIGIR 2021

### Explanation in Recommender System
-   Graph-based Extractive Explainer for Recommendations. WWW 2022 [使用图注意力网络来实现可解释推荐]

-   ExpScore: Learning Metrics for Recommendation Explanation. WWW 2022 [可解释推荐评价指标]

-   Path Language Modeling over Knowledge Graphs for Explainable Recommendation. WWW 2022 [在知识图谱上学习语言模型，实现推荐和解释]

-   Accurate and Explainable Recommendation via Review Rationalization. WWW 2022 [提取评论中的因果关系]

-   AmpSum: Adaptive Multiple-Product Summarization towards Improving Recommendation Captions. WWW 2022 [生成商品标题]

-   Comparative Explanations of Recommendations. WWW 2022 [可比较的推荐解释]

-   Neuro-Symbolic Interpretable Collaborative Filtering for Attribute-based Recommendation. WWW 2022 [以模型为核心的神经符号可解释协同过滤]

-   Try This Instead: Personalized and Interpretable Substitute
    Recommendation. KDD 2020

-   CAFE: Coarse-to-Fine Neural Symbolic Reasoning for Explainable
    Recommendation. CIKM 2020

-   Explainable Recommender Systems via Resolving Learning
    Representations. CIKM 2020

-   Generate Neural Template Explanations for Recommendation. CIKM 2020

-   Explainable Recommendation with Comparative Constraints on Product
    Aspects. WSDM 2021

-   Explanation as a Defense of Recommendation. WSDM 2021

-   EX\^3: Explainable Product Set Recommendation for Comparison
    Shopping. WWW 2021

-   Learning from User Feedback on Explanations to Improve Recommender
    Models. WWW 2021
    
-   On Interpretation and Measurement of Soft Attributes for Recommendation. SIGIR 2021

-   ReXPlug: Explainable Recommendation using Plug-and-Play Language Model. SIGIR 2021

-   User-Centric Path Reasoning towards Explainable Recommendation. SIGIR 2021

### Long-tail/Cold-start in Recommendations

-   Alleviating Cold-start Problem in CTR Prediction with A Variational Embedding Learning Framework. WWW 2022 [使用变分embedding学习框架缓解 CTR 预测中的冷启动问题]

-   PNMTA: A Pretrained Network Modulation and Task Adaptation Approach for User Cold-Start Recommendation. WWW 2022 [加入编码调制器和预测调制器，使得编码器和预测器可以自适应处理冷启动用户。]

-   KoMen: Domain Knowledge Guided Interaction Recommendation for Emerging Scenarios. WWW 2022 [元学习+图网络]

-   Content-aware Neural Hashing for Cold-start Recommendation. SIGIR
    2020

-   MAMO: Memory-Augmented Meta-Optimization for Cold-start
    Recommendation. KDD 2020

-   Learning Transferrable Parameters for Long-tailed Sequential User
    Behavior Modeling. KDD 2020

-   Meta-learning on Heterogeneous Information Networks for Cold-start
    Recommendation. KDD 2020

-   Cold-Start Sequential Recommendation via Meta Learner. AAAI 2021

-   Personalized Adaptive Meta Learning for Cold-start User Preference
    Prediction. AAAI 2021

-   Task-adaptive Neural Process for User Cold-Start Recommendation. WWW
    2021

-   A Model of Two Tales: Dual Transfer Learning Framework for Improved
    Long-tail Item Recommendation. WWW 2021

-   Learning Graph Meta Embeddings for Cold-Start Ads in Click-Through Rate Prediction. SIGIR 2021

-   FORM: Follow the Online Regularized Meta-Leader for Cold-Start Recommendation. SIGIR 2021

-   Privileged Graph Distillation for Cold-start Recommendation. SIGIR 2021

-   Learning to Warm Up Cold Item Embeddings for Cold-start Recommendation with Meta Scaling and Shifting Networks. SIGIR 2021

-   Fairness among New Items in Cold Start Recommender Systems. SIGIR 2021

### Diversity in Recommendations

- Fast Greedy MAP Inference for Determinantal Point Process to Improve Recommendation Diversity. NIPS 2018. [PDF](https://proceedings.neurips.cc/paper/2018/file/dbbf603ff0e99629dda5d75b6f75f966-Paper.pdf)

-   PD-GAN: Adversarial Learning for Personalized Diversity-Promoting Recommendation. IJCAI 2019. [PDF](https://www.ijcai.org/proceedings/2019/0537.pdf)

-   Sequential and Diverse Recommendation with Long Tail. IJCAI 2019. [PDF](https://www.ijcai.org/proceedings/2019/0380.pdf)

-   Diversified Interactive Recommendation with Implicit Feedback. AAAI 2020. [PDF](https://ojs.aaai.org/index.php/AAAI/article/download/5931/5787)

-   ART (Attractive Recommendation Tailor): How the Diversity of Product Recommendations Affects Customer Purchase Preference in Fashion Industry. CIKM 2020. [PDF](https://dl.acm.org/doi/pdf/10.1145/3340531.3412687?casa_token=pLrkqMKPqS4AAAAA:SROCQTKY_rSZVDJa2gTQf5bRGKky_BJEnNOcXXi0A1nYDNO9cBb1FjmIucxg7NN_K42IZA5RGye3XA)

-   A Framework for Recommending Accurate and Diverse Items Using Bayesian Graph Convolutional Neural Networks. KDD 2020. [PDF](https://dl.acm.org/doi/pdf/10.1145/3394486.3403254?casa_token=2k8s3JpMHGQAAAAA:KQUJSQl1AT3d_f0ZhIO0PGKqu_NhPMuPS1lULeZqUSI_FqoHMpsrbTFganamJuZtbD1NJj2FU8N1GA)

-   Enhancing Recommendation Diversity using Determinantal Point Processes on Knowledge Graphs. SIGIR 2020. [PDF](https://dl.acm.org/doi/pdf/10.1145/3397271.3401213?casa_token=WLxAwJzJFhwAAAAA:k_i4GlcKpa6xxtdxPfZLuyyVZ_cp61I4C6pf361chyAYvYzWFQeZJjNQ95POg2UiKPECCcaF-hz9YA) 

-   A Hybrid Bandit Framework for Diversified Recommendation. AAAI 2021. [PDF](https://arxiv.org/pdf/2012.13245)

-   On the Diversity and Explainability of Recommender Systems: A Practical Framework for Enterprise App Recommendation.  CIKM 2021. [PDF](https://dl.acm.org/doi/pdf/10.1145/3459637.3481940?casa_token=x4k2BTtSkmMAAAAA:J-83ktko4ediMOH7qhGal9GmLiop5gLEUgsmffLKfJK2ITuC6m8SDdKvbG4xnttmjH2gCLL66geyog)

-   P-Companion:  A Principled Framework for Diversified Complementary Product Recommendation. CIKM 2021. [PDF](https://dl.acm.org/doi/pdf/10.1145/3340531.3412732)

-   Sliding Spectrum Decomposition for Diversified Recommendation. KDD 2021. [PDF](https://dl.acm.org/doi/pdf/10.1145/3447548.3467108?casa_token=-ODzWqfs760AAAAA:4NO7u-6ARd9lVBIuyiqCN2WKK0QCKbQUCW532MVJduRVV_0dawflyQ1y8YUXaKxMo342KmqF7Q)

-   Enhancing Domain-Level and User-Level Adaptivity in Diversified Recommendation.  SIGIR 2021. [PDF](https://dl.acm.org/doi/abs/10.1145/3404835.3462957) 

-   Dynamic Graph Construction for Improving Diversity of Recommendation. RecSys 2021. [PDF](https://dl.acm.org/doi/abs/10.1145/3460231.3478845)

-   Towards Unified Metrics for Accuracy and Diversity for Recommender Systems. RecSys 2021. [PDF](https://dl.acm.org/doi/pdf/10.1145/3460231.3474234)

-   DGCN: Diversified Recommendation with Graph Convolutional Networks.  WWW 2021. [PDF](http://fi.ee.tsinghua.edu.cn/public/publications/b344fd48-92b0-11eb-96bc-0242ac120003.pdf)

-   Future-Aware Diverse Trends Framework for Recommendation. WWW 2021. [PDF](https://arxiv.org/pdf/2011.00422)

-   Random Walks with Erasure: Diversifying Personalized Recommendations on Social and Information Networks.  WWW 2021. [PDF](https://arxiv.org/pdf/2102.09635)


### Evaluation

-   Measuring Recommendation Explanation Quality: The Conflicting Goals
    of Explanations. SIGIR 2020

-   Evaluating Conversational Recommender Systems via User Simulation.
    KDD 2020

-   On Sampled Metrics for Item Recommendation. KDD 2020

-   On Sampling Top-K Recommendation Evaluation. KDD 2020

-   Are We Evaluating Rigorously： Benchmarking Recommendation for
    Reproducible Evaluation and Fair Comparison. RecSys 2020

-   On Target Item Sampling in Offline Recommender System Evaluation.
    RecSys 2020
    
-   Standing in Your Shoes: External Assessments for Personalized Recommender Systems. SIGIR 2021

Technique
---------

### Pre-training in Recommender System

-   S\^3-Rec: Self-Supervised Learning for Sequential Recommendation
    with Mutual Information Maximization. CIKM 2020

-   Self-supervised Learning for Large-scale Item Recommendations. arXiv 2020

-   U-BERT Pre-Training User Representations for Improved
    Recommendation. AAAI 2021

-   Pre-Training Graph Neural Networks for Cold-Start Users and Items
    Representation. WSDM 2021

-   Augmenting Sequential Recommendation with Pseudo-Prior Items via
    Reversely Pre-training Transformer. SIGIR 2021

-   Self-supervised Graph Learning for Recommendation. SIGIR 2021

-   Self-Supervised Hypergraph Convolutional Networks for Session-based
    Recommendation. AAAI 2021

-   Self-Supervised Multi-Channel Hypergraph Convolutional Network
    for Social Recommendation. WWW 2021

-   Pre-training Graph Transformer with Multimodal Side Information
    for Recommendation. ACM MM2021

-   SelfCF: A Simple Framework for Self-supervised Collaborative
    Filtering. arXiv 2021

-   UPRec: User-Aware Pre-training for Recommender Systems. arXiv 2021

-   Curriculum Pre-Training Heterogeneous Subgraph Transformer for
    Top-N Recommendation. arXiv 2021

-   One4all User Representation for Recommender Systems in
    E-commerce. arXiv 2021

-   Graph Neural Pre-training for Enhancing Recommendations using
    Side Information. arXiv 2021

### Reinforcement Learning in Recommendations

-   MINDSim: User Simulator for News Recommenders. WWW 2022 [用户模拟+新闻推荐]

-   Multi-level Recommendation Reasoning over Knowledge Graphs with Reinforcement Learning. WWW 2022

-   Multiple Choice Questions based Multi-Interest Policy Learning for Conversational Recommendation. WWW 2022

-   Off-policy Learning over Heterogeneous Information for Recommendation. WWW 2022

-   MaHRL: Multi-goals Abstraction based Deep Hierarchical Reinforcement
    Learning for Recommendations. SIGIR 2020

-   Interactive Recommender System via Knowledge Graph-enhanced
    Reinforcement Learning. SIGIR 2020

-   Joint Policy-Value Learning for Recommendation. KDD 2020

-   BLOB: A Probabilistic Model for Recommendation that Combines Organic
    and Bandit Signals. KDD 2020

-   Learning to Collaborate in Multi-Module Recommendation via
    Multi-Agent Reinforcement Learning without Communication. RecSys
    2020

-   Reinforcement Learning with a Disentangled Universal Value Function
    for Item Recommendation. AAAI 2021

-   User Response Models to Improve a REINFORCE Recommender System. WSDM
    2021

-   Cost-Effective and Interpretable Job Skill Recommendation with Deep
    Reinforcement Learning. WWW 2021

-   A Multi-Agent Reinforcement Learning Framework for Intelligent
    Electric Vehicle Charging Recommendation. WWW 2021

-   Reinforcement Recommendation with User Multi-aspect Preference. WWW
    2021
    
-   RLNF: Reinforcement Learning based Noise Filtering for Click-Through Rate Prediction. SIGIR 2021

-   Unified Conversational Recommendation Policy Learning via Graph-based Reinforcement Learning. SIGIR 2021

### Knowledge Distillation in Recommendations

-   Privileged Features Distillation at Taobao Recommendations. KDD 2020

-   DE-RRD: A Knowledge Distillation Framework for Recommender System.
    CIKM 2020

-   Bidirectional Distillation for Top-K Recommender System. WWW 2021

### NAS in Recommendations
-   Towards Automatic Discovering of Deep Hybrid Network Architecture for Sequential Recommendation. WWW 2022 [通过NAS来搜索每一层使用注意力/卷积模块]

-   Neural Input Search for Large Scale Recommendation Models. KDD 2020

-   Field-aware Embedding Space Searching in Recommender Systems. WWW
    2021

### Federated Learning in Recommendations

-   Poisoning Deep Learning based Recommender Model in Federated Learning Scenarios. IJCAI 2022 [设计针对基于深度学习的推荐模型的攻击]

-   FedFast Going Beyond Average for Faster Training of Federated
    Recommender Systems. KDD 2020

### GNN in Recommendations

-   Heterogeneous Interactive Snapshot Network for Review-Enhanced Stock Profiling and Recommendation. IJCAI 2022

-   Self-supervised Graph Neural Networks for Multi-behavior Recommendation. IJCAI 2022 [GNN + 多行为推荐]

-   RecipeRec: A Heterogeneous Graph Learning Model for Recipe Recommendation. IJCAI 2022 [用于食谱推荐的新型异构图学习模型]

-   Graph Convolution Network based Recommender Systems: Learning Guarantee and Item Mixture Powered Strategy. NIPS 2022 [基于图卷积网络的推荐系统：学习保证和商品混合驱动策略]

-   Contrastive Graph Structure Learning via Information Bottleneck for Recommendation. NIPS 2022 [基于信息瓶颈的对比图结构学习]

-   Improving Graph Collaborative Filtering with Neighborhood-enriched Contrastive Learning. WWW 2022 [通过邻居节点间的对比学习来改善图协同过滤]

-   Revisiting Graph based Social Recommendation: A Distillation Enhanced Social Graph Network. WWW 2022 [使用知识蒸馏来融入user-item交互图和user-user社交图的信息]

-   STAM: A Spatiotemporal Aggregation Method for Graph Neural Network-based Recommendation. WWW 2022 [同时聚合时空领域信息]

-   Hypercomplex Graph Collaborative Filtering. WWW 2022 [超复图协同过滤]

-   Graph Neural Transport Networks with Non-local Attentions for Recommender Systems. WWW 2022 [使用非局部注意力来实现不加深GNN的同时捕捉节点间的长距离依赖]

-   FIRE: Fast Incremental Recommendation with Graph Signal Processing. WWW 2022 [通过图信号处理来实现快速增量推荐]

-   Large-scale Personalized Video Game Recommendation via Social-aware Contextualized Graph Neural Network. WWW 202 [同时考虑个性化，游戏上下文，社交联系]

-   Neural Graph Collaborative Filtering. SIGIR 2019

-   A Neural Influence Diffusion Model for Social Recommendation. SIGIR 2019

-   Graph Neural Networks for Social Recommendation. WWW 2019

-   Knowledge Graph Convolutional Networks for Recommender Systems. WWW 2019

-   KGAT: Knowledge Graph Attention Network for Recommendation. KDD 2019

-   Session-based recommendation with graph neural networks. AAAI 2019

-   Graph contextualized self-attention network for session-based
    recommendation. IJCAI 2019

-   Session-based social recommendation via dynamic graph attention
    networks. WSDM 2019

-   Fi-GNN: Modeling Feature Interactions via Graph Neural Networks for
    CTR Prediction. WWW 2019

-   Bundle Recommendation with Graph Convolutional Networks. SIGIR 2020

-   Sequential Recommendation with Graph Convolutional Networks. 
    SIGIR 2021

-   Structured Graph Convolutional Networks with Stochastic Masks for
    Recommender Systems. SIGIR 2021

-   Adversarial-Enhanced Hybrid Graph Network for User Identity Linkage.
    SIGIR 2021

-   Should Graph Convolution Trust Neighbors? A Simple Causal Inference
    Method. SIGIR 2021

-   A Graph-Convolutional Ranking Approach to Leverage the Relational
    Aspects of User-Generated Content. SIGIR 2021

-   Relational Learning with Gated and Attentive Neighbor Aggregator for
    Few-Shot Knowledge Graph Completion. SIGIR 2021

-   Learning Graph Meta Embeddings for Cold-Start Ads in Click-Through
    Rate Prediction. SIGIR 2021

-   Neural Graph Matching based Collaborative Filtering. SIGIR 2021

-   Modeling Intent Graph for Search Result Diversification. SIGIR 2021

-   User-Centric Path Reasoning towards Explainable Recommendation.
    SIGIR 2021

-   Joint Knowledge Pruning and Recurrent Graph Convolution for News
    Recommendation. SIGIR 2021

-   Retrieving Complex Tables with Multi-Granular Graph Representation
    Learning. SIGIR 2021

-   Privileged Graph Distillation for Cold-start Recommendation. SIGIR 2021

-   Decoupling Representation Learning and Classification for GNN-based
    Anomaly Detection. SIGIR 2021

-   Meta-Inductive Node Classification across Graphs. SIGIR 2021

-   Self-supervised Graph Learning for Recommendation. SIGIR 2021

-   TIE: A Framework for Embedding-based Incremental Temporal Knowledge
    Graph Completion. SIGIR 2021

-   Graph Meta Network for Multi-Behavior Recommendation with Interaction
    Heterogeneity and Diversity. SIGIR 2021

-   AdsGNN: Behavior-Graph Augmented Relevance Modeling in Sponsored Search.
    SIGIR 2021

-   Enhanced Graph Learning for Collaborative Filtering via Mutual
    Information Maximization. SIGIR 2021

-   WGCN: Graph Convolutional Networks with Weighted Structural Features.
    SIGIR 2021


Analysis
--------

-   How Dataset Characteristics Affect the Robustness of Collaborative
    Recommendation Models. SIGIR 2020

-   Agreement and Disagreement between True and False-Positive Metrics
    in Recommender Systems Evaluation. SIGIR 2020

-   Critically Examining the Claimed Value of Convolutions over
    User-Item Embedding Maps for Recommender Systems. CIKM 2020

-   On Estimating Recommendation Evaluation Metrics under Sampling. AAAI
    2021

-   Beyond Point Estimate Inferring Ensemble Prediction Variation from
    Neuron Activation Strength in Recommender Systems. WSDM 2021

-   Bias-Variance Decomposition for Ranking. WSDM 2021

-   Theoretical Understandings of Product Embedding for E-commerce
    Machine Learning. WSDM 2021

Other
-----

-   Tenrec: A Large-scale Multipurpose Benchmark Dataset for Recommender Systems. NIPS 2022 [推荐系统的大规模多用途基准数据集]

-   The trade-offs of model size in large recommendation models : A 10000 ×× compressed criteo-tb DLRM model (100 GB parameters to mere 10MB). NIPS 2022 [模型压缩]

-   DreamShard: Generalizable Embedding Table Placement for Recommender Systems. NIPS 2022 [推荐系统的通用embedding表]

-   On the Generalizability and Predictabilityof Recommender Systems. NIPS 2022 [提出一种元学习方法，针对一个全新的，未见过的数据集选择最优算法和参数]

-   Learning Personalized Risk Preferences for Recommendation. SIGIR
    2020

-   Distributed Equivalent Substitution Training for Large-Scale
    Recommender Systems. SIGIR 2020

-   Beyond User Embedding Matrix: Learning to Hash for Modeling
    Large-Scale Users in Recommendation. SIGIR 2020

-   How to Retrain a Recommender System? SIGIR 2020

-   Recommendation for New Users and New Items via Randomized Training
    and Mixture-of-Experts Transformation. SIGIR 2020

-   Compositional Embeddings Using Complementary Partitions for
    Memory-Efficient Recommendation Systems. KDD 2020

-   Improving Recommendation Quality in Google Drive. KDD 2020

-   A Method to Anonymize Business Metrics to Publishing Implicit
    Feedback Datasets. RecSys 2020

-   Exploiting Performance Estimates for Augmenting Recommendation
    Ensembles. RecSys 2020

-   User Simulation via Supervised Generative Adversarial Network. WWW
    2021
