# Must-read papers on Graph Generation models, algorithms and applications


Contributed by Jianjun Hu, Yuxin Li, Alir, Chris, Rongzhi, Yong zhao.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#basic-models">2.1 Basic Models</a></td>
    <td>&ensp;<a href="#graph-types">2.2 Graph Types</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#pooling-methods">2.3 VAE: Variational Autoencoder models</a></td>
    <td>&ensp;<a href="#analysis">2.4 GAN: generative adversarial networks</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#efficiency">2.5 Auto-regressive models</a></td>
    <td></td>
</tr>
<tr><td colspan="2"><a href="#SourceCode">3. Open source codes</a></td></tr> 

<tr><td colspan="2"><a href="#benchmark">4. Benchmark Datasets</a></td></tr> 

<tr><td colspan="2"><a href="#Leaderboard">5. Leaderboards and SOTA performance</a></td></tr> 

<tr><td colspan="2"><a href="#applications">6. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#physics">Physics</a></td>
    <td>&ensp;<a href="#chemistry">Chemistry</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Organic-Materials">Organic Materials</a></td>
    <td>&emsp;<a href="#Inorganic-Materials">Inorganic Materials</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#biology">Biology</a></td>
    <td>&emsp;<a href="#Pharmacy">Pharmacy: drug design</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Media-Generation">Image/Video/Sound/Speech Synthesis </a></td>
    <td>&emsp;<a href="#Language-Synthesis">Natural language generation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#programs">Program synthesis</a></td>
    <td>&ensp;<a href="#computer-network">Computer Network design</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#engineering">Engineering design: circuits/systems synthesis</a></td>
    <td>&ensp;<a href="#knowledgegraph">Knowledge Graph</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#Music-generation">Graph mining</a></td>
    <td>&ensp;<a href="#misc">Other applications</a></td>
</tr>
</table>

## [Survey papers](#content)
1. Must read papers on graphical neural networks [link](https://github.com/thunlp/GNNPapers)

1. **Introduction to Graph Neural Networks.** Synthesis Lectures on Artificial Intelligence and Machine Learning, Morgan & Claypool Publishers, 2020. [book](https://www.morganclaypool.com/doi/10.2200/S00980ED1V01Y202001AIM045)

    *Zhiyuan Liu, Jie Zhou.* 

1. **Graph Neural Networks: A Review of Methods and Applications.** arxiv 2018. [paper](https://arxiv.org/pdf/1812.08434.pdf)
   
    *Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun.* 

1. **A Comprehensive Survey on Graph Neural Networks.** arxiv 2019. [paper](https://arxiv.org/pdf/1901.00596.pdf)

    *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu.*
    

1. **Deep Learning on Graphs: A Survey.** arxiv 2018. [paper](https://arxiv.org/pdf/1812.04202.pdf)

    *Ziwei Zhang, Peng Cui, Wenwu Zhu.*


1. **Geometric Deep Learning: Going beyond Euclidean data.** IEEE SPM 2017. [paper](https://arxiv.org/pdf/1611.08097.pdf)

    *Bronstein, Michael M and Bruna, Joan and LeCun, Yann and Szlam, Arthur and Vandergheynst, Pierre.*

1. **Computational Capabilities of Graph Neural Networks.** IEEE TNN 2009. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4703190)

    *Scarselli, Franco and Gori, Marco and Tsoi, Ah Chung and Hagenbuchner, Markus and Monfardini, Gabriele.*

1. **Neural Message Passing for Quantum Chemistry.** ICML 2017. [paper](https://arxiv.org/pdf/1704.01212.pdf)

    *Gilmer, Justin and Schoenholz, Samuel S and Riley, Patrick F and Vinyals, Oriol and Dahl, George E.*

1. **Non-local Neural Networks.** CVPR 2018. [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Non-Local_Neural_Networks_CVPR_2018_paper.pdf)

    *Wang, Xiaolong and Girshick, Ross and Gupta, Abhinav and He, Kaiming.*

1. **The Graph Neural Network Model.** IEEE TNN 2009. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4700287)

    *Scarselli, Franco and Gori, Marco and Tsoi, Ah Chung and Hagenbuchner, Markus and Monfardini, Gabriele.*
    
1. **Benchmarking Graph Neural Networks.** arxiv 2020. [paper](https://arxiv.org/pdf/2003.00982.pdf)

    *Dwivedi, Vijay Prakash and Joshi, Chaitanya K. and Laurent, Thomas and Bengio, Yoshua and Bresson, Xavier.*

1. **Foundations and modelling of dynamic networks using Dynamic Graph Neural Networks: A survey.** arxiv 2020. [paper](https://arxiv.org/abs/2005.07496)

    *Skarding, Joakim and Gabrys, Bogdan and Musial, Katarzyna.*


## [Models](#content)   

### [Basic Models](#content)
1. **Supervised Neural Networks for the Classification of Structures.** IEEE TNN 1997. [paper](https://ieeexplore.ieee.org/abstract/document/572108)

    *Alessandro Sperduti and Antonina Starita.*

1. **Graphical-Based Learning Environments for Pattern Recognition.** SSPR/SPR 2004. [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-540-27868-9_4.pdf)

    *Franco Scarselli, Ah Chung Tsoi, Marco Gori, Markus Hagenbuchner.*

1. **A new model for learning in graph domains.** IJCNN 2005. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/4202380_A_new_model_for_earning_in_raph_domains/links/0c9605188cd580504f000000.pdf)

    *Marco Gori, Gabriele Monfardini, Franco Scarselli.*

1. **Graph Neural Networks for Ranking Web Pages.** WI 2005. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/221158677_Graph_Neural_Networks_for_Ranking_Web_Pages/links/0c9605188cd5090ede000000/Graph-Neural-Networks-for-Ranking-Web-Pages.pdf)

    *Franco Scarselli, Sweah Liang Yong, Marco Gori, Markus Hagenbuchner, Ah Chung Tsoi, Marco Maggini.*

1. **Neural Network for Graphs: A Contextual Constructive Approach.** IEEE TNN 2009. [paper](https://ieeexplore.ieee.org/abstract/document/4773279)

    *Alessio Micheli.*
    
1. **Spectral Networks and Locally Connected Networks on Graphs.** ICLR 2014. [paper](https://arxiv.org/pdf/1312.6203.pdf)

    *Joan Bruna, Wojciech Zaremba, Arthur Szlam, Yann LeCun.*
    
1. **Deep Convolutional Networks on Graph-Structured Data.** arxiv 2015. [paper](https://arxiv.org/pdf/1506.05163.pdf)

    *Mikael Henaff, Joan Bruna, Yann LeCun.*
    
1. **Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering.** NIPS 2016. [paper](http://papers.nips.cc/paper/6081-convolutional-neural-networks-on-graphs-with-fast-localized-spectral-filtering.pdf)

    *Michaël Defferrard, Xavier Bresson, Pierre Vandergheynst.*

1. **Diffusion-Convolutional Neural Networks.** NIPS 2016. [paper](https://arxiv.org/pdf/1511.02136.pdf)

    *James Atwood, Don Towsley.*
    
1. **Gated Graph Sequence Neural Networks.** ICLR 2016. [paper](https://arxiv.org/pdf/1511.05493.pdf)

    *Yujia Li, Daniel Tarlow, Marc Brockschmidt, Richard Zemel.*
    
1. **Learning Convolutional Neural Networks for Graphs.** ICML 2016. [paper](http://proceedings.mlr.press/v48/niepert16.pdf)

    *Mathias Niepert, Mohamed Ahmed, Konstantin Kutzkov.* 
    

    

<details><summary> more </summary> 

21. **Bayesian Semi-supervised Learning with Graph Gaussian Processes.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.04379)

    *Yin Cheng Ng, Nicolò Colombo, Ricardo Silva.*

22. **Adaptive Graph Convolutional Neural Networks.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.03226.pdf)

    *Ruoyu Li, Sheng Wang, Feiyun Zhu, Junzhou Huang.*  

1. **Dual Graph Convolutional Networks for Graph-Based Semi-Supervised Classification.** WWW 2018. [paper](http://delivery.acm.org/10.1145/3190000/3186116/p499-zhuang.pdf?ip=123.134.247.159&id=3186116&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1564108433_6b20d1fe2ab710632bc8434ad3a00bc8)

    *Chenyi Zhuang, Qiang Ma.*

1. **Learning Steady-States of Iterative Algorithms over Graphs.** ICML 2018. [paper](http://proceedings.mlr.press/v80/dai18a/dai18a.pdf)

    *Hanjun Dai, Zornitsa Kozareva, Bo Dai, Alex Smola, Le Song.*

1. **Graph Capsule Convolutional Neural Networks.** ICML 2018 Workshop. [paper](https://arxiv.org/pdf/1805.08090.pdf)

    *Saurabh Verma, Zhi-Li Zhang.*
    
1. **Capsule Graph Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=Byl8BnRcYm)

    *Zhang Xinyi, Lihui Chen.*
    
1. **Graph Wavelet Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1ewdiR5tQ)

    *Bingbing Xu, Huawei Shen, Qi Cao, Yunqi Qiu, Xueqi Cheng.*

1. **Deep Graph Infomax.** ICLR 2019. [paper](https://openreview.net/pdf?id=rklz9iAcKQ)

    *Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.*
    
1. **Predict then Propagate: Graph Neural Networks meet Personalized PageRank.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1gL-2A9Ym)

    *Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann.*

1. **LanczosNet: Multi-Scale Deep Graph Convolutional Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=BkedznAqKQ)

    *Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard Zemel.*

1. **Invariant and Equivariant Graph Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=Syx72jC9tm)

    *Haggai Maron, Heli Ben-Hamu, Nadav Shamir, Yaron Lipman.*

1. **GMNN: Graph Markov Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1905.06214)

    *Meng Qu, Yoshua Bengio, Jian Tang.*
    
1. **Position-aware Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1906.04817)

    *Jiaxuan You, Rex Ying, Jure Leskovec.*

1. **Disentangled Graph Convolutional Networks.** ICML 2019. [paper](http://proceedings.mlr.press/v97/ma19a/ma19a.pdf)

    *Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu.*
    


    
1. **Graph Learning-Convolutional Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.09971.pdf)

    *Bo Jiang, Ziyan Zhang, Doudou Lin, Jin Tang.*

1. **Data Representation and Learning with Graph Diffusion-Embedding Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jiang_Data_Representation_and_Learning_With_Graph_Diffusion-Embedding_Networks_CVPR_2019_paper.pdf)

    *Bo Jiang, Doudou Lin, Jin Tang, Bin Luo.*
    
1. **Label Efficient Semi-Supervised Learning via Graph Filtering.** CVPR 2019. [paper](https://arxiv.org/pdf/1901.09993.pdf)

    *Qimai Li, Xiao-Ming Wu, Han Liu, Xiaotong Zhang, Zhichao Guan.*
    
1. **SPAGAN: Shortest Path Graph Attention Network.** IJCAI 2019. [paper](https://cse.buffalo.edu/~jsyuan/papers/2019/SPAGAN_Shortest_Path_Graph_Attention_Network.pdf)

    *Yiding Yang, Xinchao Wang, Mingli Song, Junsong Yuan, Dacheng Tao.*
    
1. **Topology Optimization based Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_to.pdf)

    *Liang Yang, Zesheng Kang, Xiaochun Cao, Di Jin, Bo Yang, Yuanfang Guo.*
    
1. **Hierarchical Graph Convolutional Networks for Semi-supervised Node Classification.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.06667.pdf)

    *Fenyu Hu, Yanqiao Zhu, Shu Wu, Liang Wang, Tieniu Tan.*
    
1. **Masked Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_mask.pdf)

    *Liang Yang, Fan Wu, Yingkui Wang, Junhua Gu, Yuanfang Guo.*
    
1. **Dual Self-Paced Graph Convolutional Network: Towards Reducing Attribute Distortions Induced by Topology.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_paced.pdf)

    *Liang Yang, Zhiyang Chen, Junhua Gu, Yuanfang Guo.* 

1. **Bayesian graph convolutional neural networks for semi-supervised classification.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.11103.pdf)

    *Yingxue Zhang, Soumyasundar Pal, Mark Coates, Deniz Üstebay.*
    
1. **GeniePath: Graph Neural Networks with Adaptive Receptive Paths.** AAAI 2019. [paper](https://arxiv.org/pdf/1802.00910.pdf)

    *Ziqi Liu, Chaochao Chen, Longfei Li, Jun Zhou, Xiaolong Li, Le Song, Yuan Qi.*
    
1. **Gaussian-Induced Convolution for Graphs.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.04393.pdf)

    *Jiatao Jiang, Zhen Cui, Chunyan Xu, Jian Yang.*
    
1. **Fisher-Bures Adversary Graph Convolutional Networks.** UAI 2019. [paper](https://arxiv.org/pdf/1903.04154.pdf)

    *Ke Sun, Piotr Koniusz, Zhen Wang.*
    
1. **N-GCN: Multi-scale Graph Convolution for Semi-supervised Node Classification.** UAI 2019. [paper](https://arxiv.org/pdf/1802.08888.pdf)

    *Sami Abu-El-Haija, Amol Kapoor, Bryan Perozzi, Joonseok Lee.*
    

1. **A Flexible Generative Framework for Graph-based Semi-supervised Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-1831)

	*Jiaqi Ma, Weijing Tang, Ji Zhu, Qiaozhu Mei.*

1. **Semi-Implicit Graph Variational Auto-Encoders.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-5716)

	*Arman Hasanzadeh, Ehsan Hajiramezanali, Krishna Narayanan, Nick Duffield, Mingyuan Zhou, Xiaoning Qian.*

1. **Hyperbolic Graph Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4472)

	*Qi Liu, Maximilian Nickel, Douwe Kiela.*

1. **Hyperbolic Graph Convolutional Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-2699)

	*Ines Chami, Zhitao Ying, Christopher Ré, Jure Leskovec.*

1. **Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-3077)

	*Simon Du, Kangcheng Hou, Russ Salakhutdinov, Barnabas Poczos, Ruosong Wang, Keyulu Xu.*

1. **SNEQ: Semi-supervised Attributed Network Embedding with Attention-based Quantisation.** AAAI 2020. [paper](http://users.monash.edu/~yli/assets/pdf/sneq-aaai-20.pdf)

	*Tao He, Lianli Gao, Jingkuan Song, Xin Wang, Kejie Huang, Yuan-­‐Fang Li.*

1. **Going Deep: Graph Convolutional Ladder-Shape Networks.** AAAI 2020. [paper](https://shiruipan.github.io/publication/aaai-2020-hu/)

	*Ruiqi Hu, Shirui Pan, Guodong Long, Qinghua Lu, Liming Zhu, Jing Jiang.*

1. **Co-GCN for Multi-View Semi-Supervised Learning.** AAAI 2020. [paper]()

	*Shu Li, Wen-­‐Tao Li, Wei Wang.*

1. **Graph Representation Learning via Ladder Gamma Variational Autoencoders.** AAAI 2020. [paper]()

	*Arindam Sarkar, Nikhil Mehta, Piyush Rai.*

1. **GSSNN: Graph Smoothing Splines Neural Networks.** AAAI 2020. [paper](https://shiruipan.github.io/publication/aaai-2020-zhu/)

	*Shichao Zhu, Lewei Zhou, Shirui Pan, Chuan Zhou, Guiying Yan, Bin Wang.*

1. **Effective Decoding in Graph Auto-Encoder using Triadic Closure.** AAAI 2020. [paper](https://arxiv.org/abs/1911.11322)

	*Han Shi, Haozheng Fan, James T. Kwok.*

1. **An Attention-based Graph Neural Network for Heterogeneous Structural Learning.** AAAI 2020. [paper](https://arxiv.org/abs/1912.10832)

	*Huiting Hong, Hantao Guo, Yucheng Lin, Xiaoqing Yang, Zang Li, Jieping Ye.*

1. **Fast and Deep Graph Neural Networks.** AAAI 2020. [paper](https://arxiv.org/abs/1911.08941)

	*Claudio Gallicchio, Alessio Micheli.*

1. **Hypergraph Label Propagation Network.** AAAI 2020. [paper]()

	*Yubo Zhang, Nan Wang, Yufeng Chen, Changqing Zou, Hai Wan, Xibin Zhao, Yue Gao.*

1. **Learning Signed Network Embedding via Graph Attention.** AAAI 2020. [paper]()

	*Yu Li, Yuan Tian, Jiawei Zhang, Yi Chang.*

1. **GraLSP: Graph Neural Networks with Local Structural Patterns.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07675)

	*Yilun Jin, Guojie Song, Chuan Shi.*

1. **ASAP: Adaptive Structure Aware Pooling for Learning Hierarchical Graph Representations.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07979)

	*Ekagra Ranjan, Soumya Sanyal, Partha Pratim Talukdar.*

1. **Multi‐Stage Self­‐Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes.** AAAI 2020. [paper](https://zhouchenlin.github.io/Publications/2020-AAAI-M3S.pdf)

	*Ke Sun, Zhouchen Lin, Zhanxing Zhu.*

1. **Collaborative Graph Convolutional Networks: Unsupervised Learning Meets Semi-­‐Supervised Learning.** AAAI 2020. [paper]()

	*Binyuan Hui,  Pengfei Zhu, Qinghua, Hu.*

1. **A Multi­‐Scale Approach for Graph Link Prediction.** AAAI 2020. [paper]()

	*Lei Cai, Shuiwang Ji.*

1. **Adaptive Structural Fingerprints for Graph Attention Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJxWx0NYPr)

	*Kai Zhang, Yaokang Zhu, Jun Wang, Jie Zhang.*

1. **Strategies for Pre-training Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=HJlWWJSFDH)

	*Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec.*

1. **DropEdge: Towards Deep Graph Convolutional Networks on Node Classification.** ICLR 2020. [paper](https://openreview.net/pdf?id=Hkx1qkrKPr)

	*Yu Rong, Wenbing Huang, Tingyang Xu, Junzhou Huang.*

1. **Directional Message Passing for Molecular Graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=B1eWbxStPH)

	*Johannes Klicpera, Janek Groß, Stephan Günnemann.*

1. **DeepSphere: a graph-based spherical CNN.** ICLR 2020. [paper](https://openreview.net/pdf?id=B1e3OlStPB)

	*Michaël Defferrard, Martino Milani, Frédérick Gusset, Nathanaël Perraudin.*

1. **Geom-GCN: Geometric Graph Convolutional Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=S1e2agrFvS)

	*Hongbin Pei, Bingzhe Wei, Kevin Chen-Chuan Chang, Yu Lei, Bo Yang.*

1. **Curvature Graph Network.** ICLR 2020. [paper](https://openreview.net/pdf?id=BylEqnVFDB)

	*Ze Ye, Kin Sum Liu, Tengfei Ma, Jie Gao, Chao Chen.*

1. **Measuring and Improving the Use of Graph Information in Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=rkeIIkHKvS)

	*Yifan Hou, Jian Zhang, James Cheng, Kaili Ma, Richard T. B. Ma, Hongzhi Chen, Ming-Chang Yang.*

1. **Memory-Based Graph Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1laNeBYPB)

	*Amir Hosein Khasahmadi, Kaveh Hassani, Parsa Moradi, Leo Lee, Quaid Morris.*

1. **Pruned Graph Scattering Transforms.** ICLR 2020. [paper](https://openreview.net/pdf?id=rJeg7TEYwB)

	*Vassilis N. Ioannidis, Siheng Chen, Georgios B. Giannakis.*

1. **Neural Execution of Graph Algorithms.** ICLR 2020. [paper](https://openreview.net/pdf?id=SkgKO0EtvS)

	*Petar Veličković, Rex Ying, Matilde Padovano, Raia Hadsell, Charles Blundell.*

1. **GraphSAINT: Graph Sampling Based Inductive Learning Method.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJe8pkHFwS)

	*Hanqing Zeng, Hongkuan Zhou, Ajitesh Srivastava, Rajgopal Kannan, Viktor Prasanna.*

1. **Graph inference learning for semi-supervised classification.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1evOhEKvH)

	*Chunyan Xu, Zhen Cui, Xiaobin Hong, Tong Zhang, Jian Yang, Wei Liu.*

1. **SGAS: Sequential Greedy Architecture Search.** CVPR 2020. [paper](https://arxiv.org/abs/1912.00195)

	*Guohao Li, Guocheng Qian, Itzel C. Delgadillo, Matthias Müller, Ali Thabet, Bernard Ghanem.*

     </details>
### [Graph Types](#content)
1. **DyRep: Learning Representations over Dynamic Graphs.** ICLR 2019. [paper](https://openreview.net/pdf?id=HyePrhR5KX)

    *Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha.*

1. **Hypergraph Neural Networks.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.09401.pdf)

    *Yifan Feng, Haoxuan You, Zizhao Zhang, Rongrong Ji, Yue Gao.*

1. **Heterogeneous Graph Attention Network.** WWW 2019. [paper](https://arxiv.org/pdf/1903.07293.pdf)

    *Xiao Wang, Houye Ji, Chuan Shi, Bai Wang, Peng Cui, P. Yu, Yanfang Ye.*
    
1. **Representation Learning for Attributed Multiplex Heterogeneous Network.** KDD 2019. [paper](https://arxiv.org/pdf/1905.01669.pdf)

    *Yukuo Cen, Xu Zou, Jianwei Zhang, Hongxia Yang, Jingren Zhou, Jie Tang.*
    
1. **ActiveHNE: Active Heterogeneous Network Embedding.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.05659.pdf)
   
    *Xia Chen, Guoxian Yu, Jun Wang, Carlotta Domeniconi, Zhao Li, Xiangliang Zhang.*
    
1. **GCN-LASE: Towards Adequately Incorporating Link Attributes in Graph Convolutional Networks.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.09817.pdf)

    *Ziyao Li, Liang Zhang, Guojie Song.*
    
1. **Dynamic Hypergraph Neural Networks.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0366.pdf)

    *Jianwen Jiang, Yuxuan Wei, Yifan Feng, Jingxuan Cao, Yue Gao.*
    
    
1. **HyperGCN: A New Method For Training Graph Convolutional Networks on Hypergraphs.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-850)

	*Naganand Yadati, Madhav Nimishakavi, Prateek Yadav, Vikram Nitin, Anand Louis, Partha Talukdar.*

1. **Graph Transformer Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-6458)

	*Seongjun Yun, Minbyul Jeong, Raehyun Kim, Jaewoo Kang, Hyunwoo Kim.*

1. **Recurrent Space-time Graph Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-6993)

	*Andrei Nicolicioiu, Iulia Duta, Marius Leordeanu.*

1. **EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs.** AAAI 2020. [paper](https://arxiv.org/abs/1902.10191)

	*Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler, Tao B. Schardl, Charles E. Leiserson.*

1. **Spatial-Temporal Synchronous Graph Convolutional Networks: A New Framework for Spatial-Temporal Network Data Forecasting.** AAAI 2020. [paper](https://github.com/Davidham3/STSGCN/blob/master/paper/AAAI2020-STSGCN.pdf)

	*Chao Song, Youfang Lin, Shengnan Guo, Huaiyu Wan.*

1. **Type-aware Anchor Link Prediction across Heterogeneous Networks based on Graph Attention Network.** AAAI 2020. [paper]()

	*Xiaoxue Li, Yanmin Shang, Yanan Cao, Yangxi Li, Jianlong Tan, Yanbing Liu.*    

1. **Composition-based Multi-Relational Graph Convolutional Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=BylA_C4tPr)

	*Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Partha Talukdar.*

1. **Inductive representation learning on temporal graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=rJeW1yHYwH)

	*da Xu, chuanwei ruan, evren korpeoglu, sushant kumar, kannan achan.*

1. **Hyper-SAGNN: a self-attention based graph neural network for hypergraphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=ryeHuJBtPH)

	*Ruochi Zhang, Yuesong Zou, Jian Ma.*

### [Organic Materials](#content)


1. **StructPool: Structured Graph Pooling via Conditional Random Fields.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJxg_hVtwH)

	*Hao Yuan, Shuiwang Ji.*

### [Inorganic Materials](#content)
1. **A Comparison between Recursive Neural Networks and Graph Neural Networks.** IJCNN 2006. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1716174)

    *Vincenzo Di Massa, Gabriele Monfardini, Lorenzo Sarti, Franco Scarselli, Marco Maggini, Marco Gori.*
    


### [Pharmacy](#content)
1. **Stochastic Training of Graph Convolutional Networks with Variance Reduction.** ICML 2018. [paper](http://www.scipaper.net/uploadfile/2018/0716/20180716100330880.pdf)
   
    *Jianfei Chen, Jun Zhu, Le Song.*
    



## [Applications](#content)

### [Physics](#content)

1. **Discovering objects and their relations from entangled scene representations.** ICLR Workshop 2017. [paper](https://arxiv.org/pdf/1702.05068.pdf)

    *David Raposo, Adam Santoro, David Barrett, Razvan Pascanu, Timothy Lillicrap, Peter Battaglia.*  

1. **A simple neural network module for relational reasoning.** NIPS 2017. [paper](https://arxiv.org/pdf/1706.01427.pdf)

    *Adam Santoro, David Raposo, David G.T. Barrett, Mateusz Malinowski, Razvan Pascanu, Peter Battaglia, Timothy Lillicrap.*  

1. **Interaction Networks for Learning about Objects, Relations and Physics.** NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

    *Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu.* 

1. **Graph networks as learnable physics engines for inference and control.** ICML 2018. [paper](https://arxiv.org/pdf/1806.01242.pdf)

    *Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel, Martin Riedmiller, Raia Hadsell, Peter Battaglia.* 


1. **Graph Element Networks: adaptive, structured computation and memory.** ICML 2019. [paper](https://arxiv.org/pdf/1904.09019)

    *Ferran Alet, Adarsh K. Jeewajee, Maria Bauza, Alberto Rodriguez, Tomas Lozano-Perez, Leslie Pack Kaelbling.*

1. **Physics-aware Difference Graph Networks for Sparsely-Observed Dynamics.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1gelyrtwH)

	*Sungyong Seo, Chuizheng Meng, Yan Liu.*

### [Biology](#content)

1. **Convolutional networks on graphs for learning molecular fingerprints.** NIPS 2015. [paper](https://arxiv.org/pdf/1509.09292.pdf)

    *David Duvenaud, Dougal Maclaurin, Jorge Aguilera-Iparraguirre, Rafael Gómez-Bombarelli, Timothy Hirzel, Alán Aspuru-Guzik, Ryan P. Adams.* 

1. **Molecular Graph Convolutions: Moving Beyond Fingerprints.** Journal of computer-aided molecular design 2016. [paper](https://arxiv.org/pdf/1603.00856.pdf)

    *Steven Kearnes, Kevin McCloskey, Marc Berndl, Vijay Pande, Patrick Riley.* 

1. **Protein Interface Prediction using Graph Convolutional Networks.** NIPS 2017. [paper](http://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks.pdf)

    *Alex Fout, Jonathon Byrd, Basir Shariat, Asa Ben-Hur.* 

1. **Hybrid Approach of Relation Network and Localized Graph Convolutional Filtering for Breast Cancer Subtype Classification.** IJCAI 2018. [paper](https://arxiv.org/abs/1711.05859)

    *Sungmin Rhee, Seokjun Seo, Sun Kim.*

1. **Modeling polypharmacy side effects with graph convolutional networks.** ISMB 2018. [paper](https://arxiv.org/abs/1802.00543)

    *Marinka Zitnik, Monica Agrawal, Jure Leskovec.*

1. **Spectral Multigraph Networks for Discovering and Fusing Relationships in Molecules.** NeurIPS Workshop 2018. [paper](https://arxiv.org/pdf/1811.09595.pdf)

    *Boris Knyazev, Xiao Lin, Mohamed R. Amer, Graham W. Taylor.*

1. **MR-GNN: Multi-Resolution and Dual Graph Neural Network for Predicting Structured Entity Interactions.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.09558.pdf)

    *Nuo Xu, Pinghui Wang, Long Chen, Jing Tao, Junzhou Zhao.*

1. **Graph Transformation Policy Network for Chemical Reaction Prediction.** KDD 2019. [paper](https://arxiv.org/pdf/1812.09441)

    *Kien Do, Truyen Tran, Svetha Venkatesh.*

1. **Learning Multimodal Graph-to-Graph Translation for Molecular Optimization.** ICLR 2019. [paper](https://openreview.net/pdf?id=B1xJAsA5F7)

    *Wengong Jin, Kevin Yang, Regina Barzilay, Tommi Jaakkola.*

1. **A Generative Model For Electron Paths.** ICLR 2019. [paper](https://openreview.net/pdf?id=r1x4BnCqKX)

    *John Bradshaw, Matt J. Kusner, Brooks Paige, Marwin H. S. Segler, José Miguel Hernández-Lobato.*

1. **Retrosynthesis Prediction with Conditional Graph Logic Network.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4761)

	*Hanjun Dai, Chengtao Li, Connor Coley, Bo Dai, Le Song.*



### [Knowledge Graph](#content)

  
1. **End-to-end Structure-Aware Convolutional Networks for Knowledge Base Completion.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.04441.pdf)

    *Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou.*
    
1. **Knowledge Transfer for Out-of-Knowledge-Base Entities : A Graph Neural Network Approach.** IJCAI 2017. [paper](https://arxiv.org/pdf/1706.05674.pdf)

    *Takuo Hamaguchi, Hidekazu Oiwa, Masashi Shimbo, Yuji Matsumoto.* 






### [Other Applications](#content)

1. **Inductive Matrix Completion Based on Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=ByxxgCEYDS)

	*Muhan Zhang, Yixin Chen.*


### [Media-Generation](#content)
1. **Graph Neural Networks for Object Localization.** ECAI 2006. [paper](http://ebooks.iospress.nl/volumearticle/2775)

    *Gabriele Monfardini, Vincenzo Di Massa, Franco Scarselli, Marco Gori.*

1. **Learning Human-Object Interactions by Graph Parsing Neural Networks.** ECCV 2018. [paper](https://arxiv.org/pdf/1808.07962.pdf)

    *Siyuan Qi, Wenguan Wang, Baoxiong Jia, Jianbing Shen, Song-Chun Zhu.*

1. **Learning Conditioned Graph Structures for Interpretable Visual Question Answering.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1806.07243)

    *Will Norcliffe-Brown, Efstathios Vafeias, Sarah Parisot.*

1. **Symbolic Graph Reasoning Meets Convolutions.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7456-symbolic-graph-reasoning-meets-convolutions.pdf)

    *Xiaodan Liang, Zhiting Hu, Hao Zhang, Liang Lin, Eric P. Xing.*

1. **Out of the Box: Reasoning with Graph Convolution Nets for Factual Visual Question Answering.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7531-out-of-the-box-reasoning-with-graph-convolution-nets-for-factual-visual-question-answering.pdf)

    *Medhini Narasimhan, Svetlana Lazebnik, Alexander Schwing.*

1. **Structural-RNN: Deep Learning on Spatio-Temporal Graphs.** CVPR 2016. [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Jain_Structural-RNN_Deep_Learning_CVPR_2016_paper.pdf)

    *Ashesh Jain, Amir R. Zamir, Silvio Savarese, Ashutosh Saxena.*

1. **Relation Networks for Object Detection.** CVPR 2018. [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Hu_Relation_Networks_for_CVPR_2018_paper.pdf)

    *Han Hu, Jiayuan Gu, Zheng Zhang, Jifeng Dai, Yichen Wei.*

1. **Learning Region features for Object Detection.** ECCV 2018. [paper](https://arxiv.org/pdf/1803.07066)

    *Jiayuan Gu, Han Hu, Liwei Wang, Yichen Wei, Jifeng Dai.*

1. **The More You Know: Using Knowledge Graphs for Image Classification.** CVPR 2017. [paper](https://arxiv.org/pdf/1612.04844.pdf)

    *Kenneth Marino, Ruslan Salakhutdinov, Abhinav Gupta.* 

1. **Understanding Kin Relationships in a Photo.** TMM 2012. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6151163)

    *Siyu Xia, Ming Shao, Jiebo Luo, Yun Fu.* 
    
1. **Graph-Structured Representations for Visual Question Answering.** CVPR 2017. [paper](https://arxiv.org/pdf/1609.05600.pdf)

    *Damien Teney, Lingqiao Liu, Anton van den Hengel.* 

1. **Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.07455.pdf)

    *Sijie Yan, Yuanjun Xiong, Dahua Lin.* 

1. **Dynamic Graph CNN for Learning on Point Clouds.** CVPR 2018. [paper](https://arxiv.org/pdf/1801.07829.pdf)

    *Yue Wang, Yongbin Sun, Ziwei Liu, Sanjay E. Sarma, Michael M. Bronstein, Justin M. Solomon.* 

1. **PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation.** CVPR 2018. [paper](https://arxiv.org/pdf/1612.00593.pdf)
   
    *Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas.* 

1. **3D Graph Neural Networks for RGBD Semantic Segmentation.** CVPR 2017. [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Qi_3D_Graph_Neural_ICCV_2017_paper.pdf)

    *Xiaojuan Qi, Renjie Liao, Jiaya Jia, Sanja Fidler, Raquel Urtasun.* 

1. **Iterative Visual Reasoning Beyond Convolutions.** CVPR 2018. [paper](https://arxiv.org/pdf/1803.11189)

    *Xinlei Chen, Li-Jia Li, Li Fei-Fei, Abhinav Gupta.* 

1. **Dynamic Edge-Conditioned Filters in Convolutional Neural Networks on Graphs.** CVPR 2017. [paper](https://arxiv.org/pdf/1704.02901)

    *Martin Simonovsky, Nikos Komodakis.* 

1. **Situation Recognition with Graph Neural Networks.** ICCV 2017. [paper](https://arxiv.org/pdf/1708.04320)

    *Ruiyu Li, Makarand Tapaswi, Renjie Liao, Jiaya Jia, Raquel Urtasun, Sanja Fidler.* 

1. **Deep Reasoning with Knowledge Graph for Social Relationship Understanding.** IJCAI 2018. [paper](https://arxiv.org/pdf/1807.00504.pdf)

    *Zhouxia Wang, Tianshui Chen, Jimmy Ren, Weihao Yu, Hui Cheng, Liang Lin.* 

1. **I Know the Relationships: Zero-Shot Action Recognition via Two-Stream Graph Convolutional Networks and Knowledge Graphs.** AAAI 2019. [paper](http://nlpr-web.ia.ac.cn/mmc/homepage/jygao/JY_Gao_files/Conference_Papers/AAAI2019-GJY.pdf)
   
    *Junyu Gao, Tianzhu Zhang, Changsheng Xu.*
    
<details><summary>more</summary>

21. **Graph CNNs with Motif and Variable Temporal Block for Skeleton-based Action Recognition.** AAAI 2019. [paper](https://ecs.victoria.ac.nz/foswiki/pub/Groups/Graphics/RGB-DDataProcessingForRobotics/Graph%20CNNs%20with%20Motif%20and%20Variable%20Temporal%20Block%20for%20Skeleton-based%20Action%20Recognition.pdf)

    *Yu-Hui Wen, Lin Gao, Hongbo Fu, Fang-Lue Zhang, Shihong Xia.*
    
1. **Multi-Label Image Recognition with Graph Convolutional Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.03582.pdf)

    *Zhao-Min Chen, Xiu-Shen Wei, Peng Wang, Yanwen Guo.*
    
1. **Spatial-Aware Graph Relation Network for Large-Scale Object Detection.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xu_Spatial-Aware_Graph_Relation_Network_for_Large-Scale_Object_Detection_CVPR_2019_paper.pdf)

    *Hang Xu, Chenhan Jiang, Xiaodan Liang, Zhenguo Li.*
    
1. **GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)

    *Xinhong Ma, Tianzhu Zhang, Changsheng Xu.*
    
1. **Mind Your Neighbours: Image Annotation With Metadata Neighbourhood Graph Co-Attention Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Mind_Your_Neighbours_Image_Annotation_With_Metadata_Neighbourhood_Graph_Co-Attention_CVPR_2019_paper.pdf)

    *Junjie Zhang, Qi Wu, Jian Zhang, Chunhua Shen, Jianfeng Lu.*
    
1. **Attentive Relational Networks for Mapping Images to Scene Graphs.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.10696.pdf)

    *Mengshi Qi, Weijian Li, Zhengyuan Yang, Yunhong Wang, Jiebo Luo.*
    
1. **Knowledge-Embedded Routing Network for Scene Graph Generation.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.03326.pdf)

    *Tianshui Chen, Weihao Yu, Riquan Chen, Liang Lin.*
    
1. **Auto-Encoding Scene Graphs for Image Captioning.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.02378.pdf)

    *Xu Yang, Kaihua Tang, Hanwang Zhang, Jianfei Cai.*
    
1. **Learning to Cluster Faces on an Affinity Graph.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.02749.pdf)

    *Lei Yang, Xiaohang Zhan, Dapeng Chen, Junjie Yan, Chen Change Loy, Dahua Lin.*
    
1. **Learning a Deep ConvNet for Multi-label Classification with Partial Labels.** CVPR 2019. [paper](https://arxiv.org/pdf/1902.09720.pdf)

    *Thibaut Durand, Nazanin Mehrasa, Greg Mori.*
    
1. **Graph Convolutional Label Noise Cleaner: Train a Plug-and-play Action Classifier for Anomaly Detection.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.07256.pdf)

    *Jia-Xing Zhong, Nannan Li, Weijie Kong, Shan Liu, Thomas H. Li, Ge Li.*
    
1. **Learning Actor Relation Graphs for Group Activity Recognition.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.10117.pdf)

    *Jianchao Wu, Limin Wang, Li Wang, Jie Guo, Gangshan Wu.*
    
1. **ABC: A Big CAD Model Dataset For Geometric Deep Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.06216.pdf)

    *Sebastian Koch, Albert Matveev, Zhongshi Jiang, Francis Williams, Alexey Artemov, Evgeny Burnaev, Marc Alexa, Denis Zorin, Daniele Panozzo.*
    
1. **Neighbourhood Watch: Referring Expression Comprehension via Language-guided Graph Attention Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.04794.pdf)

    *Peng Wang, Qi Wu, Jiewei Cao, Chunhua Shen, Lianli Gao, Anton van den Hengel.*
    
1. **Graph-Based Global Reasoning Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.12814.pdf)

    *Yunpeng Chen, Marcus Rohrbach, Zhicheng Yan, Shuicheng Yan, Jiashi Feng, Yannis Kalantidis.*

1. **Linkage Based Face Clustering via Graph Convolution Network.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.11306.pdf)

    *Zhongdao Wang, Liang Zheng, Yali Li, Shengjin Wang.*
    
1. **Fast Interactive Object Annotation with Curve-GCN.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.06874.pdf)

    *Huan Ling, Jun Gao, Amlan Kar, Wenzheng Chen, Sanja Fidler.*
    
1. **Semantic Graph Convolutional Networks for 3D Human Pose Regression.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.03345.pdf)

    *Long Zhao, Xi Peng, Yu Tian, Mubbasir Kapadia, Dimitris N. Metaxas.*
    
1. **Neural Task Graphs: Generalizing to Unseen Tasks from a Single Video Demonstration.** CVPR 2019. [paper](https://arxiv.org/pdf/1807.03480.pdf)

    *De-An Huang, Suraj Nair, Danfei Xu, Yuke Zhu, Animesh Garg, Li Fei-Fei, Silvio Savarese, Juan Carlos Niebles.*
    
1. **Graphonomy: Universal Human Parsing via Graph Transfer Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.04536.pdf)

    *Ke Gong, Yiming Gao, Xiaodan Liang, Xiaohui Shen, Meng Wang, Liang Lin.*
    
1. **Learning Context Graph for Person Search.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.01830.pdf)

    *Yichao Yan, Qiang Zhang, Bingbing Ni, Wendong Zhang, Minghao Xu, Xiaokang Yang.*
    
1. **Occlusion-Net: 2D/3D Occluded Keypoint Localization Using Graph Networks.** CVPR 2019. [paper](http://www.cs.cmu.edu/~mvo/index_files/Papers/ONet_19.pdf)

    *N. Dinesh Reddy, Minh Vo, Srinivasa G. Narasimhan.*
    
1. **MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.00087.pdf)

    *Da Zhang, Xiyang Dai, Xin Wang, Yuan-Fang Wang, Larry S. Davis.*
    
1. **Context-Aware Visual Compatibility Prediction.** CVPR 2019. [paper](https://arxiv.org/pdf/1902.03646.pdf)

    *Guillem Cucurull, Perouz Taslakian, David Vazquez.*
    
1. **Graph Attention Convolution for Point Cloud Semantic Segmentation.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Graph_Attention_Convolution_for_Point_Cloud_Semantic_Segmentation_CVPR_2019_paper.pdf)

    *Lei Wang, Yuchun Huang, Yaolin Hou, Shenman Zhang, Jie Shan.*
    
1. **An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition.** CVPR 2019. [paper](https://arxiv.org/pdf/1902.09130.pdf)

    *Chenyang Si, Wentao Chen, Wei Wang, Liang Wang, Tieniu Tan.*
    
1. **Actional-Structural Graph Convolutional Networks for Skeleton-based Action Recognition.** CVPR 2019. [paper](https://arxiv.org/pdf/1904.12659.pdf)

    *Maosen Li, Siheng Chen, Xu Chen, Ya Zhang, Yanfeng Wang, Qi Tian.*
    
1. **Graph Convolutional Tracking.** CVPR 2019. [paper](http://nlpr-web.ia.ac.cn/mmc/homepage/jygao/JY_Gao_files/Conference_Papers/GCT-CVPR2019-GJY.pdf)

    *Junyu Gao, Tianzhu Zhang, Changsheng Xu.*
    
1. **Two-Stream Adaptive Graph Convolutional Networks for Skeleton-Based Action Recognition.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Two-Stream_Adaptive_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.pdf)

    *Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu.*

1. **Skeleton-Based Action Recognition With Directed Graph Neural Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Skeleton-Based_Action_Recognition_With_Directed_Graph_Neural_Networks_CVPR_2019_paper.pdf)

    *Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu.*
    
1. **Neural Module Networks.** CVPR 2016. [paper](https://arxiv.org/pdf/1511.02799.pdf)

    *Jacob Andreas, Marcus Rohrbach, Trevor Darrell, Dan Klein.*

1. **LatentGNN: Learning Efficient Non-local Relations for Visual Recognition.** ICML 2019. [paper](https://arxiv.org/pdf/1905.11634)

    *Songyang Zhang, Shipeng Yan, Xuming He.*

1. **Graph Convolutional Gaussian Processes.** ICML 2019. [paper](https://arxiv.org/pdf/1905.05739)

    *Ian Walker, Ben Glocker.*

1. **GEOMetrics: Exploiting Geometric Structure for Graph-Encoded Objects.** ICML 2019. [paper](https://arxiv.org/pdf/1901.11461)

    *Edward J. Smith, Scott Fujimoto, Adriana Romero, David Meger.*

1. **Learning Cross­‐modal Context Graph Networks for Visual Grounding.** AAAI 2020. [paper](https://arxiv.org/abs/1911.09042)

	*Yongfei Liu, Bo Wan, Xiaodan Zhu, Xuming He.*

1. **Zero­‐Shot Sketch-based Image Retrieval via Graph Convolution Network.** AAAI 2020. [paper]()

	*Zhaolong Zhang, Yuejie Zhang, Rui Feng, Tao Zhang, Weiguo Fan.*

1. **Hybrid Graph Neural Networks for Crowd Counting.** AAAI 2020. [paper](https://arxiv.org/pdf/2002.00092)

	*Ao Luo, Fan Yang, Xin Li, Dong Nie, Zhicheng Jiao, Shangchen Zhou, Hong Cheng.*

1. **Learning Graph Convolutional Network for Skeleton-­‐based Human Action Recognition by Neural Searching.** AAAI 2020. [paper](https://arxiv.org/abs/1911.04131)

	*Wei Peng, Xiaopeng Hong, Haoyu Chen, Guoying Zhao.*

1. **STEP: Spatial Temporal Graph Convolutional Networks for Emotion Perception from Gaits.** AAAI 2020. [paper](https://arxiv.org/abs/1910.12906)

	*Uttaran Bhattacharya, Trisha Mittal, Rohan Chandra, Tanmay Randhavane, Aniket Bera, Dinesh Manocha.*

1. **Relation‐Aware Pedestrian Attribute Recognition with Graph Convolutional Networks.** AAAI 2020. [paper]()

	*Zichang Tan, Yang Yang, Jun Wan, Stan Li.*

1. **Deep Generative Probabilistic Graph Neural Networks for Scene Graph Generation.** AAAI 2020. [paper](https://grlearning.github.io/papers/135.pdf)

	*Mahmoud Khademi, Oliver Schulte.*

1. **Zero-­‐shot Ingredient Recognition by Multi-­‐Relational Graph Convolutional Network.** AAAI 2020. [paper](http://www.liangmingpan.com/files/publications/AAAI20_Paper.pdf)

	*Jingjing Chen, Liang-Ming Pan, Zhi-Peng Wei, Xiang Wang, Chong-Wah Ngo,Tat-Seng Chua.*

1. **Location-aware Graph Convolutional Networks for Video Question Answering.** AAAI 2020. [paper]()

	*Deng Huang, Peihao Chen, Runhao Zeng, Qing Du, Mingkui Tan, Chuang Gan.*

1. **Facial Action Unit Intensity Estimation via Semantic Correspondence Learning with Dynamic Graph Convolution.** AAAI 2020. [paper]()

	*Fan Yingruo, Jacqueline C.K. Lam, Victor Li.*

1. **Reasoning with Heterogeneous Graph Alignment for Video Question Answering.** AAAI 2020. [paper]()

	*Pin Jiang, Yahong Han.*

1. **Multi-Label Classification with Label Graph Superimposing.** AAAI 2020. [paper](https://arxiv.org/abs/1911.09243)

	*Ya Wang, Dongliang He, Fu Li, Xiang Long, Zhichao Zhou, Jinwen Ma, Shilei Wen.*

1. **Part-Level Graph Convolutional Network for Skeleton-Based Action Recognition.** AAAI 2020. [paper]()

	*Linjiang Huang, Yan Huang, Wanli Ouyang, Liang Wang.*

1. **SOGNet: Scene Overlap Graph Network for Panoptic Segmentation.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07527)

	*Yibo Yang, Hongyang Li, Xia Li, Qijie Zhao, Jianlong Wu, Zhouchen Lin.*

1. **Universal-RCNN: Universal Object Detector via Transferable Graph R-CNN.** AAAI 2020. [paper](https://arxiv.org/abs/2002.07417)

	*Hang Xu, Linpu Fang, Xiaodan Liang, Wenxiong Kang, Zhenguo Li.*

1. **Abstract Diagrammatic Reasoning with Multiplex Graph Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=ByxQB1BKwH)

	*Duo Wang, Mateja Jamnik, Pietro Lio.*

</details>

### [Language-Synthesis](#content)



1. **Exploiting Semantics in Neural Machine Translation with Graph Convolutional Networks.** NAACL 2018. [paper](http://www.aclweb.org/anthology/N18-2078)

    *Diego Marcheggiani, Joost Bastings, Ivan Titov.*

1. **Exploring Graph-structured Passage Representation for Multi-hop Reading Comprehension with Graph Neural Networks.** 2018. [paper](https://arxiv.org/abs/1809.02040)

    *Linfeng Song, Zhiguo Wang, Mo Yu, Yue Zhang, Radu Florian, Daniel Gildea.*

1. **Graph Convolution over Pruned Dependency Trees Improves Relation Extraction.** EMNLP 2018. [paper](https://arxiv.org/abs/1809.10185)

    *Yuhao Zhang, Peng Qi, Christopher D. Manning.*

1. **A Graph-to-Sequence Model for AMR-to-Text Generation.** ACL 2018. [paper](https://arxiv.org/abs/1805.02473)

    *Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea.*
    
1. **Graph-to-Sequence Learning using Gated Graph Neural Networks.** ACL 2018. [paper](https://arxiv.org/pdf/1806.09835.pdf)

    *Daniel Beck, Gholamreza Haffari, Trevor Cohn.*


1. **Graph Convolutional Encoders for Syntax-aware Neural Machine Translation.** EMNLP 2017. [paper](https://arxiv.org/pdf/1704.04675)

    *Joost Bastings, Ivan Titov, Wilker Aziz, Diego Marcheggiani, Khalil Sima'an.* 
    
<details><summary>more</summary>


1. **PaperRobot: Incremental Draft Generation of Scientific Ideas.** ACL 2019. [paper](https://arxiv.org/pdf/1905.07870)

    *Qingyun Wang, Lifu Huang, Zhiying Jiang, Kevin Knight, Heng Ji, Mohit Bansal, Yi Luan.*


1. **GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction.** ACL 2019. [paper](https://tsujuifu.github.io/pubs/acl19_graph-rel.pdf)

    *Tsu-Jui Fu, Peng-Hsuan Li, Wei-Yun Ma.*


1. **Generating Logical Forms from Graph Representations of Text and Entities.** ACL 2019. [paper](https://arxiv.org/pdf/1905.08407)

    *Peter Shaw, Philip Massey, Angelica Chen, Francesco Piccinno, Yasemin Altun.*


1. **Coherent Comment Generation for Chinese Articles with a Graph-to-Sequence Model.** ACL 2019. [paper](https://arxiv.org/pdf/1906.01231)

    *Wei Li, Jingjing Xu, Yancheng He, Shengli Yan, Yunfang Wu, Xu sun.*
    
1. **Structured Neural Summarization.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1ersoRqtm)

    *Patrick Fernandes, Miltiadis Allamanis, Marc Brockschmidt.*
        
1. **Text Generation from Knowledge Graphs with Graph Transformers.** NAACL 2019. [paper](https://arxiv.org/pdf/1904.02342.pdf)

    *Rik Koncel-Kedziorski, Dhanush Bekal, Yi Luan, Mirella Lapata, Hannaneh Hajishirzi.*

1. **Structural Neural Encoders for AMR-to-text Generation.** NAACL 2019. [paper](https://arxiv.org/pdf/1903.11410.pdf)

    *Marco Damonte, Shay B. Cohen.*
    
1. **Graph Transformer for Graph-to-Sequence Learning.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07470)

	*Deng Cai, Wai Lam.*

</details>
   
### [Generation](#content)

1. **Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1806.02473)

    *Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, Jure Leskovec.*

1. **Constrained Generation of Semantically Valid Graphs via Regularizing Variational Autoencoders.** NeurIPS 2018. [paper](https://papers.nips.cc/paper/7942-constrained-generation-of-semantically-valid-graphs-via-regularizing-variational-autoencoders.pdf)

    *Tengfei Ma, Jie Chen, Cao Xiao.*

1. **Learning deep generative models of graphs.** ICLR Workshop 2018. [paper](https://arxiv.org/abs/1803.03324)

    *Yujia Li, Oriol Vinyals, Chris Dyer, Razvan Pascanu, Peter Battaglia.*

1. **MolGAN: An implicit generative model for small molecular graphs.** 2018. [paper](https://arxiv.org/abs/1805.11973)

    *Nicola De Cao, Thomas Kipf.*

1. **GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models.** ICML 2018. [paper](https://arxiv.org/abs/1802.08773)

    *Jiaxuan You, Rex Ying, Xiang Ren, William L. Hamilton, Jure Leskovec.*

1. **NetGAN: Generating Graphs via Random Walks.** ICML 2018. [paper](https://arxiv.org/abs/1803.00816)

    *Aleksandar Bojchevski, Oleksandr Shchur, Daniel Zügner, Stephan Günnemann.*

1. **Graphite: Iterative Generative Modeling of Graphs.** ICML 2019. [paper](https://arxiv.org/pdf/1803.10459)

    *Aditya Grover, Aaron Zweig, Stefano Ermon.*

1. **Generative Code Modeling with Graphs.** ICLR 2019. [paper](https://openreview.net/pdf?id=Bke4KsA5FX)

    *Marc Brockschmidt, Miltiadis Allamanis, Alexander L. Gaunt, Oleksandr Polozov.*

1. **Efficient Graph Generation with Graph Recurrent Attention Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-2394)

	*Renjie Liao, Yujia Li, Yang Song, Shenlong Wang, Will Hamilton, David Duvenaud, Raquel Urtasun, Richard Zemel.*

1. **Graph Normalizing Flows.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-7511)

	*Jenny Liu, Aviral Kumar, Jimmy Ba, Jamie Kiros, Kevin Swersky.*

1. **Conditional Structure Generation through Graph Variational Generative Adversarial Nets.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-772)

	*Carl Yang, Peiye Zhuang, Wenhan Shi, Alan Luu, Pan Li.*

1. **GraphAF: a Flow-based Autoregressive Model for Molecular Graph Generation.** ICLR 2020. [paper](https://openreview.net/pdf?id=S1esMkHYPr)

	*Chence Shi, Minkai Xu, Zhaocheng Zhu, Weinan Zhang, Ming Zhang, Jian Tang.*



### [Combinatorial Optimization](#content)

1. **Combinatorial Optimization with Graph Convolutional Networks and Guided Tree Search.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7335-combinatorial-optimization-with-graph-convolutional-networks-and-guided-tree-search.pdf)

    *Zhuwen Li, Qifeng Chen, Vladlen Koltun.*


### [Inorganic-Materials](#content)

1. **A Unified Framework for Data Poisoning Attack to Graph-based Semi-supervised Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-5182)

	*Xuanqing Liu, Si Si, Jerry Zhu, Yang Li, Cho-Jui Hsieh.*


### [Organic-Materials](#content)


### [Chemistry](#content)


### [Graph Mining](#content)

1. **Attributed Graph Clustering: A Deep Attentional Embedding Approach.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.06532.pdf)

    *Chun Wang, Shirui Pan, Ruiqi Hu, Guodong Long, Jing Jiang, Chengqi Zhang.*
    


    
### [Circuit Design](#content)
1. **Contextual Graph Markov Model: A Deep and Generative Approach to Graph Processing.** ICML 2018. [paper](https://arxiv.org/pdf/1805.10636.pdf)

    *Davide Bacciu, Federico Errica, Alessio Micheli.*


1. **Motif-matching based Subgraph-level Attentional Convolution Network for Graph Classification.** AAAI 2020. [paper]()

	*Hao Peng, Jianxin Li,  Qiran Gong, Yuanxing Ning, Senzhang Wang, Lifang He.*

1. **A Fair Comparison of Graph Neural Networks for Graph Classification.** ICLR 2020. [paper](https://openreview.net/pdf?id=HygDF6NFPB)

	*Federico Errica, Marco Podda, Davide Bacciu, Alessio Micheli.*



### [Reinforcement Learning](#content)




1. **Learning Transferable Graph Exploration.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-1444)

	*Hanjun Dai, Yujia Li, Chenglong Wang, Rishabh Singh, Po-Sen Huang, Pushmeet Kohli.*


1. **Graph Convolutional Reinforcement Learning.** ICLR 2020. [paper](https://openreview.net/pdf?id=HkxdQkSYDB)

	*Jiechuan Jiang, Chen Dun, Tiejun Huang, Zongqing Lu.*

1. **Reinforcement Learning Based Graph-to-Sequence Model for Natural Question Generation.** ICLR 2020. [paper](https://openreview.net/pdf?id=HygnDhEtvr)

	*Yu Chen, Lingfei Wu, Mohammed J. Zaki.*

1. **Reinforced Genetic Algorithm Learning for Optimizing Computation Graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=rkxDoJBYPB)

	*Aditya Paliwal, Felix Gimeno, Vinod Nair, Yujia Li, Miles Lubin, Pushmeet Kohli, Oriol Vinyals.*



### [Traffic Network](#content)

1. **Spatiotemporal Multi‐Graph Convolution Network for Ride-hailing Demand Forecasting.** AAAI 2019. [paper](http://www-scf.usc.edu/~yaguang/papers/aaai19_multi_graph_convolution.pdf)

    *Xu Geng, Yaguang Li, Leye Wang, Lingyu Zhang, Qiang Yang, Jieping Ye, Yan Liu.*
    



### [Few-shot and Zero-shot Learning](#content)

1. **Few-Shot Learning with Graph Neural Networks.** ICLR 2018. [paper](https://arxiv.org/pdf/1711.04043.pdf)

    *Victor Garcia, Joan Bruna.* 




### [Program Synthesis](#content)

1. **Learning to Represent Programs with Graphs.** ICLR 2018. [paper](https://arxiv.org/abs/1711.00740)

    *Miltiadis Allamanis, Marc Brockschmidt, Mahmoud Khademi.*







### [Social Network](#content)


1. **Rumor Detection on Social Media with Bi-Directional Graph Convolutional Networks.** AAAI 2020. [paper](https://arxiv.org/abs/2001.06362)

	*Tian Bian, Xi Xiao, Tingyang Xu, Peilin Zhao, Wenbing Huang, Yu Rong, Junzhou Huang.*

### [Graph Matching](#content)

1. **Deep Graph Matching Consensus.** ICLR 2020. [paper](https://openreview.net/pdf?id=HyeJf1HKvS)

	*Matthias Fey, Jan E. Lenssen, Christopher Morris, Jonathan Masci, Nils M. Kriege.*


### [Computer Network Design](#content)

1. **Unveiling the potential of Graph Neural Networks for network modeling and optimization in SDN.** ACM SOSR 2019. [paper](https://arxiv.org/pdf/1901.08113.pdf)

    *Krzysztof Rusek, José Suárez-Varela, Albert Mestres, Pere Barlet-Ros, Albert Cabellos-Aparicio.*
    
    
### [SourceCode](#content)

1. ** https://github.com/nyu-dl/conditional-molecular-design-ssvae **

	*Seokho Kang, Kyunghyun Cho*
	
1. **Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation [link](https://github.com/bowenliu16/rl_graph_generation/tree/master/gym-molecule)**

1. **Generating Focussed Molecule Libraries for Drug Discovery with Recurrent Neural Networks**
	[link](https://github.com/jaechanglim/molecule-generator)
	
1. **https://github.com/molecularsets/moses**

1. **https://github.com/kevinid/molecule_generator**

1. **https://github.com/chennnnnyize/Generative-Molecules**

1. **https://github.com/jensengroup/mol_gen**

1. **https://github.com/insilicomedicine/BiAAE**

1. **Hierarchical Generation of Molecular Graphs using Structural Motifs**
	[link](https://github.com/wengong-jin/hgraph2graph)
	
    
### [Leaderboard](#content)


