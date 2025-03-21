# Deep Learning Models for off-target predicitons in CRISPR-Cas9 gene editing
This repository includes a deep convolutional neural network for predicting the off-targets in CRISPR-Cas9 gene editing.

# CRISPOR dataset
The dataset to plot ROC curves in Figure 3 and 4 of our paper are collected from CRISPOR paper [2]. 

The descriptions of this dataset can be found in Fig. 2 of the CRISPOR paper: "For each scoring method, shown are the True positive rate (TPR)/False positive rate (FPR) when classifying 143 validated off-targets with a mismatch count of up to four, one of the PAMs NAG/NGA/NGG, and a minimum modification frequency of 0.1 %.". 

You can get this dataset from the github of CRISPOR paper (https://github.com/maximilianh/crisporPaper) through running the python script -- **"plotRoc.py"**.

# PREREQUISITE
The models for off-target predicitons were conducted by using Python 2.7.13 and TensorFLow v1.4.1. 
Following Python packages should be installed:
<ul>
<li><p>scipy</p></li>
<li><p>numpy</p></li>
<li><p>pandas</p></li>
<li><p>scikit-learn</p></li>
<li><p>TensorFlow</p></li>
</ul>

The Keras version of CNN were conducted by Python 3.6, TensorFlow 1.9.0, Keras 2.2.0.
Following Python packages should be installed:
<ul>
<li><p>scipy</p></li>
<li><p>numpy</p></li>
<li><p>pandas</p></li>
<li><p>Keras</p></li>
<li><p>TensorFlow</p></li>
</ul>

# REFERENCE

[1] Hui Peng, Yi Zheng, Zhixun Zhao, Tao Liu, Jinyan Li; Recognition of CRISPR/Cas9 off-target sites through ensemble learning of uneven mismatch distributions, Bioinformatics, Volume 34, Issue 17, 1 September 2018, Pages i757–i765, https://doi.org/10.1093/bioinformatics/bty558

[2] Haeussler, M., Schönig, K., Eckert, H. et al. Evaluation of off-target and on-target scoring algorithms and integration into the guide RNA selection tool CRISPOR. Genome Biol 17, 148 (2016). https://doi.org/10.1186/s13059-016-1012-2

# CONTAINS:
<ul>
<li><p>CFDScoring/cfd-score-calculator.py : Python script to run CFD score </p></li>
<li><p>predictions/cnn_std_prediction_TF.py : CNN_std conducted by TensorFlow</p></li>
<li><p>predictions/cnn_std_keras.py : CNN_std conducted by Keras used for off-target prediction </p></li>
</p></li>
</ul>

---------------------------------------

