

# 团队介绍
商家平台算法是链接用户、商家与淘宝平台的核心团队，拥有万亿级别的数据与计算资源，以及一群热情友好富有技术激情的小伙伴。等你来成就自我，一起让天下没有难做的生意。

技术上，我们不断精进超大规模的商品、视频、直播、图文的召回、排序、重混排能力，包含跨域多模态与智能UI，同时通过深度强化学习技术优化推荐策略，设计智能流量机制，助力用户规模增长、商家及内容创作者成长。

# 业务介绍
## 店铺
### 全部宝贝
<p align = "center">
<img src="assets/img/all_items.JPG" width="240"/>   
</p>
"全部宝贝"展现店铺内售卖的所有宝贝，搜推一体，手机淘宝顶级成交场景之一。  
算法在该场景的主要工作包括：

- 经典商品搜索推荐效率优化。样本构建，特征构建，模型优化（召回、粗排、精排、LTR、重排），训练目标优化，以及训练过程优化（含Reinforcement Learning）。
- 端智能。根据用户实时行为，触发端上重排，规划触发云端引擎重新请求，用户动线干预，如引导用户订阅店铺，分发优惠券。
- 智能UI。如宝贝价格展现优化，标题优化，背书与卖点信息优化等。
- 搜索相关性与用户体验优化。比如分词改写，相关性过滤。
- 其他功能优化。如快捷筛选，搜索词推荐，店内热点趋势推荐等。

## 详情
商品详情页不仅仅是信息的简单展示，它是用户与商品之间的桥梁，是激发消费欲望、建立用户信任的重要阵地，我们致力于通过详情的信息展示和分发效率提升带来用户体验 和手淘大盘增量的提升。算法在该场景的主要工作包括：
- 用户动线理解：深入分析用户的关键决策过程，提高商品信息的精准展示，确保用户能够快速找到所需的信息，提升决策效率和转化效率。
- 经典的推荐效率优化。包括商品推荐、SKU推荐等场景，样本构建，特征构建，模型优化（召回、粗排、精排、LTR、重排），训练目标优化，以及训练过程优化。
- 自然语言理解。包括对SKU进行劣质识别、关键信息抽取、结构化展示等，提升信息传递的效率。
  
## 关注
## BC通道

# 招聘职位及要求
1. 具备优秀的编码能力，扎实的数据结构和算法功底；
2. 熟悉大规模机器学习/深度学习算法，具有搜推告等相关领域经验；
3. 优秀的分析问题和解决问题的能力，对解决具有挑战性问题充满激情，不轻易放弃；
4. 对技术有热情，对搜推广业务有自己的思考，能够用技术推动业务进步和变革；
5. 有良好的沟通表达能力具有团队精神，有良好的团队协同能力；
6. 在有影响力的计算机学术会议（SIGKDD、AAAI、SIGIR、ICML、NIPS、WWW、CIKM、ACL、RECSYS等）或期刊上发表过论文者优先。
7. 职位层级P5-P7

# 团队代表性技术
- 2023年
  - CMR 强化学习生成式重排模型，有机融入复杂业务意图，同时支持在线实时多目标权重调节。
  - DPAN 显示建模用户相似推荐与相关推荐的偏好，带来更加多样性的推荐结果。
  - Panel-MDP 打破强化学习线性MDP定义，有效建模2D 商品分布之间的相互影响。
- 2022年
  - XDM 通过引入曝光未点击宝贝序列强化用户理解，提升召回效果。
- 2020年
  - ESM^2 引入加购与收藏，应对成交样本选择性偏差与正样本稀疏性，有效提升商品转化预估。
  - GMCM 利用图结构，有效建模用户在手淘详情页上的细致行为，捕获用户购买兴趣。
  - Multi-IPW与Multi-DR，利用propensity与Double Robust技术，从因果推断角度，实现无偏成交率预估。
- 2019年
  - SDM手淘最早的生成式召回模型之一。
  - DSIN多session的用户兴趣与意图理解，用于点击率预估。
  - ldcTree 级联深度树模型，有效捕获稀疏正信号，用于成交转化率预估。

# 团队典型代表作
* KDD2023: Controllable Multi-Objective Re-ranking with Policy Hypernetworks
* SIGIR-AP2023: Reinforcement Re-ranking with 2D Grid-based Recommendation Panels
* CIKM2023: DPAN: Dynamic Preference-based and Attribute-aware Network for Relevant Recommendations
* DASFAA2022: XDM: Improving Sequential Deep Matching with Unclicked User Behaviors for Recommender System
* SIGIR2020: Entire Space Multi-Task Modeling via Post-Click Behavior Decomposition for Conversion Rate Prediction
* SIGIR2020: GMCM: Graph-based Micro-behavior Conversion Model for Post-click Conversion Rate Estimation
* WWW2020: Large-scale causal approaches to debiasing post-click conversion rate estimation with multi-task learning
* CIKM2019: SDM: Sequential Deep Matching Model for Online Large-scale Recommender System
* IJCAI2019: Deep Session Interest Network for Click-Through Rate Prediction
* AAAI2019: Multi-Level Deep Cascade Trees for Conversion Rate Prediction in Recommendation System

# 我要和Boss直接聊
团队Leader：林泉（花名铁衣）

Email：tieyi.lq@taobao.com




