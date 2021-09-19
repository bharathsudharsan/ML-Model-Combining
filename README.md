# Combining Ubiquitous ML Models in IoT (Repo under construction)

## Table of Contents

## Algorithms used for Combining ML Models

## Devices and Datasets for Experiments 

Below are the Chosen heterogeneous devices on which distributed ML model training is performed then combined using 7 combining methods.

Below datasets are used for training on MCUs and CPUs.

1. [Banknote Authentication](https://archive.ics.uci.edu/ml/datasets/banknote+authentication) (5 features, 2 classes, 1372 samples) <br/>
2. [Haberman's Survival](https://archive.ics.uci.edu/ml/datasets/Haberman's+Survival) (3 features, 2 classes, 306 samples). <br/>
3. [Titanic](https://www.kaggle.com/c/titanic/data) (11 features, 2 classes,  1300 samples) <br/>

## Useful Books, Toolboxes and Datasets

### Books

1. [Ensemble Methods: Foundations and Algorithms](https://www.crcpress.com/Ensemble-Methods-Foundations-and-Algorithms/Zhou/p/book/9781439830031): Classical text book covering most of the ensemble learning techniques.
A **must-read** for people in the field

2. [Ensemble Machine Learning: Methods and Applications](https://link.springer.com/book/10.1007%2F978-1-4419-9326-7): Responding to a shortage of literature dedicated to the topic, this volume offers comprehensive coverage of state-of-the-art ensemble learning techniques,
including various contributions from researchers in leading industrial research labs.

3. [Applications of Supervised and Unsupervised Ensemble Methods](https://www.springer.com/gp/book/9783642039980): This book contains the extended papers presented at the 2nd Workshop on Supervised and Unsupervised Ensemble Methods and their Applications (SUEMA), in conjunction with ECAI.

4. [Data Mining and Knowledge Discovery Handbook](https://link.springer.com/chapter/10.1007/0-387-25465-X_45) Chapter 45 (Ensemble Methods for Classifiers): This chapter provides an overview of ensemble methods in classification tasks. We present all important types of ensemble method including boosting and bagging.
Combining methods and modeling issues such as ensemble diversity and ensemble size are discussed.

5. [Outlier Ensembles: An Introduction](https://www.springer.com/gp/book/9783319547640): Great intro book for ensemble learning in outlier analysis.

### Toolboxes

1. [combo](https://github.com/yzhao062/combo): combo is a comprehensive Python toolbox for combining machine learning (ML) models and scores for various tasks, including classification, clustering, and anomaly detection. It supports the combination of ML models from core libraries such as scikit-learn and xgboost.

2. [pycobra](https://github.com/bhargavvader/pycobra):  python library implementing ensemble methods for regression, classification and visualisation tools including Voronoi tesselations.

3. [DESlib](https://github.com/scikit-learn-contrib/DESlib):  A Python library for dynamic classifier and ensemble selection.

4. [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn):  A Python Package to Tackle the Curse of Imbalanced Datasets in Machine Learning.


### Datasets

As a subfield of machine learning, ensemble learning is usually tested against
general machine learning benchmark datasets. Some helpful links can be found below:

1. [List of datasets for machine-learning research - Wikipedia](https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research)
2. [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)
3. [PMLB: a large benchmark suite for machine learning evaluation and comparison](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5725843/): [Dataset Repository](https://github.com/EpistasisLab/penn-ml-benchmarks)

## Classic Papers

### Overview & Survey

1. Ensemble methods in machine learning @MCS. [PDF](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.34.4718&rep=rep1&type=pdf)
2. Popular ensemble methods: An empirical study @JAIR. [PDF](https://www.d.umn.edu/~rmaclin/publications/opitz-jair99.pdfP)
3. Ensemble learning: A survey @ Wiley Interdisciplinary Reviews. [PDF](https://onlinelibrary.wiley.com/doi/pdf/10.1002/widm.1249)

### Boosting

1. Xgboost: A scalable tree boosting system @ KDD. [PDF](https://dl.acm.org/ft_gateway.cfm?ftid=1775849&id=2939785)
2. Lightgbm: A highly efficient gradient boosting decision tree @ NIPS. [PDF](https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree.pdf)
3. CatBoost: unbiased boosting with categorical features @ NIPS. [PDF](https://papers.nips.cc/paper/7898-catboost-unbiased-boosting-with-categorical-features.pdf)

### Clustering Ensemble

1. Cluster Ensembles – A Knowledge Reuse Framework for Combining Multiple Partitions @ JMLR. [PDF](http://strehl.com/download/strehl-jmlr02.pdf)
2. Clusterer Ensemble @ KBS. [PDF](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/kbs06.pdf)
3. A survey of clustering ensemble algorithms @ IJPRAI. [PDF](https://pdfs.semanticscholar.org/0d1b/7d01fb2634b6160a96bbdd73f918ed3859cb.pdf)
4. Clustering ensemble method @ Cybernetics. [PDF](https://www.researchgate.net/publication/322520921_Clustering_ensemble_method)

### Outlier Ensemble

1. Outlier ensembles: position paper @ SIGKDD Explorations. [PDF](https://pdfs.semanticscholar.org/841e/ce7c3812bbf799c99c84c064bbcf77916ba9.pdf)
2. Ensembles for unsupervised outlier detection: challenges and research questions a position paper @ SIGKDD Explorations. [PDF](http://www.kdd.org/exploration_files/V15-01-02-Zimek.pdf)
3. Isolation forest @ ICDM. [PDF](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf)
4. Outlier detection with autoencoder ensembles @ SDM. [PDF](http://saketsathe.net/downloads/autoencode.pdf)
5. An Unsupervised Boosting Strategy for Outlier Detection Ensembles @ PAKDD. [PDF](https://link.springer.com/chapter/10.1007/978-3-319-93034-3_45)
6. LSCP: Locally selective combination in parallel outlier ensembles @ SDM. [PDF](https://epubs.siam.org/doi/pdf/10.1137/1.9781611975673.66)

### Ensemble Learning for Data Stream

1. A survey on ensemble learning for data stream classification @ ACM Computing Surveys. [PDF](https://www.researchgate.net/publication/315698712_A_Survey_on_Ensemble_Learning_for_Data_Stream_Classification)
2. Ensemble learning for data stream analysis: A survey @Information Fusion. [PDF](http://www.math.chalmers.se/Stat/Grundutb/GU/MSA220/S18/DataStream-Classification.pdf)

### Key Algorithms

1. Bagging predictors @Machine Learning. [PDF](https://link.springer.com/content/pdf/10.1007/BF00058655.pdf)
2. A decision-theoretic generalization of on-line learning and an application to boosting @JCSS. [PDF](https://pdfs.semanticscholar.org/5fb5/f7b545a5320f2a50b30af599a9d9a92a8216.pdf)
3. Bagging, Boosting @AAAI/IAAI. [PDF](http://www.cs.ecu.edu/~dingq/CSCI6905/readings/BaggingBoosting.pdf)
4. Stacked generalization @Neural Networks. [PDF](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.133.8090&rep=rep1&type=pdf)
5. Stacked regressions @Machine Learning. [PDF](https://link.springer.com/content/pdf/10.1007/BF00117832.pdf)

## Source and Ranking Portals

1. [CORE](http://portal.core.edu.au/conf-ranks/)
2. [ERA](http://www.conferenceranks.com/#)
3. [SJR](https://www.scimagojr.com/)

## Reputed Data Mining Conferences/Workshops/Journals

### Conferences and Workshops

1. [ACM International Conference on Knowledge Discovery and Data Mining (SIGKDD)](http://www.kdd.org/conferences)

2. [ACM International Conference on Management of Data (SIGMOD)](https://sigmod.org/)

3. [The Web Conference (WWW) ](https://www2018.thewebconf.org/)

4. [IEEE International Conference on Data Mining (ICDM)](http://icdm2018.org/)

5. [SIAM International Conference on Data Mining (SDM)](https://www.siam.org/Conferences/CM/Main/sdm19)

6. [IEEE International Conference on Data Engineering (ICDE)](https://icde2018.org/)

7. [ACM InternationalConference on Information and Knowledge Management (CIKM)](http://www.cikmconference.org/)

8. [ACM International Conference on Web Search and Data Mining (WSDM)](http://www.wsdm-conference.org/2018/)

9. [The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD)](http://www.ecmlpkdd2018.org/)

10. [The Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD)](http://pakdd2019.medmeeting.org)

### Journals

1. [ACM Transactions on Knowledge Discovery from Data (TKDD)](https://tkdd.acm.org/)

2. [IEEE Transactions on Knowledge and Data Engineering (TKDE)](https://www.computer.org/web/tkde)

3. [ACM SIGKDD Explorations Newsletter](http://www.kdd.org/explorations)

4. [Data Mining and Knowledge Discovery](https://link.springer.com/journal/10618)

5. [Knowledge and Information Systems (KAIS)](https://link.springer.com/journal/10115)


## Doing Good Research and Get it Published

[How to do good research, Get it published in SIGKDD and get it cited](http://www.cs.ucr.edu/~eamonn/Keogh_SIGKDD09_tutorial.pdf): A fantastic tutorial on by Prof. Eamonn Keogh (UC Riverside)

[Checklist for Revising a SIGKDD Data Mining Paper](https://web.cs.dal.ca/~eem/gradResources/KDD/Checklist%20for%20Revising%20a%20SIGKDD%20Data%20Mining%20Paper.pdf): A concise checklist by Prof. Eamonn Keogh (UC Riverside)

[How to Write and Publish Research Papers for the Premier Forums in Knowledge & Data Engineering](http://acsic.org/files/Writing16-Web.pdf): A tutorial on how to structure data mining papers by Prof. Xindong Wu (University of Louisiana at Lafayette)
