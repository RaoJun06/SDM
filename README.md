# SDM: Sequential Deep Matching Model for Online Large-scale Recommender System
Code (Python2.7, TF1.4) of the sequential deep matching (SDM) model for recommender system at Taobao.
Current version only contains the core code of our model. The processes of data processing and evaluation are executed on our internal cloud platform [ODPS](https://www.alibabacloud.com/campaign/10-year-anniversary).

Here is the arxiv [link](https://arxiv.org/abs/1909.00385)

Citation:
```
@article{SDM2019,
  title={SDM: Sequential Deep Matching Model for Online Large-scale Recommender System},
  author={Lv, Fuyu and Jin, Taiwei and Yu, Changlong and Sun, Fei and Lin, Quan and Yang, Keping and Ng, Wilfred},
  journal={arXiv preprint arXiv:1909.00385},
  year={2019},
  url={https://arxiv.org/pdf/1909.00385.pdf}
}
```

## Datasets

**JD Dataset:** [raw data](https://drive.google.com/open?id=19PemKrhA8j-RZj0i20_j4ERcnzaxl5JZ), [train and test data](https://drive.google.com/open?id=1pam-_ojsKooRLVeOXEvbh3AwJ6S4IZ7B) in the paper (tfrecord).
The schema of raw data is shown in data/sample_data/.

**Taobao Dataset:** We will release the dataset after internal checking procedure if possible.


## Disclaimer
This is an implementation on experiment of offline JD dataset rather than the online official version.
There may be differences between results reported in the paper and the released one,
because the former one is achieved in distribution tensorflow on our internal deep learning platform [PAI](https://data.aliyun.com/product/learn).
