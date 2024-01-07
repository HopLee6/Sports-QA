# Sports-QA: A Large-Scale Video Question Answering Benchmark for Complex and Professional Sports

Haopeng Li, Andong Deng, Qiuhong Ke*, Jun Liu*, Hossein Rahmani, Yulan Guo, Bernt Schiele, Chen Chen

[Paper](https://arxiv.org/submit/5332853)

## Introduction

Reasoning over sports videos for question answering is an important task with numerous applications, such as player training and information retrieval. However, this task has not been explored due to the lack of relevant datasets and the challenging nature it presents. Most datasets for video question answering (VideoQA) focus mainly on general and coarse-grained understanding of daily-life videos, which is not applicable to sports scenarios requiring professional action understanding and fine-grained motion analysis. In this paper, we introduce the first dataset, named Sports-QA, specifically designed for the sports VideoQA task. The Sports-QA dataset includes various types of questions, such as descriptions, chronologies, causalities, and counterfactual conditions, covering multiple sports.

## Dataset Statistics

The numbers of QA pairs for different types and different sports.

|                | Descriptive  | Temporal  | Causal | Counterfactual | Total  |
|----------------|--------|--------|--------|----------|--------|
| Basketball     | 5,629  | 22     | 785    | 278      | 6,714  |
| Football       | 6,659  | 1,355  | 1,949  | 523      | 10,486 |
| Volleyball     | 6,120  | 360    | 1,942  | 685      | 9,107  |
| Gym            | 6,382  | 1,997  | 0      | 0        | 8,379  |
| Floor Exercise | 6,046  | 11,012 | 0      | 0        | 19,418 |
| Balance Beam   | 7,477  | 12,773 | 0      | 0        | 20,250 |
| Uneven Bars    | 7,294  | 12,124 | 0      | 0        | 17,058 |
| Vault          | 2,661  | 0      | 0      | 0        | 2,661  |
| Total          | 48,268 | 39,643 | 4,676  | 1,486    | 94,073 |


## Examples

![Examples from SportsQA](pics/sportsqa_eg.png)

<div align="center">
  Examples from SportsQA
</div>

## Download

*Coming soon!*

## Citation

```
@article{li2024sports,
  title={Sports-QA: A Large-Scale Video Question Answering Benchmark for Complex and Professional Sports},
  author={Li, Haopeng and Deng, Andong and Ke, Qiuhong and Liu, Jun and Rahmani, Hossein and Guo, Yulan and Schiele, Bernt and Chen, Chen},
  journal={arXiv preprint arXiv:2401.01505},
  year={2024}
}
```
