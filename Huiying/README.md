# Huiying's Work (PhD thesis)
This repository maintains a list of materials that Huiying looks into. 

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#Papers">Papers </a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Graph-Data">Graph Data</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Contrastive-Learning">Contrastive Learning</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Diffusion">Diffusion</a></td></tr>
	
<tr><td colspan="2">&emsp;<a href="#Sequential-Data">Sequential Data</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Change-Point-Detection">Change Point Detection</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Anomaly-Detection">Anomaly Detection</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Data-Imputation">Data Imputation</a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Predictive-Learning">Predictive Learning </a></td></tr>
	<tr><td colspan="2">&emsp;&emsp;<a href="#Transformer">Transformer</a></td></tr>

<tr><td colspan="2">&emsp;<a href="#Un/Self-supervised-Learning">Un/Self-supervised Learning</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Knowledge-Distillation">Knowledge Distillation</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Neural-Architecture-Search">Neural Architecture Search</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Attention">Attention</a></td></tr>

<tr><td colspan="2"><a href="#Notebooks">Notebooks </a></td></tr>
<tr><td colspan="2"><a href="#Foundations-of-Deep-Learning">Foundations of Deep Learning </a></td></tr>
<tr><td colspan="2"><a href="#Tools">Tools </a></td></tr>
<tr><td colspan="2"><a href="#Resources">Resources </a></td></tr>
<tr><td colspan="2"><a href="#People">People </a></td></tr>	
</table>

### [Papers](#content)

#### [Contrastive Learning](#content)

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
    

#### [Data Imputation](#content)

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
    

#### [Change Point Detection](#content)

1. **An Evaluation of Change Point Detection Algorithms.** arXiv.stat.ML 2020. [paper](https://arxiv.org/abs/2003.06222)
    *Gerrit J.J. van den Burg, Christopher K.I. Williams.*

1. **A Survey of Methods for Time Series Change Point Detection.** ACM 2017. [paper](https://www.researchgate.net/publication/307947624_A_Survey_of_Methods_for_Time_Series_Change_Point_Detection)
    *Samaneh Aminikhanghahi, Diane J Cook.*

1. **Bayesian Online Changepoint Detection.** arXiv.stat.ML 2007. [paper](https://arxiv.org/abs/0710.3742)
    *Ryan Prescott Adams, David J.C. MacKay.*

1. **Time Series Change Point Detection with Self-Supervised Contrastive Predictive Coding.** WWW'2021. [paper](https://arxiv.org/abs/2011.14097)
    *Shohreh Deldari, Daniel V. Smith, Hao Xue, Flora D. Salim.*
    

#### [Anomaly Detection](#content)

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


#### [Un/Self-supervised Learning](#content)

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

1. **Distilling BERT into Simple Neural Networks with Unlabeled Transfer Data.** arVix 2019. [paper](https://arxiv.org/abs/1910.01769)
    *Subhabrata Mukherjee, Ahmed Hassan Awadallah.*

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
    

#### [Attention](#content)

1. **Attention Is All You Need.** NeurlPS 2017. [paper](https://arxiv.org/abs/1706.03762)
    *Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin.*
    
1. **Effective Approaches to Attention-based Neural Machine Translation.** ACL 2015. [paper](https://aclanthology.org/D15-1166/)
    *Thang Luong, Hieu Pham, Christopher D. Manning.*


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





