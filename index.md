![logo_tutorial](https://raw.githubusercontent.com/ssl-recsys/ssl-recsys.github.io/main/logo2_tutorial.png)
![uq_logo](https://raw.githubusercontent.com/ssl-recsys/ssl-recsys.github.io/main/uq_logo2.jpg)

<br>
Welcome! This is the page of our tutorial "<b>Self-Supervised Learning in Recommendation: Fundamentals and Advances</b>" at The Web Conference (WWW) 2022.

(Last update: 19/04/2022)

### Time
CET 14:00 - 15:30, 26/04/2022
<hr>

### Description

The neural architecture-based recommenders have demonstrated overwhelming advantages over their traditional counterparts. However, the highly sparse user behavior data often bottlenecks deep neural recommendation models to take full advantage of their capacity for better performance. Recently, self-supervised learning (SSL), which can enable training on massive unlabeled data with automatic data annotation, has received tremendous attention across multiple fields including recommender systems. It has turned out that SSL can significantly improve the recommendation quality by designing pretext tasks to discover supervisory signals from the raw data, serving as a natural antidote to the data sparsity issue. In this tutorial, we will systematically introduce the methodologies of applying SSL to recommendation. The topics to be covered include: (1) foundation and overview of self-supervised recommendation; (2) a comprehensive taxonomy of existing SSL-driven recommendation methods which is constructed based on the characteristics of pretext tasks; (3) how to apply SSL to various recommendation scenarios where different types of data and multiple optimization objectives are involved; (4) limitations in current research and future research directions; (5) an open-source toolkit to facilitate empirical comparisons and methodological development of self-supervised recommendation methods (released at https://github.com/Coder-Yu/SELFRec). 

<hr>

### Presenters

<b>Junliang Yu</b>  is a third-year Ph.D. student in the School of Information Technology and Electrical Engineering at the University of Queensland, jointly advised by A/Prof. Hongzhi Yin and Prof. Zi (Helen) Huang. He received his Bachelor and Master degrees from Chongqing University. His research interests include recommender systems, social media analytics, deep learning on graphs, and self-supervised learning. His recent research mainly focuses on efficient and explainable self-supervised learning for recommendation. He has 10+ publications on top-tier international venues such as KDD, WWW, ICDM, CIKM, AAAI, SIGIR, VLDBJ, and TKDE. He also served as the conference PC member of AAAI, CIKM, IJCAI, etc, and the journal reviewer for TOIS, TIST, TNNLS, TKDE, etc. 

<b>Hongzhi Yin</b> works as ARC Future Fellow and associate professor with The University of Queensland, Australia. He is leading the Responsible Big Data Intelligence Lab and was recognized as Field Leader of Data Mining & Analysis in The Australian’s Research 2020 magazine. His current main research interests include recommender system, graph embedding and mining, chatbots, social media analytics and mining, edge machine learning, trustworthy machine learning, decentralized and federated learning, and smart healthcare. He has published 180+ papers in the top conferences and journals, including 100+ CORE A* and 60+ CORE A, such as KDD (x15), IEEE TKDE (x14), SIGIR (x10), WSDM (x6), WWW (x6) and ACM TOIS (x11). He has won 6 Best Paper Awards such as ICDE’19 Best Paper Award, DASFAA’20 Best Student Paper Award, and ACM Computing Reviews’ 21st Annual Best of Computing Notable Books and Articles as well as one invited paper in the special issue of KAIS on the best papers of ICDM 2018. He is currently serving as Associate Editor for Springer Nature Computer Science, Editorial Board of Journal of Computer Science and Technology (JCST), Big Data Networks (specialty section of Frontiers in ICT, Frontiers in Digital Humanities, Frontiers in Big Data and Frontiers in Computer Science), Information, Guest Editors of ACM Transactions on Intelligent Systems and Technology, Information Systems, and World Wide Web. 

<b>Tong Chen</b> is a Lecturer with the Data Science Discipline at The University of Queensland. He received his PhD degree in Computer Science from The University of Queensland in 2020. Dr. Chen’s research interests include data mining, machine learning, business intelligence, recommender systems, and predictive analytics. He has 40+ publications on top-tier international venues such as KDD, SIGIR, ICDE, AAAI, IJCAI, ICDM, WWW, TKDE, IJCAI, TOIS, CIKM, as well as the prestigious health informatics journal JBHI. He has been actively providing professional services to over 20 worldleading international conferences/journals in the fields of data mining, information retrieval and AI. For example, his roles include program committee member of IJCAI’21 (SPC), WSDM’21, CIKM’21 and IJCAI’20, reviewer for TKDE, TOIS, TKDD and TNNLS, as well as session chair for conferences CIKM’21, VLDB’20, and DASFAA’20.

<hr>

### Outline

This is a 90-minute lecture-style tutorial that includes:
- <b>Introduction</b>  (10 mins)
  - Overview of Recommendation
  - History of SSL in Recommendation   
- <b>Taxonomy of Self-Supervised Recommendation Methods</b>  (15 mins)
  - Formulation of self-supervised recommendation
  - Taxonomy and training paradigms
- <b>Data Augmentation Techniques</b>  (10 mins)
- <b>SSL Methods for Recomendation</b>  (30 mins)
   - Contrastive mehthods
   - Predictive methods
   - Generative methods
   - Hybrid methods
- <b>Opensource Toolkit for Self-Supervised Recommendation</b> (5 mins)
- <b>Limitations and Future Research Trends</b> (10 mins)
- <b>Q&A</b> (10 mins)
<hr>

### Targeted Audience

 The tutorial targets at a broad range of audiences from recommendation and other related areas, including academic and industrial researchers, graduate students, and practitioners. After the tutorial, we expect the audience will have a grasp of basic SSL strategies for enhancing recommendation, and gain real-world practice experiences through working on the released opensource toolkit. As for the prerequisite, basic knowledge of information retrieval and recommendation is preferred, and the tutorial will also introduce the foundation for better audience engagement.

<hr>

### Our papers on self-supervised recommendation

+ [Are Graph Augmentations Necessary? Simple Graph Contrastive Learning for Recommendation](https://arxiv.org/abs/2112.08679).  <i><b>SIGIR'22</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/SimGCL.py) <br>
Junliang Yu, Hongzhi Yin, Xin Xia, Tong Chen, Lizhen Cui, Quoc Viet Hung Nguyen
+ [	On-Device Next-Item Recommendation with Self-Supervised Knowledge Distillation](https://arxiv.org/abs/2204.11091).  <i><b>SIGIR'22</b></i> [[code]]() <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Guandong Xu, Quoc Viet Hung Nguyen
+ [Self-Supervised Graph Co-Training for Session-based Recommendation](https://dl.acm.org/doi/abs/10.1145/3459637.3482388).  <i><b>CIKM'21</b></i> [[code]](https://github.com/xiaxin1998/COTREC) <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Yingxia Shao, Lizhen Cui
+ [Double-Scale Self-Supervised Hypergraph Learning for Group Recommendation](https://dl.acm.org/doi/10.1145/3459637.3482426).  <i><b>CIKM'21</b></i> [[code]](https://github.com/0411tony/HHGR) <br>
Junwei Zhang, Min Gao, Junliang Yu, Lei Guo, Jundong Li, Hongzhi Yin
+ [Socially-Aware Self-Supervised Tri-Training for Recommendation](https://dl.acm.org/doi/10.1145/3447548.3467340).  <i><b>KDD'21</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/SEPT.py) <br>
Junliang Yu, Hongzhi Yin, Min Gao, Xin Xia, Xiangliang Zhang, Nguyen Quoc Viet Hung
+ [Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation](https://dl.acm.org/doi/abs/10.1145/3442381.3449844).  <i><b>WWW'21</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/MHCN.py) <br>
Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang
+ [Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/16578).  <i><b>AAAI'21</b></i> [[code]](https://github.com/xiaxin1998/DHCN) <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Lizhen Cui, Xiangliang Zhang
