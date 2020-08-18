**Noticeably**, the tools of data, util, vlfeat, affinity.m, evaluate.m and startup.m come from <a href="https://github.com/fcakir/mihash">here</a> and we highly **appreciate the authors' contributions**.

**The followings are our contributions:**

**MY_ONLINE_HASHING_METHOD** directory contains our online hashing methods including

(1) **HCOH.m**  ==> <a href="https://dl.acm.org/citation.cfm?id=3240519">Supervised Online Hashing via Hadamard Codebook Learning </a>, ACM MM 2018. 

(2) **BSODH.m**  ==> <a href ="https://arxiv.org/abs/1901.10185">Towards Optimal Discrete Online Hashing with Balanced Similarity </a>, AAAI 2019.

(3) **HMOH.m**  ==> <a href ="https://arxiv.org/abs/1905.04454">Hadamard Matrix Guided Online Hashing </a>, IJCV 2020 (Under Review).

**HMOH shows the best performance and is encouraged to compare.**

**Running Steps**:

First, run **./data/download_data.sh** to download the datasets of CIFAR10-VGG16-fc7, ImageNet-VGG, LabelMe-GIST and Places205_AlexNet_fc7_PCA128. Click <a href="链接:https://pan.baidu.com/s/15KCwxNfOqtNgFMqWyg0lsg">here</a> ( password: 2x0mS6g ) to download the MNIST dataset. Click <a href="https://pan.baidu.com/s/19aErUrC9F-K9NSrKQ5J8Qg">here</a> ( password: 4z8l ) to download the NUS-WIDE dataset.

Second, put all downloaded datasets into **./data** directory.

Third, run **startup.m**.

Fourth, run **our source codes**.
