# Multimodal-Transformer-for-Emotion-Recognition
Correspondence to mishra.pa@gmail.com

Prerequisites
  Python 3.6/3.7
  Pytorch (>=1.0.0) and torchvision
  CUDA 10.0 or above
Datasets 
Data files (containing processed IEMOCAP, MOSI and MOSEI datasets) can be downloaded from
http://immortal.multicomp.cs.cmu.edu/raw_datasets/processed_data/

Run the Code
  Create (empty) folders for data and pre-trained models:
  mkdir data pre_trained_models
  and put the downloaded data in 'data/'.

Command as follows
python main.py [--FLAGS]
Note that the default arguments are for unaligned version of IEMOCAP. For other datasets, please refer to Supplmentary.

Thanks to https://github.com/yaohungt/Multimodal-Transformer for the inspiration

Their paper on Multimodal Transformer is mentioned in the below link 
https://arxiv.org/pdf/1906.00295.pdf

@inproceedings{tsai2019MULT,
  title={Multimodal Transformer for Unaligned Multimodal Language Sequences},
  author={Tsai, Yao-Hung Hubert and Bai, Shaojie and Liang, Paul Pu and Kolter, J. Zico and Morency, Louis-Philippe and Salakhutdinov, Ruslan},
  booktitle={Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  month = {7},
  year={2019},
  address = {Florence, Italy},
  publisher = {Association for Computational Linguistics},
}
