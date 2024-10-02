# Deep Learning for SimsReality Inc. 
This repository contains materials for employees at SimsReality Corporation to learn AI/ML technologies.
Deep Learning is regarded as a panacea in this era. 
In this course, you will learn the foundations of deep learning, understand how to interprete others' neural networks, and learn how to build your own neural networks.
You will also learn about popular neural network structures including convolutional neural networks, Recurrent NNs and transformers 
In addition, you will learn about Deep learning based Natural Language Processing techniques including word embeddings, BERT and GPT-like LLM(Large Language Model)s. 

## Course Information
- This course meets for in-class lecture.
- For all inquiries related to this course, please contact kyongha AT kisti DOT re DOT kr.
### Instructor
- Dr. Kyong-Ha Lee AT KISTI(Korea Institute of Science and Technology Information)

## Materials
- Book: <a href="https://link.springer.com/book/10.1007/978-3-319-94463-0">Neural networks and deep learning: a textbook</a> by Charu C. Aggarwal(but not mandatory)
- All slides for this class will be available here. 
- Some papers in a reading list will be reviewed if time is available.
- All course announcements take place though this page. Please check this webpage frequently.
### Class components and grading
- This course has the following components:
  - In-class lecture (60~70%)
  - Code reivew and excercise (30~40%)


## Syllabus
|Event|Date|In-class lecture|Materials and Exercises|
|---------|----|-------------|------------|
|Lecture 1|Aug. 28|<a href="https://github.com/bart7449/simsreality/blob/main/class1.pdf">Basic Concepts for understanding AI, ML</a>| | 
|Lecture 2|Aug. 29|<a href="https://github.com/bart7449/simsreality/blob/main/class2.pdf">An Introduction to neural networks I</a><ul><li>neural network<li>Training NN</ul>| | 
|Lecture 3|Sep. 11|<a href="https://github.com/bart7449/simsreality/blob/main/class3.pdf">An Introduction to neural networks II</a><ul><li>Regression <li>Classification|<a href="https://github.com/bart7449/simsreality/blob/main/Regression.ipynb">Prediction of housing price by using regression techniques</a><br><a href="https://github.com/bart7449/simsreality/blob/main/lab2.ipynb">Diabetes classification using NN</a> | 
|Lecture 4|Sep. 12|<a href="https://github.com/bart7449/simsreality/blob/main/class3.pdf">Convolutional Neural Network I</a> | |
|Lecture 5|Sep. 30|<a href="https://github.com/bart7449/simsreality/blob/main/class3.pdf">Convolutional Neural Network II</a>|<a href="https://github.com/bart7449/simsreality/blob/main/lab3.ipynb">Character Recognition with MNIST dataset</a><br><a href="https://github.com/bart7449/simsreality/blob/main/lab4.ipynb"> Detecting Pneumonia with X-ray images</a> |
|Lecture 6|Oct. 02|<a href="https://github.com/bart7449/simsreality/blob/main/class6.pdf">Recurrent Neural Network</a> |  |
|Lecture 7|Oct 07|<a href="https://github.com/bart7449/simsreality/blob/main/class7.pdf">RNN and Attention Mechanisms</a> |<a href="https://github.com/bart7449/simsreality/blob/main/lab5.ipynb"> RNN examples </a>| |
|Lecture 8|Oct. 10|<a href="https://github.com/bart7449/simsreality/blob/main/class8.pdf">Natural Language Processing with DL I</a> <ul><li>word vectors <li>attention mechanism <li>transformers</ul> |  |
|Lecture 9|Oct. 14|<a href="https://github.com/bart7449/simsreality/blob/main/class9.pdf">Natural Language Processing with DL II</a> <ul><li>BERT <li>GPT-like model</ul> |Building sLLM | |
|Lecture 10|Oct. 16|<a href="https://github.com/bart7449/simsreality/blob/main/class10.pdf">Advanced topics and applications</a> |  |








  
## Reading list for further discussion
### General Techniques
- [Ioffe15a] <a href="http://proceedings.mlr.press/v37/ioffe15.pdf"> Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift</a>, In Proceedings of ICLR 2015.
- (optional)[Ba2016a] <a href="https://arxiv.org/pdf/1607.06450.pdf?utm_source=sciontist.com">Layer Normalization</a>, arXiv:1607.06450v1, 2016.
- (optional)[Glorot10a]<a href="http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf">Understanding the difficulty of training deep feedforward neural networks</a>, In proceedings of AISTATS 2010.
- (optional)[He2015a] <a href="https://openaccess.thecvf.com/content_iccv_2015/papers/He_Delving_Deep_into_ICCV_2015_paper.pdf">Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification</a>, In Proceedings of ICCV 2015.
- [Hinton15a] <a href="https://arxiv.org/pdf/1503.02531.pdf">Distilling the Knowledge in a Neural Network</a>, arXiv:1503.02531v1, 2015.

### Convolutional Neural Network
- [Alex12a] <a href="https://kr.nvidia.com/content/tesla/pdf/machine-learning/imagenet-classification-with-deep-convolutional-nn.pdf">ImageNet Classification with Deep Convolutional Neural Networks </a>,  Advances in Neural Informaiton Processing Systems 25:1098-1105, 2012
- [He16a] <a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">Deep Residual Learning for Image Recognition</a>, In Proceedings of CVPR 2016.
- [He16b] <a href="https://arxiv.org/pdf/1603.05027.pdf">Identity mapping in deep residual networks</a>, In Proceedings of ECCV 2016.
- [Huang17a] <a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Densely_Connected_Convolutional_CVPR_2017_paper.pdf">Densely connected convolutional networks</a>, In Proceedings of CVPR 2017.
- [Hu2018]<a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Squeeze-and-Excitation_Networks_CVPR_2018_paper.pdf">Squeeze-and-excitation networks</a>, In Proceedings of CVPR 2018.
- [Kipf2017]<a href="https://arxiv.org/pdf/1609.02907.pdf">Semi-supervised classification with graph convolutional networks</a>, In Proceedings of ICLR 2017</a>

### Distributed Representations for words and graphs
- [Mikolov13a] <a href="https://arxiv.org/pdf/1310.4546.pdf">Distributed Representations of Words and Phrases and their Compositionality</a>, Advances in Neural Information Processing Systems 26 (2013): 3111-3119.
- [Rong2016a] <a href="https://arxiv.org/pdf/1411.2738.pdf&xid=25657,15700021,15700124,15700149,15700168,15700186,15700191,15700201,15700208&usg=ALkJrhhNCZKc2CO7hRoTrGd6aH2nBc-ZVQ">word2vec Parameter Learning Explained</a>, arXiv:1411.2738v4
- [Le14a]<a href="http://proceedings.mlr.press/v32/le14.pdf">Distributed Representations of Sentences and Documents</a>, In Proceedings of the ICML 2014.
- [Bojanowski17a] <a href="https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00051?source=post_page---------------------------">Enriching word vectors with subword information</a>, Transactions of the Association for Computational Linguistics 5 (2017): 135-146.
- [Grover16a] <a href="https://dl.acm.org/doi/pdf/10.1145/2939672.2939754">node2vec: Scalable Feature Learning for Networks</a>, In Proceedings of KDD 2016.

### Attention and Transformers
- [Badahnau16a] <a href="https://arxiv.org/pdf/1409.0473.pdf"> NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING TO ALIGN AND TRANSLATE</a>, In Proceedings of ICLR 2015
- [Vaswani17a] <a href="https://arxiv.org/pdf/1706.03762.pdf">Attention is All You Need<a>, In Proceedings of NeurIPS 2017  
- [Devlin19a] <a href="https://www.aclweb.org/anthology/N19-1423/">BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding</a>, In Proceedings of ACL 2019
