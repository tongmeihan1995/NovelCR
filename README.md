## What is NovelCR?
NovelCR is a large-scale bilingual benchmark designed for long-span coreference resolution.

NovelCR features extensive annotations, including 148k mentions in NovelCR-en and 311k mentions in NovelCR-zh. 

Moreover, the dataset is notably rich in long-span coreference pairs, with **85%** of pairs in NovelCR-en and **83%** in NovelCR-zh spanning across three or more sentences. 

Experiments on NovelCR reveal a large gap between state-of-the-art baselines and human performance, highlighting that NovelCR remains an open issue.

### Support Language
English (en)

Chinese (zh)

## Download
NovelCR is now available on Hugging Face

Chinese NovelCR: [https://huggingface.co/datasets/shuaiwa16/novelCR/tree/main]

## Overview of NovelCR
### Example
![Alt text](sdfa)

### Comparison to existing benchmark
![Alt text](sdfa)


## Citation

If you find NovelCR useful in your research, please cite our work:

```bibtex
@inproceedings{tong-wang-2025-novelcr,
    title = "{N}ovel{CR}: A Large-Scale Bilingual Dataset Tailored for Long-Span Coreference Resolution",
    author = "Tong, MeiHan  and
      Wang, Shuai",
    editor = "Che, Wanxiang  and
      Nabende, Joyce  and
      Shutova, Ekaterina  and
      Pilehvar, Mohammad Taher",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2025",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-acl.268/",
    doi = "10.18653/v1/2025.findings-acl.268",
    pages = "5161--5173",
    ISBN = "979-8-89176-256-5",
    abstract = "Coreference resolution (CR) endeavors to match pronouns, noun phrases, etc. with their referent entities, acting as an important step for deep text understanding. Presently available CR datasets are either small in scale or restrict coreference resolution to a limited text span. In this paper, we present NovelCR, a large-scale bilingual benchmark designed for long-span coreference resolution. NovelCR features extensive annotations, including 148k mentions in NovelCR-en and 311k mentions in NovelCR-zh. Moreover, the dataset is notably rich in long-span coreference pairs, with 85{\%} of pairs in NovelCR-en and 83{\%} in NovelCR-zh spanning across three or more sentences. Experiments on NovelCR reveal a large gap between state-of-the-art baselines and human performance, highlighting that NovelCR remains an open issue."
}
