## COMM
The PyTorch implementation of paper [From CLIP to DINO: Visual Encoders Shout in Multi-modal Large Language Models](https://arxiv.org/pdf/2310.08825.pdf)

## Overview
<div align=center>
<img src="https://github.com/YuchenLiu98/COMM/blob/main/images/overall.png" width="680px">
</div>

**COMM**, an MLLM designed to integrate the visual embeddings of **C**LIP and DIN**O**v2 with **M**ulti-level features **M**erging for enhancing the visual capabilities of multi-modal large language model.

## News
[10/16] We released **From CLIP to DINO: Visual Encoders Shout in Multi-modal Large Language Models**, which is designed to integrate CLIP and DINOv2 with multi-level features merging for enhancing visual capabilities of MLLMs. Checkout the [paper](2310.08825).
[10/18] We apologized that the paper and code are under the corporation's legal review. The code release will be delayed. Thanks for your patience!

## Performance
We evaluate the model's multi-modal capabilities on five major categories of multi-modal tasks: Referring Expression
Comprehension, Referring Expression Generation, Object Hallucination Benchmark, Visual Question Answering and Image Captioning.
Our COMM achieves SOTA performance on multiple VL tasks as follows.
<div align=center>
<img src="https://github.com/YuchenLiu98/COMM/blob/main/images/performance.png" width="740px">
</div>

## Examples
<div align=center>
<img src="https://github.com/YuchenLiu98/COMM/blob/main/images/spot.png" width="540px">
</div>
<br />
<div align=center>
<img src="https://github.com/YuchenLiu98/COMM/blob/main/images/rec_case.png" width="740px">
</div>
<br />
<div align=center>
<img src="https://github.com/YuchenLiu98/COMM/blob/main/images/reg_case.png" width="740px">
</div>
<br />
<div align=center>
<img src="https://github.com/YuchenLiu98/COMM/blob/main/images/object.png" width="740px">
</div>

## Citation
Please cite our paper if the code is helpful to your research.
```
@article{jiang2023from,
    author = {Jiang, Dongsheng and Liu, Yuchen and Liu, Songlin and Zhang, Xiaopeng and Li, Jin and Xiong, Hongkai and Tian, Qi},
    title = {From CLIP to DINO: Visual Encoders Shout in Multi-modal Large Language Models},
    journal={arXiv preprint arXiv:2310.08825},
    year = {2023}
}
```
## Acknowledgement
- [LLaVA](https://github.com/haotian-liu/LLaVA) and [Shikra](https://github.com/shikras/shikra): The codebase we built upon, which have the amazing multi-modal capabilities!
- [Vicuna](https://github.com/lm-sys/FastChat): The powerful LLM we used.
- [DINOv2](https://github.com/facebookresearch/dinov2): Our used vision encoder.
<br />
Thanks for their wonderful works.
