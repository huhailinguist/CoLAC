# CoLAC: Corpus of Linguistic Acceptability for Chinese

## Detail sof CoLAC

We present Corpus of Linguistic Acceptability in Chinese (CoLAC), the first large-scale  acceptability dataset in a non-Indo-European language handcrafted by linguists to evaluate the grammatical proficiency of language models. Our dataset consists of 7,495 sentences collected from one syntax textbook, one linguistics handbook, and 68 linguistics journal articles, all verified by native speakers of Mandarin. 

Every example sentence has two labels:

1) **label0**: a single label from the linguist who proposed the example (Note that this label is not from a single linguist, as we collected examples from one syntax textbook, one handbook for Chinese syntax and about 70 journal articles authored by different theoretical syntacticians), which we call **linguist label**,

2) **label1**: a **crowd label**, mapped from the mean ratings from other native speakers of Mandarin Chinese. **This label is used in all our experiments.**

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/42b52008-d677-443e-870f-c1c8ea9904f2)

Statistics of CoLAC:

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/008cfe43-8405-477b-af55-6a385b1fb503)

## Baselines

We ran several baselines, using XLM-R, the Chinese RoBERTa, variants of InstructGPT, ChatGPT and mTk. Results are shown below.

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/a95c6b0b-8d20-43e7-b85e-d704d76bb86f)

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/24827ef1-cb48-42b0-a338-0c24b25b8d64)

## Cross-lingual transfer learning

![image](https://github.com/huhailinguist/CoLAC/assets/29844482/472bdf6c-96a5-4520-8b2f-40c89c90c8d7)



## Citation

```
@misc{hu2023revisiting,
      title={Revisiting Acceptability Judgements}, 
      author={Hai Hu and Ziyin Zhang and Weifang Huang and Jackie Yan-Ki Lai and Aini Li and Yina Patterson and Jiahui Huang and Peng Zhang and Chien-Jer Charles Lin and Rui Wang},
      year={2023},
      eprint={2305.14091},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
