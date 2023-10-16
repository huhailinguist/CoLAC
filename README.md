# CoLAC: Corpus of Linguistic Acceptability for Chinese

## Details of CoLAC

We present [Corpus of Linguistic Acceptability in Chinese (CoLAC)](https://arxiv.org/abs/2305.14091), the first large-scale  acceptability dataset in a non-Indo-European language handcrafted by linguists to evaluate the grammatical proficiency of language models. Our dataset consists of 7,495 sentences collected from one syntax textbook, one linguistics handbook, and 68 linguistics journal articles, all verified by native speakers of Mandarin. 

Every example sentence has two labels:

1) **label0**: a single label from the linguist who proposed the example (Note that this label is not from a single linguist, as we collected examples from one syntax textbook, one handbook for Chinese syntax and about 70 journal articles authored by different theoretical syntacticians), which we call **linguist label**,

2) **label1**: a **crowd label**, mapped from the mean ratings from other native speakers of Mandarin Chinese. **This label is used in all our experiments.**

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/9a64b507-b7d3-4c9b-a45e-c1393d76e9bc)

Statistics of CoLAC:

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/a20e7550-cd10-490a-88ab-f32a9ad8124c)


## Baselines

We ran several baselines, using XLM-R, the Chinese RoBERTa, variants of InstructGPT, ChatGPT and mTk. Results are shown below.

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/4489c6bc-7eb6-4aa5-8d3d-3788fdf348cb)

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/f0da7d19-d1d2-4b10-b45c-d97e43e03d7a)


## Cross-lingual transfer learning

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/d9979197-b264-4b39-8023-65e85d409f54)

For details of the experiments, see our paper. 


## Citation

```
@misc{hu2023revisiting,
      title={Revisiting Acceptability Judgements}, 
      author={Hai Hu and Ziyin Zhang and Weifang Huang and Jackie Yan-Ki Lai and Aini Li and Yina Patterson and Jiahui Huang and Peng Zhang and Chien-Jer Charles Lin and Rui Wang},
      year={2023},
      eprint={2305.14091},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2305.14091}
}
```
