# Huiying's Work (PhD thesis)
This repository maintains a list of materials that Huiying looks into. 

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#Papers">Papers </a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Graph-Data">Graph Data</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Contrastive-Learning">Contrastive Learning</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Pre-Training">Pre-Training</a></td></tr>
    <tr><td colspan="2">&emsp;&emsp;<a href="#Incorporating-Knowledge">Incorporating Knowledge</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Tabular-Data">Tabular Data</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Tabular-Representation">Tabular Representation</a></td></tr>
    <tr><td colspan="2">&emsp;&emsp;<a href="#Incorporating-External-Knowledge">Incorporating External Knowledge</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Factuality-and-Trustworthiness">Factuality and Trustworthiness</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Fact-Checking">Fact-Checking</a></td></tr>
    <tr><td colspan="2">&emsp;&emsp;<a href="#Evidence-Based">Evidence-Based</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Sequential-Data">Sequential Data</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Change-Point-Detection">Change Point Detection</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Anomaly-Detection">Anomaly Detection</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Data-Imputation">Data Imputation</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Self-supervised-Learning">Self-supervised Learning</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Knowledge-Distillation">Knowledge Distillation</a></td></tr>
    <tr><td colspan="2">&emsp;&emsp;<a href="#Symbolic-Commonsense">Symbolic | Commonsense</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Knowledge-Engine">Knowledge Engine</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Neural-Architecture-Search">Neural Architecture Search</a></td></tr>
<tr><td colspan="2"><a href="#Notebooks">Notebooks </a></td></tr>
<tr><td colspan="2"><a href="#Foundations-of-Deep-Learning">Foundations of Deep Learning </a></td></tr>
<tr><td colspan="2"><a href="#Tools">Tools </a></td></tr>
<tr><td colspan="2"><a href="#Resources">Resources </a></td></tr>
<tr><td colspan="2"><a href="#People">People </a></td></tr>	
</table>






### [Papers](#content)

#### [Graph Data](#content)
##### [Contrastive Learning](#content)

1. **Multi-Scale Contrastive Siamese Networks for Self-Supervised Graph Representation Learning.** IJCAI 2021. [paper](https://www.ijcai.org/proceedings/2021/0204.pdf) [code](https://github.com/GRAND-Lab/MERIT)
    *Yanqiao Zhu, Yichen Xu, Feng Yu, Qianq Liu, Shu Wu, Liang Wang.*

1. **Deep Graph Contrastive Representation Learning.** ICML 2020. [paper](https://arxiv.org/abs/2006.04131v2) [code](https://github.com/CRIPAC-DIG/GRACE)
    *Yanqiao Zhu, Yichen Xu, Feng Yu, Qianq Liu, Shu Wu, Liang Wang.*

1. **Graph Contrastive Learning with Augmentation.**  NeurIPS 2020. [paper](https://arxiv.org/abs/2010.13902) [code](https://github.com/Shen-Lab/GraphCL)
    *Yuning You, Tianlong Chen, Yongduo Sui, Ting Chen, Zhangyang Wang, Yang Shen.*
    
1. **GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training.**  KDD 2020. [paper](https://arxiv.org/abs/2006.09963) [code](https://github.com/THUDM/GCC)
    *Jiezhong Qiu, Qibin Chen, Yuxiao Dong, Jing Zhang, Hongxia Yang, Ming Ding, Kuansan Wang, Jie Tang.*
    
1. **GraLSP: Graph Neural Networks with Local Structural Patterns.**  AAAI 2020. [paper](https://arxiv.org/abs/1911.07675) [code](https://github.com/KL4805/GraLSP)
    *Yilun Jin, Guojie Song, Chuan Shi.*
    

##### [Pre-Training](#content)

1. **Strategies for Pre-training Graph Neural Networks.** ICLR 2020. [paper](https://arxiv.org/abs/1905.12265) [code](https://github.com/snap-stanford/pretrain-gnns)
    *Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec.*    

##### [Incorporating Knowledge](#content)

1. **Augmenting Neural Networks with First-order Logic.** ACL 2019. [paper](https://aclanthology.org/P19-1028/) 
   *Tao Li, Vivek Srikumar.*    




#### [Tabular Data](#content)
##### [Tabular Representation](#content) 

1. **Learning Enhanced Representations for Tabular Data via Neighborhood Propagation.** arXiv preprint 2022. [paper](https://arxiv.org/pdf/2206.06587.pdf)
   *Kounianhua Du, Weinan Zhang, Ruiwen Zhou, Yangkun Wang, Xilong Zhao, Jiarui Jin, Quan Gan, Zheng Zhang, David Wipf.*
   
1. **SubTab: Subsetting Features of Tabular Data for Self-Supervised Representation Learning.** NeurIPS 2021. [paper](https://github.com/AstraZeneca/SubTab/)
   *Talip Ucar, Ehsan Hajiramezanali, Lindsay Edwards.*
   
1. **INFOTABS: Inference on Tables as Semi-structured Data.** ACL 2020. [paper](https://aclanthology.org/2020.acl-main.210/)

   *Vivek Gupta, Maitrey Mehta, Pegah Nokhiz, Vivek Srikumar*

##### [Incorporating External Knowledge](#content) 

1. **Incorporating External Knowledge to Enhance Tabular Reasoning.** NAACL 2021. [paper](https://aclanthology.org/2021.naacl-main.224/)
   *J. Neeraja, Vivek Gupta, Vivek Srikumar.*



#### [Factuality and Trustworthiness](#content) 

##### [Fact-Checking](#content) 

1. **Generating Scientific Claims for Zero-Shot Scientific Fact Checking.** ACL 2022. [paper](https://aclanthology.org/2022.acl-long.175/)

   *Dustin Wright, David Wadden, Kyle Lo, Bailey Kuehl, Arman Cohan, Isabelle Augenstein, Lucy Wang*.

1. **An Experimental Study to Understand User Experience and Perception Bias Occurred by Fact-checking Messages**. WWW 2021. [paper](https://sci-hub.se/https://doi.org/10.1145/3442381.3450121)

   *Sungkyu Park , Jamie Yejean Park , Hyojin Chin , Jeong-han Kang , Meeyoung Cha*.

1. **Automated Fact-Checking for Assisting Human Fact-Checkers.** IJCAI 2021. [paper](https://www.ijcai.org/proceedings/2021/619)

   *Preslav Nakov, David Corney, Maram Hasanain, Firoj Alam, Tamer Elsayed, Alberto Barrón-Cedeño, Paolo Papotti, Shaden Shaar, Giovanni Da San Martino.*

1. **Multi-Hop Fact Checking of Political Claims.** IJCAI 2021. [paper](https://www.ijcai.org/proceedings/2021/0536)

   *Wojciech Ostrowski, Arnav Arora, Pepa Atanasova, Isabelle Augenstein.*

1. **Towards Few-shot Fact-Checking via Perplexity.** NAACL 2021. [paper](https://aclanthology.org/2021.naacl-main.158/)

   *Nayeon Lee, Yejin Bang, Andrea Madotto, Pascale Fung.*

1. **Improving Evidence Retrieval for Automated Explainable Fact-Checking.** NAACL 2021. [paper](https://aclanthology.org/2021.naacl-demos.10/)

   *Chris Samarinas, Wynne Hsu, Mong Li Lee*

1. **A Multi-Level Attention Model for Evidence-Based Fact Checking.** ACL/IJCNLP 2021. [paper](https://aclanthology.org/2021.findings-acl.217/)

   *Canasai Kruengkrai, Junichi Yamagishi, Xin Wang.*

1. **Joint Verification and Reranking for Open Fact Checking Over Tables.** ACL/IJCNLP 2021. [paper](https://aclanthology.org/2021.acl-long.529/)

   *Michael Sejr Schlichtkrull, Vladimir Karpukhin, Barlas Oguz, Mike Lewis, Wen-tau Yih, Sebastian Riedel.*

1. **Strong and Light Baseline Models for Fact-Checking Joint Inference.** ACL/IJCNLP 2021. [paper](https://aclanthology.org/2021.findings-acl.426/)

   *Kateryna Tymoshenko, Alessandro Moschitti.*

1. **FACE-KEG: Fact Checking Explained using KnowledgE Graphs.** WSDM 2021. [paper](https://dl.acm.org/doi/10.1145/3437963.3441828)

   *Nikhita Vedula , Srinivasan Parthasarathy.*

1. **Factoring Fact-Checks: Structured Information Extraction from Fact-Checking Articles**. WWW 2020. [paper](https://sci-hub.se/https://doi.org/10.1145/3366423.3380231)

   *Shan Jiang , Simon Baumgartner , Abe Ittycheriah , Cong Yu.*

1. **Generating Fact Checking Explanations.** ACL 2020. [paper](https://aclanthology.org/2020.acl-main.656/)

   *Pepa Atanasova, Jakob Grue Simonsen, Christina Lioma, Isabelle Augenstein*.

1. **DeSePtion: Dual Sequence Prediction and Adversarial Examples for Improved Fact-Checking.** ACL 2020. [paper](https://aclanthology.org/2020.acl-main.761/)

   *Christopher Hidey, Tuhin Chakrabarty, Tariq Alhindi, Siddharth Varia, Kriste Krstovski, Mona Diab, Smaranda Muresan.*

1. **LogicalFactChecker: Leveraging Logical Operations for Fact Checking with Graph Module Network.** ACL 2020. [paper](https://aclanthology.org/2020.acl-main.539/)

   *Wanjun Zhong, Duyu Tang, Zhangyin Feng, Nan Duan, Ming Zhou, Ming Gong, Linjun Shou, Daxin Jiang, Jiahai Wang, Jian Yin*.

1. **Reasoning Over Semantic-Level Graph for Fact Checking.** ACL 2020. [paper](https://aclanthology.org/2020.acl-main.549/)

   *Wanjun Zhong, Jingjing Xu, Duyu Tang, Zenan Xu, Nan Duan, Ming Zhou, Jiahai Wang, Jian Yin.*

1. **Cracking Tabular Presentation Diversity for Automatic Cross-Checking over Numerical Facts.** KDD 2020. [paper](https://dl.acm.org/doi/10.1145/3394486.3403310)

   *Hongwei Li , Qingping Yang , Yixuan Cao , Jiaquan Yao , Ping Luo*

1. **Explainable Automated Fact-Checking for Public Health Claims.** EMNLP 2020. [paper](https://aclanthology.org/2020.emnlp-main.623/)

   *Neema Kotonya, Francesca Toni.*

1. **Generating Fact Checking Briefs.** EMNLP 2020. [paper](https://aclanthology.org/2020.emnlp-main.580/)

    *Angela Fan, Aleksandra Piktus, Fabio Petroni, Guillaume Wenzek, Marzieh Saeidi, Andreas Vlachos, Antoine Bordes, Sebastian Riedel.*

1. **AnswerFact: Fact Checking in Product Question Answering.** EMNLP 2020. [paper](https://aclanthology.org/2020.emnlp-main.188/)

    *Wenxuan Zhang, Yang Deng, Jing Ma, Wai Lam.*

1. **FactCatch: Incremental Pay-as-You-Go Fact Checking with Minimal User Effort.** SIGIR 2020. [paper](https://sci-hub.se/https://doi.org/10.1145/3397271.3401408)

    *Thanh Tam Nguyen , Matthias Weidlich , Hongzhi Yin , Bolong Zheng , Quang Huy Nguyen , Quoc Viet Hung Nguyen.*

1. **Scrutinizer: Fact Checking Statistical Claims**. VLDB 2020. [paper](http://www.vldb.org/pvldb/vol13/p2965-karagiannis.pdf)

    *Georgios Karagiannis , Mohammed Saeed , Paolo Papotti , Immanuel Trummer.*

1. **Buckle: Evaluating Fact Checking Algorithms Built on Knowledge Bases**. VLDB 2019. [paper](http://www.vldb.org/pvldb/vol12/p1798-huynh.pdf)

    *Viet-Phi Huynh , Paolo Papotti.*

1. **Mining an "Anti-Knowledge Base" from Wikipedia Updates with Applications to Fact Checking and Beyond**. VLDB 2019. [paper](http://www.vldb.org/pvldb/vol13/p561-karagiannis.pdf)

    *Georgios Karagiannis , Immanuel Trummer , Saehan Jo , Shubham Khandelwal , Xuezhi Wang , Cong Yu.*

1. **User Guidance for Efficient Fact Checking**. VLDB 2019. [paper](http://www.vldb.org/pvldb/vol12/p850-nguyen.pdf)

    *Thanh Tam Nguyen , Matthias Weidlich , Hongzhi Yin , Bolong Zheng , Quoc Viet Hung Nguyen , Bela Stantic*.

1. **A Benchmark for Fact Checking Algorithms Built on Knowledge Bases.** CIKM 2019. [paper](https://sci-hub.se/https://doi.org/10.1145/3357384.3358036)

    *Viet-Phi Huynh , Paolo Papotti.*

1. **Attributed Multi-Relational Attention Network for Fact-checking URL Recommendation.** CIKM 2019. [paper](https://dl.acm.org/doi/10.1145/3357384.3358006)

    *Di You , Nguyen Vo , Kyumin Lee , Qiang LIU.*

1. **Evidence-based Trustworthiness.** ACL 2019. [paper](https://aclanthology.org/P19-1040.pdf)
   
    *Yi Zhang, Zachary G. Ives, Dan Roth, Department of Computer and Information Science University of Pennsylvania.*
    
1. **Towards a Benchmark for Fact Checking with Knowledge Bases**. WWW 2018. [paper](https://dl.acm.org/doi/10.1145/3184558.3191616)

    *Viet-Phi Huynh , Paolo Papotti*.

1. **Fact Checking via Evidence Patterns.** IJCAI 2018. [paper](https://www.ijcai.org/proceedings/2018/522)

   *Valeria Fionda, Giuseppe Pirrò.*

1. **Fact Checking in Community Forums.** AAAI 2018. [paper](https://dl.acm.org/doi/abs/10.5555/3504035.3504686)

   *Tsvetomila Mihaylova , Preslav Nakov , Lluís Màrquez , Alberto Barrón-Cedeño , Mitra Mohtarami , Georgi Karadzhov , James Glass.*

1. **An Interpretable Joint Graphical Model for Fact-Checking From Crowd.** AAAI 2018. [paper](https://www.byronwallace.com/static/articles/nguyen-aaai18.pdf)

   *An Nguyen, Aditya Kharosekar, Matthew Lease, Byron Wallace.*

1. **The Rise of Guardians: Fact-checking URL Recommendation to Combat Fake News.** SIGIR 2018. [paper](https://dl.acm.org/doi/10.1145/3209978.3210037)

   *Nguyen Vo , Kyumin Lee.*

1. **Truth of Varying Shades: Analyzing Language in Fake News and Political Fact-Checking.** EMNLP 2017. [paper](https://aclanthology.org/D17-1317/)

   *Hannah Rashkin, Eunsol Choi, Jin Yea Jang, Svitlana Volkova, Yejin Choi.*

1. **Fact Checking in Heterogeneous Information Networks**. WWW 2016. [paper](https://dl.acm.org/doi/10.1145/2872518.2889354)

   *Baoxu Shi , Tim Weninger*.

1. **Fact-checking Effect on Viral Hoaxes: A Model of Misinformation Spread in Social Networks**. WWW 2015. [paper](https://sci-hub.se/https://doi.org/10.1145/2740908.2742572)

   *Marcella Tambuscio , Giancarlo Ruffo , Alessandro Flammini , Filippo Menczer.*

###### System

1. **FAKTA: An Automatic End-to-End Fact Checking System.** NAACL 2019. [paper](https://aclanthology.org/N19-4014/)

   *Moin Nadeem, Wei Fang, Brian Xu, Mitra Mohtarami, James Glass.*

1. **AggChecker: A Fact-Checking System for Text Summaries of Relational Data Sets**. VLDB 2019. [paper](http://www.vldb.org/pvldb/vol12/p1938-jo.pdf)

   *Saehan Jo , Immanuel Trummer , Weicheng Yu , Xuezhi Wang , Cong Yu , Daniel Liu , Niyati Mehta*.

1. **ClaimBuster: The First-ever End-to-end Fact-checking System**. VLDB 2017. [paper](http://www.vldb.org/pvldb/vol10/p1945-li.pdf)

   *Naeemul Hassan , Gensheng Zhang , Fatma Arslan , Josue Caraballo , Damian Jimenez.*

1. **Toward Automated Fact-Checking: Detecting Check-worthy Factual Claims by ClaimBuster.** KDD 2017. [paper](https://dl.acm.org/doi/10.1145/3097983.3098131)

   *Naeemul Hassan , Fatma Arslan , Chengkai Li , Mark Tremayne*

###### Dataset

1. **MultiFC: A Real-World Multi-Domain Dataset for Evidence-Based Fact Checking of Claims.** EMNLP/IJCNLP 2019. [paper](https://aclanthology.org/D19-1475/)

   *Isabelle Augenstein, Christina Lioma, Dongsheng Wang, Lucas Chaves Lima, Casper Hansen, Christian Hansen, Jakob Grue Simonsen.*

2. **Epinions social network.** who-trust-whom online social network of a a general consumer review site Epinions.com. [link](https://snap.stanford.edu/data/soc-Epinions1.html)

##### [Evidence-Based](#content) 

1. **Is My Model Using the Right Evidence? Systematic Probes for Examining Evidence-Based Tabular Reasoning.** ACL 2022. [paper](https://aclanthology.org/2022.tacl-1.38/)

   *Vivek Gupta, Riyaz A. Bhat, Atreya Ghosal, Manish Shrivastava, Maneesh Singh, Vivek Srikumar.*




#### [Sequential Data](#content)
##### [Data Imputation](#content)

1. **FILLING THE G AP S: MULTIVARIATE TIME SERIES IMPUTATION BY GRAPH NEURAL NETWORKS.** ICLR 2022. [paper](https://arxiv.org/pdf/2108.00298.pdf)
    *Andrea Cini, Ivan Marisca, Cesare Alippi.*

1. **Multivariate Time Series Imputation with Generative Adversarial Networks.** NeurIPS 2018. [paper](https://papers.nips.cc/paper/2018/file/96b9bff013acedfb1d140579e2fbeb63-Paper.pdf)
    *Yonghong Luo, Xiangrui Cai, Ying Zhang ∗, Jun Xu, Xiaojie Yuan.*

1. **Generative Semi-supervised Learning for Multivariate Time Series Imputation.** AAAI 2021. [paper](https://papers.nips.cc/paper/2018/file/96b9bff013acedfb1d140579e2fbeb63-Paper.pdf)
    *Xiaoye Miao, Yangyang Wu, Jun Wang, Yunjun Gao, Xudong Mao, Jianwei Yin.*

1. **Missing Data Imputation using Optimal Transport.** PMLR 2020. [paper](http://proceedings.mlr.press/v119/muzellec20a.html)
    *Boris Muzellec, Julie Josse, Claire Boyer, Marco Cuturi.*

1. **Filling Missing Values on Wearable-Sensory Time Series Data .** SIAM 2020. [paper](https://epubs.siam.org/doi/10.1137/1.9781611976236.6)
    *Suwen Lin, Xian Wu, Gonzalo Martinez and Nitesh V. Chawla.*
    
1. **ST-MVL: Filling Missing Values in Geo-Sensory Time Series Data.** IJCAI 2016. [paper](https://www.ijcai.org/Proceedings/16/Papers/384.pdf)
    *Xiuwen Yi, Yu Zheng, Junbo Zhang, Tianrui Li.*
    

##### [Change Point Detection](#content)

1. **An Evaluation of Change Point Detection Algorithms.** arXiv.stat.ML 2020. [paper](https://arxiv.org/abs/2003.06222)
    *Gerrit J.J. van den Burg, Christopher K.I. Williams.*

1. **A Survey of Methods for Time Series Change Point Detection.** ACM 2017. [paper](https://www.researchgate.net/publication/307947624_A_Survey_of_Methods_for_Time_Series_Change_Point_Detection)
    *Samaneh Aminikhanghahi, Diane J Cook.*

1. **Bayesian Online Changepoint Detection.** arXiv.stat.ML 2007. [paper](https://arxiv.org/abs/0710.3742)
    *Ryan Prescott Adams, David J.C. MacKay.*

1. **Time Series Change Point Detection with Self-Supervised Contrastive Predictive Coding.** WWW 2021. [paper](https://arxiv.org/abs/2011.14097)
    *Shohreh Deldari, Daniel V. Smith, Hao Xue, Flora D. Salim.*
    

##### [Anomaly Detection](#content)

1. **Real-Time Anomaly Detection for Streaming Analytics.** arXiv 2016. [paper](https://arxiv.org/pdf/1607.02480.pdf)
    *Subutai Ahmad, Scott Purdy.*

1. **USAD: UnSupervised Anomaly Detection on Multivariate Time Series.** KDD 2020. [paper](https://dl.acm.org/doi/10.1145/3394486.3403392)
    *Julien Audibert , Pietro Michiardi , Frédéric Guyard , Sébastien Marti , Maria A. Zuluaga.*

1. **Detecting Suspicious Pattern Absences in Continuous Time Series.** SIAM 2020. [paper](https://epubs.siam.org/doi/10.1137/1.9781611976236.15)
    *JVincent Vercruyssen, Wannes Meert and Jesse Davis.*
    
1. **Trajectory Outlier Detection: Algorithms, Taxonomies,
Evaluation, and Open Challenges.** ACM 2020. [paper](https://kristiania.brage.unit.no/kristiania-xmlui/bitstream/handle/11250/2754894/Belhadi.pdf?sequence=1)
    *Asma Belhadi , Youcef Djenouri , Jerry Chun-Wei Lin , Alberto Cano.*

1. **An overview on trajectory outlier detection.** Springer 2018. [paper](https://www.researchgate.net/publication/322898173_An_overview_on_trajectory_outlier_detection)
    *Fanrong Meng.*



#### [Self-supervised Learning](#content)

1. **Transfer Learning or Self-supervised Learning? A Tale of Two Pretraining Paradigms.** arXiv 2020. [paper](https://arxiv.org/abs/2007.04234)
    *Xingyi Yang, Xuehai He, Yuxiao Liang, Yue Yang, Shanghang Zhang, Pengtao Xie.*



#### [Knowledge Distillation](#content)

1. **Knowledge Distillation and Student-Teacher Learning for Visual Intelligence: A Review and New Outlooks.** IEEE 2021. [paper](https://arxiv.org/abs/2004.05937)
    *Lin Wang, Kuk-Jin Yoon.*

1. **Knowledge Distillation: A Survey.** arVix 2020. [paper](https://arxiv.org/abs/2004.05937)
    *Jianping Gou, Baosheng Yu, Stephen John Maybank, Dacheng Tao.*

1. **Online Knowledge Distillation with Diverse Peers.** AAAI 2020. [paper](https://www.semanticscholar.org/paper/Online-Knowledge-Distillation-with-Diverse-Peers-Chen-Mei/35d39c2f61277a89d09dc899fa467ade6a3789af)
    *Defang Chen, Jian-Ping Mei, Can Wang, Yan Feng, Chun Chen.*

1. **TinyBERT: Distilling BERT for Natural Language Understanding.** arVix 2019. [paper](https://arxiv.org/abs/1909.10351)
    *Xiaoqi Jiao, Yichun Yin, Lifeng Shang, Xin Jiang, Xiao Chen, Linlin Li, Fang Wang, Qun Liu.*

1. **FastBERT: a Self-distilling BERT with Adaptive Inference Time.** ACL 2020. [paper](https://arxiv.org/abs/2004.02178)
    *Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Haotang Deng, Qi Ju.*

1. **Improved Knowledge Distillation via Teacher Assistant.** AAAI 2020. [paper](https://www.semanticscholar.org/paper/Improved-Knowledge-Distillation-via-Teacher-Mirzadeh-Farajtabar/c4c703d1bc2ac6bdca7e76c8e2cbde0314579b9b)
    *S. Mirzadeh, Mehrdad Farajtabar, Ang Li, Nir Levine, Akihiro Matsukawa, H. Ghasemzadeh.*

1. **Learning Lightweight Lane Detection CNNs by Self Attention Distillation.** arVix 2019. [paper](https://arxiv.org/abs/1908.00821)
    *Yuenan Hou, Zheng Ma, Chunxiao Liu, Chen Change Loy.*

1. **Distilling Task-Specific Knowledge from BERT into Simple Neural Networks.** arVix 2019. [paper](https://arxiv.org/abs/1903.12136)
    *Raphael Tang, Yao Lu, Linqing Liu, Lili Mou, Olga Vechtomova, Jimmy Lin.*

1. **Knowledge Distillation by On-the-Fly Native Ensemble.** NeurIPS 2018. [paper](https://www.semanticscholar.org/paper/Knowledge-Distillation-by-On-the-Fly-Native-Lan-Zhu/c864e3785a9aecf25296781c272980eaed78e51a)
    *Xu Lan, Xiatian Zhu, S. Gong.*

1. **Born-Again Neural Networks.** PMLR 2018. [paper](https://proceedings.mlr.press/v80/furlanello18a/furlanello18a.pdf)
    *Tommaso Furlanello, Zachary C. Lipton, Michael Tschannen, Laurent Itti, Anima Anandkumar.*

1. **Distilling a Neural Network Into a Soft Decision Tree.** arVix 2017. [paper](https://arxiv.org/abs/1711.09784)
    *Nicholas Frosst, Geoffrey Hinton.*

1. **Sequence-Level Knowledge Distillation.** IEEE 2016. [paper](https://arxiv.org/abs/1606.07947)
    *Yoon Kim, Alexander M. Rush.*

##### [Symbolic | Commonsense](#content)

1. **Symbolic Knowledge Distillation: from General Language Models to Commonsense Models.** NAACL 2022. [paper](https://aclanthology.org/2022.naacl-main.341/)
   *Peter West, Chandra Bhagavatula, Jack Hessel, Jena Hwang, Liwei Jiang, Ronan Le Bras, Ximing Lu, Sean Welleck, Yejin Choi.*



#### [Knowledge Engine](#Content)

1. **HAKE: Human Activity Knowledge Engine.** CVPR'18/19/20, NeurIPS'20, TPAMI'21. [github](https://github.com/DirtyHarryLYL/HAKE)
   *Shanghai Jiao Tong University.*



#### [Neural Architecture Search](#content)

1. **Neural Architecture Search: A Survey.** JMLR 2019. [paper](https://www.jmlr.org/papers/volume20/18-598/18-598.pdf)
    *Thomas Elsken, Jan Hendrik Metzen, Frank Hutter.*

1. **A Comprehensive Survey of Neural Architecture Search: Challenges and Solutions.** ACM 2020. [paper](https://arxiv.org/abs/2006.02903)
    *Pengzhen Ren, Yun Xiao, Xiaojun Chang, Po-Yao Huang, Zhihui Li, Xiaojiang Chen, Xin Wang.*

1. **BayesNAS: A Bayesian Approach for Neural Architecture Search.** arVix 2019. [paper](https://www.semanticscholar.org/paper/BayesNAS%3A-A-Bayesian-Approach-for-Neural-Search-Zhou-Yang/93c4478a5f6e22925ac0582105e4fb5a94e787a7)
    *Hongpeng Zhou, M. Yang, J. Wang, Wei Pan.*

1. **FP-NAS: Fast Probabilistic Neural Architecture Search.** CVPR 2021. [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Yan_FP-NAS_Fast_Probabilistic_Neural_Architecture_Search_CVPR_2021_paper.pdf)
    *Zhicheng Yan, Xiaoliang Dai, Peizhao Zhang, Yuandong Tian, Bichen Wu, Matt Feiszli.*

1. **CP-NAS: Child-Parent Neural Architecture Search for 1-bit CNNs.** IJCAI 2020. [paper](https://arxiv.org/abs/2005.00057)
    *Li'an Zhuo, Baochang Zhang, Hanlin Chen, Linlin Yang, Chen Chen, Yanjun Zhu, David Doermann.*
    


#### [Transformer](#content)

1. **Efficient Transformers: A Survey.** arVix 2020. [paper](https://arxiv.org/abs/2009.06732)
    *Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler.*

1. **Long Range Arena: A Benchmark for Efficient Transformers.** arVix 2020. [paper](https://arxiv.org/abs/2011.04006)
    *Yi Tay, Mostafa Dehghani, Samira Abnar, Yikang Shen, Dara Bahri, Philip Pham, Jinfeng Rao, Liu Yang, Sebastian Ruder, Donald Metzler.*

1. **Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting.** arVix 2020. [paper](https://arxiv.org/abs/2012.07436)
    *Haoyi Zhou, Shanghang Zhang, Jieqi Peng, Shuai Zhang, Jianxin Li, Hui Xiong, Wancai Zhang.*

1. **The Evolved Transformer.** ICML 2019. [paper](https://arxiv.org/abs/1901.11117)
    *David R. So, Chen Liang, Quoc V. Le.*



### [Notebooks](#content)

1. **Pytorch Tutorial by Stanford 224n.**  [link](https://web.stanford.edu/class/cs224n/materials/CS224N_PyTorch_Tutorial.html)
1. **Trajectory Outlier Detection.**  [link](https://docs.google.com/document/d/1DlQEsF-5l1OMhmflhH29dJ3wL3DEzEWVExxA56admVI/edit?usp=sharing) For USDA Animal Science Project
1. **Literature Review - Animal Movement with ML.**  [link](https://docs.google.com/document/d/17o5uYJmBdvni6CwfIFJPWchNGcRxGleY18i2HGaXu1c/edit?usp=sharing) 
1. **Contrastive Learning.**  [link](https://docs.google.com/document/d/1MtjsTzu7uTvWnZ8rZ11P6_RemtZE59vlg-ISzMKGYb8/edit?usp=sharing)

### [Foundations of Deep Learning](#content)

**YouTube - Complete Deep Learning.**  [link](https://www.youtube.com/watch?v=mH9GBJ6og5A&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=7) 

**Coding Practice.** [github repo](https://github.com/HuiyingC/deep_learning_practice)  

1. **Basics - Actication Functions, BackPropagation, SGD & GD, Optimizers, Loss Functions, ANN, CNN, etc..** [note](https://docs.google.com/document/d/1N_pN_1e2B6Ytjx7Xl_f6P0G8HnbyKovUPRdZ3V4U4wo/edit?usp=sharing) [code](https://colab.research.google.com/drive/1SVbHVL7SuUonq66Y9d7SW60r5O6qvjCI?usp=sharing)

1. **NLP.**  [note](https://docs.google.com/document/d/1JMJXKoWg5ezUXpITkGcIJQRKKOYN4R8Ita6qhEJuJ2M/edit?usp=sharing)
	1. **Word Embedding.**  [video](https://www.youtube.com/watch?v=pO_6Jk0QtKw&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=42) [code](https://colab.research.google.com/drive/1iWDevNf3MsGmx4jyP9OoydG00Nh-UblS?usp=sharing) [blog](https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/) 
	1. **Faker News Classifier Using LSTM.**  [video](https://www.youtube.com/watch?v=MXPh_lMRwAI&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=45) [code](https://colab.research.google.com/drive/1uosj0pCty_g5z-FNbcEJEKG-Ig0J5Wgx?usp=sharing) 
	1. **Stock Price Prediction And Forecasting Using Stacked LSTM.**  [video](https://www.youtube.com/watch?v=H6du_pfuznE&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=46)  [code](https://colab.research.google.com/drive/1DpxtBGcosxzx8JzdJW__4_6UHe7vPGRZ?usp=sharing)  [blog](https://machinelearningmastery.com/time-series-prediction-with-deep-learning-in-python-with-keras/)
	1. **Fake News Classifier Using Bidirectional LSTM RNN.**  [video](https://www.youtube.com/watch?v=RpTmnRGJvRQ&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=48) [code](https://colab.research.google.com/drive/1Eyjawqz_WbuyUDcBWM0uynnccVqeryLc?usp=sharing) 
	1. **Deep Learning End To End Project - A simple Flask app to classify uploaded images by VGG19 transfer learning.**  [video](https://www.youtube.com/watch?v=UeydWKkjwwE&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=50) [code](https://github.com/HuiyingC/Flask_upload_image_classification) 
	1. **Encoder And Decoder - Language Translation & Inference (sequence-to-sequence).**  [video](https://www.youtube.com/watch?v=f-JCCOHwx1c&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=52&ab_channel=KrishNaik)  [code](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/nlp/ipynb/lstm_seq2seq.ipynb#scrollTo=wEAFiThefecS)  [blog](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html) [dataset](http://www.manythings.org/anki/) 
	1. **NeurIPS 2014 Sequence to Sequence Learning with Neural Networks.**  [paper](https://proceedings.neurips.cc/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)
	1. **ICLR 2015 Neural Machine Translation by Jointly Learning to Align and Translate - To Solve the Problem in Encoder and Decoder.**  [paper](https://arxiv.org/pdf/1409.0473.pdf)

1. **Time Series.**  
	1. **LSTM.**  [blog](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
	1. **Self-Supervised Representation Learning.**  [blog](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html)

1. **Recommendation System.**  [github repo](https://github.com/HuiyingC/movie_recommender)

1. **Reinforcement Learning.**  [note](https://docs.google.com/document/d/10TF-JRqnh2ZGKR6R05L3yq7FusbPNYa1uK51sj718eo/edit?usp=sharing)  [github repo](https://github.com/HuiyingC/reinforcement_leaning)


### [Tools](#content)

1. **Paper With Code - Find papers with open source code.**  [link](https://paperswithcode.com/)
1. **Connected Papers - Explore connected papers in a visual graph.**  [link](https://www.connectedpapers.com/)
1. **Research Rabbit - Reimagine Research. We’re rethinking everything: literature search, alerts, and more**  [link](https://www.researchrabbit.ai/)
1. **Open Knowledge Maps - A visual interface to the world's scientific knowledge**  [link](https://openknowledgemaps.org/index)
1. **DeepL Translator.**  [link](https://www.deepl.com/translator)
1. **Paper Digest - Summarizes academic articles.**  [link](https://www.paper-digest.com/)
1. **Academic Phrasebank - Academic writing hints.**  [link](https://www.phrasebank.manchester.ac.uk/)
1. **Pro Writing Aid - Grammar and style checking.**  [link](https://prowritingaid.com/)
1. **Quillbot - Rewrite and enhance any sentence.**  [link](https://quillbot.com/)
1. **ML Visuals - Out-of-box ML figures.**  [link](https://github.com/dair-ai/ml-visuals)
1. **Netron - Viewer for neural network, deep learning, and machine learning models.**  [link](https://www.electronjs.org/apps/netron)


### [Resources](#content)

1. **Tiingo - A Reliable, Enterprise-Grade Financial Markets API.**  [link](https://api.tiingo.com/)


### [People](#content)
1. **Graph Representation Learning - Constrastive Learning.**
	1. **Ming Jin (GRAND Lab at Monash University).** [google-scholar](https://scholar.google.com/citations?hl=en&user=I2xvKaIAAAAJ) [profile](https://kimmeen.github.io/)	
	1. **Prof. Shirui Pan (GRAND Lab at Monash University).** [google-scholar](https://scholar.google.com.au/citations?hl=en&user=frWRJN4AAAAJ&view_op=list_works&sortby=pubdate) [profile](https://shiruipan.github.io/)	
	1. **Yuning You (Shen Lab at Texas A&M University).** [google-scholar](https://scholar.google.com/citations?user=KEwC1N8AAAAJ&hl=en) [profile](https://yyou1996.github.io/publications/)
	1. **Yanqiao Zhu (Institute of Automation, Chinese Academy of Sciences).** [google-scholar](https://scholar.google.com/citations?hl=en&user=NBbJT3AAAAAJ) [profile](https://sxkdz.github.io/)





