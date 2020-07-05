# Must-read papers on Deep Learning Graph Generation:&nbsp; models, algorithms and applications


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
    <td>&emsp;<a href="#VAE-Models">2.3 VAE: Variational Autoencoder models</a></td>
    <td>&ensp;<a href="#GAN-Models">2.4 GAN: generative adversarial networks</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Autoregressive-Models">2.5 Auto-regressive models</a></td>
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
    <td>&emsp;<a href="#Drug-Design">Drug design</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Media-Generation">Image/Video/Sound/Speech Synthesis </a></td>
    <td>&emsp;<a href="#Language-Synthesis">Natural language generation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#programs">Program synthesis</a></td>
    <td>&ensp;<a href="#computer-network"> Causal graph discovery</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#engineering">Engineering design: circuits/systems</a></td>
    <td>&ensp;<a href="#knowledgegraph">Knowledge Graph</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#Music-generation">Graph mining</a></td>
    <td>&ensp;<a href="#misc">Other applications</a></td>
</tr>
</table>

## [Survey papers](#content)

1. **Must read papers on graphical neural networks [link](https://github.com/thunlp/GNNPapers)**

1. **Deep learning for molecular design—a review of the state of the art." Molecular Systems Design & Engineering 4, no. 4 (2019): 828-849**

	Elton, Daniel C., Zois Boukouvalas, Mark D. Fuge, and Peter W. Chung. 
	
1. **"Graph Generators: State of the Art and Open Challenges." ACM Computing Surveys (CSUR) 53, no. 2 (2020): 1-30.**

	Bonifati, Angela, Irena Holubová, Arnau Prat-Pérez, and Sherif Sakr. 
	
1. **Advances and challenges in deep generative models for de novo molecule generation**
	Xue, Dongyu and Gong, Yukang and Yang, Zhaoyi and Chuai, Guohui and Qu, Sheng and Shen, Aizong and Yu, Jing and Liu, Qi

1. **Inverse molecular design using machine learning: Generative models for matter engineering." Science 361, no. 6400 (2018): 360-365.**

	Sanchez-Lengeling, Benjamin, and Alán Aspuru-Guzik.	
1. **Machine-enabled inverse design of inorganic solid materials: promises and challenges." Chemical Science 11, no. 19 (2020): 4871-4881.**

	Noh, Juhwan, Geun Ho Gu, Sungwon Kim, and Yousung Jung

<hr>

1. ** Awesome self-supervised learning [Link](https://github.com/jason718/awesome-self-supervised-learning)

1. **Graph Neural Networks: A Review of Methods and Applications.** arxiv 2018. [paper](https://arxiv.org/pdf/1812.08434.pdf)
   
    *Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun.* 

1. **A Comprehensive Survey on Graph Neural Networks.** arxiv 2019. [paper](https://arxiv.org/pdf/1901.00596.pdf)

    *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu.*
    

1. **Deep Learning on Graphs: A Survey.** arxiv 2018. [paper](https://arxiv.org/pdf/1812.04202.pdf)

    *Ziwei Zhang, Peng Cui, Wenwu Zhu.*
    
1. **Benchmarking Graph Neural Networks.** arxiv 2020. [paper](https://arxiv.org/pdf/2003.00982.pdf)

    *Dwivedi, Vijay Prakash and Joshi, Chaitanya K. and Laurent, Thomas and Bengio, Yoshua and Bresson, Xavier.*

1. **Foundations and modelling of dynamic networks using Dynamic Graph Neural Networks: A survey.** arxiv 2020. [paper](https://arxiv.org/abs/2005.07496)

    *Skarding, Joakim and Gabrys, Bogdan and Musial, Katarzyna.*


## [Models](#content)   

### [Basic Models](#content)
    
1. **Paper Name. Conference/Journal. Year***
  [[pdf]](link) 
  [[code]](link)
  
	*Author 1, Author 2, and Author 3* 
  

1. **Spectral Networks and Locally Connected Networks on Graphs.** ICLR 2014. [paper](https://arxiv.org/pdf/1312.6203.pdf)

    *Joan Bruna, Wojciech Zaremba, Arthur Szlam, Yann LeCun.*
    
1. **Deep Convolutional Networks on Graph-Structured Data.** arxiv 2015. [paper](https://arxiv.org/pdf/1506.05163.pdf)

    *Mikael Henaff, Joan Bruna, Yann LeCun.*
    
1. **Diffusion-Convolutional Neural Networks.** NIPS 2016. [paper](https://arxiv.org/pdf/1511.02136.pdf)

    *James Atwood, Don Towsley.*
        
1. **Learning Convolutional Neural Networks for Graphs.** ICML 2016. [paper](http://proceedings.mlr.press/v48/niepert16.pdf)

    *Mathias Niepert, Mohamed Ahmed, Konstantin Kutzkov.* 
    
    

<details><summary> more </summary> 


1. **Graph Capsule Convolutional Neural Networks.** ICML 2018 Workshop. [paper](https://arxiv.org/pdf/1805.08090.pdf)

    *Saurabh Verma, Zhi-Li Zhang.*
    
1. **Capsule Graph Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=Byl8BnRcYm)

    *Zhang Xinyi, Lihui Chen.*
    
1. **LanczosNet: Multi-Scale Deep Graph Convolutional Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=BkedznAqKQ)

    *Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard Zemel.*
    
1. **Position-aware Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1906.04817)

    *Jiaxuan You, Rex Ying, Jure Leskovec.*

1. **Disentangled Graph Convolutional Networks.** ICML 2019. [paper](http://proceedings.mlr.press/v97/ma19a/ma19a.pdf)

    *Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu.*

    
1. **Graph Learning-Convolutional Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.09971.pdf)

    *Bo Jiang, Ziyan Zhang, Doudou Lin, Jin Tang.*
    
    
1. **Topology Optimization based Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_to.pdf)

    *Liang Yang, Zesheng Kang, Xiaochun Cao, Di Jin, Bo Yang, Yuanfang Guo.*
    
    
1. **Masked Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_mask.pdf)

    *Liang Yang, Fan Wu, Yingkui Wang, Junhua Gu, Yuanfang Guo.*

    
1. **GeniePath: Graph Neural Networks with Adaptive Receptive Paths.** AAAI 2019. [paper](https://arxiv.org/pdf/1802.00910.pdf)

    *Ziqi Liu, Chaochao Chen, Longfei Li, Jun Zhou, Xiaolong Li, Le Song, Yuan Qi.*
    
    

1. **A Flexible Generative Framework for Graph-based Semi-supervised Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-1831)

	*Jiaqi Ma, Weijing Tang, Ji Zhu, Qiaozhu Mei.*

1. **Semi-Implicit Graph Variational Auto-Encoders.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-5716)

	*Arman Hasanzadeh, Ehsan Hajiramezanali, Krishna Narayanan, Nick Duffield, Mingyuan Zhou, Xiaoning Qian.*



1. **Graph Representation Learning via Ladder Gamma Variational Autoencoders.** AAAI 2020. [paper]()

	*Arindam Sarkar, Nikhil Mehta, Piyush Rai.*

1. **Effective Decoding in Graph Auto-Encoder using Triadic Closure.** AAAI 2020. [paper](https://arxiv.org/abs/1911.11322)

	*Han Shi, Haozheng Fan, James T. Kwok.*

1. **An Attention-based Graph Neural Network for Heterogeneous Structural Learning.** AAAI 2020. [paper](https://arxiv.org/abs/1912.10832)

	*Huiting Hong, Hantao Guo, Yucheng Lin, Xiaoqing Yang, Zang Li, Jieping Ye.*


1. **GraLSP: Graph Neural Networks with Local Structural Patterns.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07675)

	*Yilun Jin, Guojie Song, Chuan Shi.*

1. **Adaptive Structural Fingerprints for Graph Attention Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJxWx0NYPr)

	*Kai Zhang, Yaokang Zhu, Jun Wang, Jie Zhang.*

1. **Strategies for Pre-training Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=HJlWWJSFDH)

	*Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec.*

1. **Directional Message Passing for Molecular Graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=B1eWbxStPH)

	*Johannes Klicpera, Janek Groß, Stephan Günnemann.*

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
    
    
1. **Dynamic Hypergraph Neural Networks.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0366.pdf)

    *Jianwen Jiang, Yuxuan Wei, Yifan Feng, Jingxuan Cao, Yue Gao.*
    
    
1. **HyperGCN: A New Method For Training Graph Convolutional Networks on Hypergraphs.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-850)

	*Naganand Yadati, Madhav Nimishakavi, Prateek Yadav, Vikram Nitin, Anand Louis, Partha Talukdar.*

1. **Graph Transformer Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-6458)

	*Seongjun Yun, Minbyul Jeong, Raehyun Kim, Jaewoo Kang, Hyunwoo Kim.*


1. **EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs.** AAAI 2020. [paper](https://arxiv.org/abs/1902.10191)

	*Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler, Tao B. Schardl, Charles E. Leiserson.*

 

1. **Composition-based Multi-Relational Graph Convolutional Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=BylA_C4tPr)

	*Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Partha Talukdar.*

1. **Inductive representation learning on temporal graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=rJeW1yHYwH)

	*da Xu, chuanwei ruan, evren korpeoglu, sushant kumar, kannan achan.*

1. **Hyper-SAGNN: a self-attention based graph neural network for hypergraphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=ryeHuJBtPH)

	*Ruochi Zhang, Yuesong Zou, Jian Ma.*
	
### [VAE-models](#content)


### [GAN-models](#content)


### [Autoregressive Models](#content)

	




## [Applications](#content)

### [Physics](#content)

1. **MR-GNN: Multi-Resolution and Dual Graph Neural Network for Predicting Structured Entity Interactions.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.09558.pdf)

    *Nuo Xu, Pinghui Wang, Long Chen, Jing Tao, Junzhou Zhao.*

1. **A Generative Model For Electron Paths.** ICLR 2019. [paper](https://openreview.net/pdf?id=r1x4BnCqKX)

    *John Bradshaw, Matt J. Kusner, Brooks Paige, Marwin H. S. Segler, José Miguel Hernández-Lobato.*


1. **Interaction Networks for Learning about Objects, Relations and Physics.** NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

    *Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu.* 

1. **Graph networks as learnable physics engines for inference and control.** ICML 2018. [paper](https://arxiv.org/pdf/1806.01242.pdf)

    *Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel, Martin Riedmiller, Raia Hadsell, Peter Battaglia.* 

1. **Physics-aware Difference Graph Networks for Sparsely-Observed Dynamics.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1gelyrtwH)

	*Sungyong Seo, Chuizheng Meng, Yan Liu.*





### [Chemistry](#content) 

Molecule Design

1. **Graph Transformation Policy Network for Chemical Reaction Prediction.** KDD 2019. [paper](https://arxiv.org/pdf/1812.09441)

    *Kien Do, Truyen Tran, Svetha Venkatesh.*
    
1. **Spectral Multigraph Networks for Discovering and Fusing Relationships in Molecules.** NeurIPS Workshop 2018. [paper](https://arxiv.org/pdf/1811.09595.pdf)

    *Boris Knyazev, Xiao Lin, Mohamed R. Amer, Graham W. Taylor.*
    
1. **Learning Multimodal Graph-to-Graph Translation for Molecular Optimization.** ICLR 2019. [paper](https://openreview.net/pdf?id=B1xJAsA5F7)

    *Wengong Jin, Kevin Yang, Regina Barzilay, Tommi Jaakkola.*    
    
1. **Retrosynthesis Prediction with Conditional Graph Logic Network.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4761)

	*Hanjun Dai, Chengtao Li, Connor Coley, Bo Dai, Le Song.*    
    
1. **Multi-objective de novo drug design with conditional graph generative model. Journal of cheminformatics. 2018**
[pdf](https://link.springer.com/content/pdf/10.1186/s13321-018-0287-6.pdf)[code](https://github.com/kevinid/molecule_generator)<br>
        *Li, Y.; Zhang, L.; Liu, Z.*
2. **Designing natural product-like virtual libraries using deep molecule generative models. macromolecules. 2018** [pdf](https://www.researchgate.net/publication/326668536_Designing_natural_product-like_virtual_libraries_using_deep_molecule_generative_models)<br>
    *Li, Y.; Zhou, X.; Liu, Z.; Zhang, L.*
3. **Automatic chemical design using a data-driven continuous representation of molecules. ACS central science. 2018** [pdf](https://doi.org/10.1021/acscentsci.7b00572)<br>
    *Gómez-Bombarelli, R.; Wei, J.N.; Duvenaud, D.; Hernández-Lobato, J.M.; Sánchez-Lengeling, B.; Sheberla,D.; Aguilera-Iparraguirre, J.; Hirzel, T.D.; Adams, R.P.; Aspuru-Guzik, A.*
4. **Improving chemical autoencoder latent space and molecular de novo generation diversity with heteroencoders. Biomolecules. 2018** [pdf](https://arxiv.org/abs/1806.09300)<br>
    *Bjerrum, E.J.; Sattarov, B.*
5. **Generating focused molecule libraries for drug discovery with recurrent neural networks. ACS central science. 2018** [pdf](https://doi.org/10.1021/acscentsci.7b00512)<br>
    *Segler, M.H.; Kogej, T.; Tyrchan, C.; Waller, M.P.*
6. **Exploring Deep Recurrent Models With Reinforcement Learning for Molecule Design. ICLR Conference. 2018**
[pdf](https://openreview.net/pdf?id=HkcTe-bR-)<br>
    *Neil, Daniel and Segler, Marwin and Guasch, Laura and Ahmed, Mohamed and Plumbley, Dean and Sellwood, Matthew and Brown, Nathan*
7. **De novo molecule design by translating from reduced graphs to SMILES. Journal of chemical information and modeling. 2018**
 [pdf](https://pubs.acs.org/doi/pdfplus/10.1021/acs.jcim.8b00626?casa_token=2WeU6DX6WVcAAAAA:YqdC52Zy0YUNlsffg0OG1zsjYrG2Zn3t7a_JZZJXXO3QDSjNmeVqKl9F6RPISAnqI_L35XBYqelAq1w)<br>
    *Pogány, Peter and Arad, Navot and Genway, Sam and Pickett, Stephen D*
8. **Constrained graph variational autoencoders for molecule design. Advances in neural information processing systems. 2018**
  [pdf](https://papers.nips.cc/paper/8005-constrained-graph-variational-autoencoders-for-molecule-design.pdf)   [code](https://github.com/microsoft/constrained-graph-variational-autoencoder)<br>
   *Qi Liu, Miltiadis Allamanis, Marc Brockschmidt, Alexander L. Gaunt*
9. **Population-based de novo molecule generation, using grammatical evolution. Chemistry Letters. 2018**
    [pdf](https://arxiv.org/pdf/1804.02134.pdf)
    [code](https://github.com/tsudalab/ChemGE)<br>
        *Yoshikawa, N.; Terayama, K.; Sumita, M.; Homma, T.; Oono, K.; Tsuda, K.*
10. **Multi-resolution autoregressive graph-to-graph translation for molecules. arXiv preprint arXiv:1907.11223. 2019** [pdf](https://chemrxiv.org/articles/Multi-Resolution_Autoregressive_Graph-to-Graph_Translation_for_Molecules/8266745/1)<br>
    *Jin, W.; Barzilay, R.; Jaakkola, T.*
11. **Optimization of molecules via deep reinforcement learning. Scientific reports. 2019** [pdf](https://www.nature.com/articles/s41598-019-47148-x) [code](https://github.com/google-research/google-research/tree/master/mol_dqn)<br>
    *Zhou, Z.; Kearnes, S.; Li, L.; Zare, R.N.; Riley, P.* 
12. **Exploring the chemical space without bias: data-free molecule generation with DQN and SELFIES. Second Workshop on Machine Learning and the Physical Sciences (NeurIPS 2019). 2019** [pdf](https://ml4physicalsciences.github.io/files/NeurIPS_ML4PS_2019_153.pdf)<br>
         *Gaudin, T.; Nigam, A.; Aspuru-Guzik, A.*
13. **A model to search for synthesizable molecules. Advances in Neural Information Processing Systems. 2019**[pdf](http://papers.nips.cc/paper/9007-a-model-to-search-for-synthesizable-molecules.pdf)<br>
        *Bradshaw, J.; Paige, B.; Kusner, M.J.; Segler, M.; Hernández-Lobato, J.M.*
14. **Advances and challenges in deep generative models for de novo molecule generation. Wiley Interdisciplinary Reviews: Computational Molecular Science. 2019** [pdf](https://doi.org/10.1002/wcms.1395)<br>
    *Xue, D.; Gong, Y.; Yang, Z.; Chuai, G.; Qu, S.; Shen, A.; Yu, J.; Liu, Q.*
15. **A two-step graph convolutional decoder for molecule generation. arXiv preprint arXiv:1906.03412. 2019** [pdf](https://arxiv.org/abs/1906.03412)<br>
    *Bresson, X.; Laurent, T.*
16. **Reinforced molecule generation with heterogeneous states. 2019 IEEE International Conference on Data Mining (ICDM). IEEE. 2019**[pdf](https://ieeexplore.ieee.org/abstract/document/8970930)<br>
        *Shi, F.; You, S.; Xu, C.*
17. **Deep convolutional generative adversarial network (dcGAN) models for screening and design of small molecules targeting cannabinoid receptors. Molecular pharmaceutics. 2019** [pdf](https://pubs.acs.org/doi/abs/10.1021/acs.molpharmaceut.9b00500)<br>
    *Bian, Y.; Wang, J.; Jun, J.J.; Xie, X.Q.*
18. **Symmetry-adapted generation of 3d point sets for the targeted discovery of molecules. Advances in Neural Information Processing Systems. 2019**
 [pdf](https://papers.nips.cc/paper/8974-symmetry-adapted-generation-of-3d-point-sets-for-the-targeted-discovery-of-molecules.pdf)<br>
    *Gebauer, Niklas and Gastegger, Michael and Schütt, Kristof*
19. **Hierarchical Graph-to-Graph Translation for Molecules. ICLR 2020 Conference Blind Submission. 2019**
 [pdf](https://openreview.net/pdf?id=rJeeKTNKDB)  [code](https://github.com/wengong-jin/hgraph2graph)<br>
    *Wengong Jin, Regina Barzilay, Tommi Jaakkola*
20. **Conditional generation of molecules from disentangled representations. Under review as a conference paper at ICLR 2020. 2019**
    [pdf](https://openreview.net/pdf?id=BkxthxHYvr)<br>
        *Mollaysa, A.; Paige, B.; Kalousis, A.*
21. **DeepGraphMol, a multi-objective, computational strategy for generating molecules with desirable properties: a graph convolution and reinforcement learning approach. BioRxiv. 2020** [pdf](https://www.biorxiv.org/content/biorxiv/early/2020/06/10/2020.05.25.114165.full.pdf)<br>
	*Khemchandani, Y.; O’hagan, S.; Samanta, S.; Swainston, N.; Roberts, T.J.; Bollegala, D.; Kell, D.B.*
22. **The synthesizability of molecules proposed by generative models. Journal of Chemical Information and Modeling. 2020**[pdf](https://arxiv.org/pdf/2002.07007.pdf)<br>
        *Gao, W.; Coley, C.W.*
23. **Machine-Learning-Assisted De Novo Design of Organic Molecules and Polymers: Opportunities and Challenges. Polymers. 2020**. [pdf](https://www.mdpi.com/2073-4360/12/1/163)<br>
    *Chen, G.; Shen, Z.; Iyer, A.; Ghumman, U.F.; Tang, S.; Bi, J.; Chen, W.; Li, Y.*
24. **A deep generative model for fragment-based molecule generation. arXiv preprint arXiv:2002.12826. 2020**. [pdf](https://arxiv.org/abs/2002.12826)<br>
    *Podda, M.; Bacciu, D.; Micheli, A.*
25. **Chembo: Bayesian optimization of small organic molecules with synthesizable recommendations. International Conference on Artificial Intelligence and Statistics. 2020**
 [pdf](http://proceedings.mlr.press/v108/korovina20a/korovina20a.pdf)  [code](https://github.com/ks-korovina/chembo)<br>
    *Korovina, Ksenia and Xu, Sailun and Kandasamy, Kirthevasan and Neiswanger, Willie and Poczos, Barnabas and Schneider, Jeff and Xing, Eric*
26. **Towards Molecule Generation with Heterogeneous States via Reinforcement Learning. Master Thesis University of Sydney. 2020**
 [pdf](https://ses.library.usyd.edu.au/bitstream/handle/2123/22335/Shi_Thesis.pdf?sequence=4&isAllowed=y)<br>
    *Fangzhou Shi*
27. **Bidirectional molecule generation with recurrent neural networks. Journal of chemical information and modeling. 2020**
  [pdf](https://pubs.acs.org/doi/pdf/10.1021/acs.jcim.9b00943)[code](https://github.com/ETHmodlab/BIMODAL) <br> 
        *Francesca Grisoni, Michael Moret, Robin Lingwood, and Gisbert Schneider*
28. **Generative network complex for the automated generation of druglike molecules. arXiv preprint arXiv:2005.14286. 2020**
  [pdf](https://arxiv.org/pdf/2005.14286) <br> 
        *Kaifu Gao, Duc D Nguyen, Meihua Tu, Guo-Wei Wei*
29. **Bidirectional molecule generation with recurrent neural networks. Journal of chemical information and modeling. 2020**
    [pdf](https://www.researchgate.net/publication/338413002_Bidirectional_Molecule_Generation_with_Recurrent_Neural_Networks)<br>
        *Grisoni, F.; Moret, M.; Lingwood, R.; Schneider, G.*
30. **Generative network complex for the automated generation of druglike molecules. arXiv preprint arXiv:2005.14286. 2020**
    [pdf](https://arxiv.org/pdf/2005.14286.pdf)<br>
        *Gao, K.; Nguyen, D.D.; Tu, M.; Wei, G.W.*
31. **Identification of molecules by de novo molecule generation from NMR spectra. Proceedings of the Symposium on Chemoinformatics 42th Materials. 2020** [pdf](https://www.jstage.jst.go.jp/article/ciqs/2019/0/2019_1P09/_pdf)[code](https://github.com/john-bradshaw/electro)<br>
        *Zhang, J.; Terayama, K.; Sumita, M.; Ito, K.; Kikuchi, J.; Tsuda, K.*
32. **On failure modes of molecule generators and optimizers. ChemRxiv. 2020**
[pdf](https://chemrxiv.org/articles/On_Failure_Modes_of_Molecule_Generators_and_Optimizers/12213542/files/22461629.pdf)<br>
       *Renz, P.; Van Rompaey, D.; Wegner, J.K.; Hochreiter, S.; Klambauer, G.*
    
### [Biology](#content)





	
	
	
### [Organic-Materials](#content)





### [Inorganic-Materials](#content)


       
    


### [Drug Design](#content)


    

### [Knowledge Graph](#content)

  
1. **End-to-end Structure-Aware Convolutional Networks for Knowledge Base Completion.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.04441.pdf)

    *Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou.*






### [Other Applications](#content)

1. **Inductive Matrix Completion Based on Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=ByxxgCEYDS)

	*Muhan Zhang, Yixin Chen.*


### [Media-Generation](#content)

Images/Videos/Sounds/Speech


    
<details><summary>more</summary>

21. **Graph CNNs with Motif and Variable Temporal Block for Skeleton-based Action Recognition.** AAAI 2019. [paper](https://ecs.victoria.ac.nz/foswiki/pub/Groups/Graphics/RGB-DDataProcessingForRobotics/Graph%20CNNs%20with%20Motif%20and%20Variable%20Temporal%20Block%20for%20Skeleton-based%20Action%20Recognition.pdf)

    *Yu-Hui Wen, Lin Gao, Hongbo Fu, Fang-Lue Zhang, Shihong Xia.*
        
1. **Knowledge-Embedded Routing Network for Scene Graph Generation.** CVPR 2019. [paper](https://arxiv.org/pdf/1903.03326.pdf)

    *Tianshui Chen, Weihao Yu, Riquan Chen, Liang Lin.*
        
1. **ABC: A Big CAD Model Dataset For Geometric Deep Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1812.06216.pdf)

    *Sebastian Koch, Albert Matveev, Zhongshi Jiang, Francis Williams, Alexey Artemov, Evgeny Burnaev, Marc Alexa, Denis Zorin, Daniele Panozzo.*
         
    
1. **Graph Convolutional Gaussian Processes.** ICML 2019. [paper](https://arxiv.org/pdf/1905.05739)

    *Ian Walker, Ben Glocker.*

1. **GEOMetrics: Exploiting Geometric Structure for Graph-Encoded Objects.** ICML 2019. [paper](https://arxiv.org/pdf/1901.11461)

    *Edward J. Smith, Scott Fujimoto, Adriana Romero, David Meger.*

1. **Deep Generative Probabilistic Graph Neural Networks for Scene Graph Generation.** AAAI 2020. [paper](https://grlearning.github.io/papers/135.pdf)

	*Mahmoud Khademi, Oliver Schulte.*










</details>

### [Language-Synthesis](#content)

1. **A Graph-to-Sequence Model for AMR-to-Text Generation.** ACL 2018. [paper](https://arxiv.org/abs/1805.02473)

    *Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea.*
   
  
<details><summary>more</summary>


1. **PaperRobot: Incremental Draft Generation of Scientific Ideas.** ACL 2019. [paper](https://arxiv.org/pdf/1905.07870)

    *Qingyun Wang, Lifu Huang, Zhiying Jiang, Kevin Knight, Heng Ji, Mohit Bansal, Yi Luan.*


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
1. **https://github.com/yongqyu/MolGAN-pytorch**
	
1. **Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation [link](https://github.com/bowenliu16/rl_graph_generation/tree/master/gym-molecule)**

1. **Generating Focussed Molecule Libraries for Drug Discovery with Recurrent Neural Networks**
	[code](https://github.com/jaechanglim/molecule-generator)
1. **A Deep Generative Model for Fragment-Based Molecule Generation. 2020**
	[code](https://github.com/marcopodda/fragment-based-dgm)
1. **ORGAN:Objective Reinforced General Adversarial Network for de novo molecule generation. 2019**
	[code](https://github.com/haroon03/ORGAN-molecule)

1. **DrugAI** 
	[code](https://github.com/Gananath/DrugAI)
	- LSTM, GAN, WGAN models.SMILES

1. **https://github.com/molecularsets/moses**

1. **https://github.com/kevinid/molecule_generator**

1. **https://github.com/chennnnnyize/Generative-Molecules**

1. **https://github.com/jensengroup/mol_gen**

1. **https://github.com/insilicomedicine/BiAAE**

1. **Hierarchical Generation of Molecular Graphs using Structural Motifs**
	[link](https://github.com/wengong-jin/hgraph2graph)
	
    
### [Leaderboard](#content)


https://github.com/usccolumbia/benchmarking-gnns/blob/master/docs/07_leaderboards.md

### [Benchmark Datasets](#content)

https://github.com/usccolumbia/benchmarking-gnns


