# RACE
The code and datasets for our EMNLP 2023 paper: EXPLAIN, EDIT, GENERATE: Rationale-Sensitive Counterfactual Data Augmentation for Multi-hop Fact Verification.


![](RACE.png)

# Datasets
All the datasets we used in experiments can be found [**Here**](https://drive.google.com/drive/folders/1EQ-LCthZAtEZXBWmuSM4-Z54aB2Nf-jh?usp=sharing), including the counterfactual data generated by _RACE_.
If you use the [**counterfactual datasets**](https://drive.google.com/drive/folders/1-VEVggJ2Nde9LTLz4leTePfEjIMEciYc?usp=sharing) we provide, please remember to cite our paper!
We will be uploading more counterfactual datasets generated by our _RACE_ later!

Note:
The samples provided with the keyword **"orig_qid"** in the counterfactual datasets are the counterfactual samples generated by RACE, where "orig_qid" denotes the "qid" of the original HoVer training sample corresponding to this counterfactual sample and the sample containing the following keywords is a counterfactual sample consisting of counterfactual evidence and original claim:
- predicted tokens: Words except "_" indicate token rationales from the original evidence extracted by CURE
- predicted tokens ids: Location of token rationales extracted by CURE in the original evidence
- sentence_rationales: Sentence rationales extracted by CURE
- entity_triggers: Corresponding to _T'_ in the paper
- constraints_2: Corresponding to the disjunctive constraints *CONS* in the paper

# Code
The code will be released soon.

# Citation
Please cite our paper if you use RACE or datasets we provided in your work:
```
@inproceedings{zhu-etal-2023-explain,
  title={{EXPLAIN}, {EDIT}, {GENERATE}: Rationale-Sensitive Counterfactual Data Augmentation for Multi-hop Fact Verification},
  author={Zhu, Yingjie and Si, Jiasheng and Zhao, Yibo and Zhu Haiyang and Zhou Deyu and He, Yulan},
  booktitle = "Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing",
  year = "2023",
  publisher = "Association for Computational Linguistics",
  url = "https://aclanthology.org/2023.emnlp-main.826",
  doi = "10.18653/v1/2023.emnlp-main.826",
  pages = "13377--13392",
}
```
