# Arabic Conditional Semantic Textual Similarity Dataset (AraCSTS)

This repository contains the Arabic Conditional Semantic Textual Similarity (C-STS) dataset introduced in our study.

The dataset files will be released upon acceptance of the associated paper.

The dataset was created by translating and adapting the **C-STS-Reannotated** dataset into Modern Standard Arabic (MSA). It is intended to support research on conditional semantic textual similarity in Arabic.

## Dataset Structure

The repository contains the train, development, and test splits used in our experiments:

Dataset Structure

The repository contains the train, development, and test splits used in our experiments:

```text
data/
├── train.csv
├── dev.csv
└── test.csv
```

The final dataset contains:

- 11,342 training examples
- 1,842 development examples
- 778 test examples

Each example contains:

- `sentence1`: the first Arabic sentence
- `sentence2`: the second Arabic sentence
- `condition`: the condition under which similarity is assessed
- `label`: the corresponding semantic similarity score

## Source Dataset

This dataset is a translated and adapted version of **C-STS-Reannotated**.

Source dataset:

https://huggingface.co/datasets/LivNLP/C-STS-Reannotated

Project page:

https://livnlp.github.io/CSTS-reannotation/

The C-STS-Reannotated resource is based on the original Conditional Semantic Textual Similarity benchmark and provides revised annotations for the task.

## License

The source C-STS-Reannotated dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

This Arabic translated and adapted version is also released under the CC BY 4.0 license.

Under this license, the dataset may be shared and adapted provided that appropriate attribution is given and modifications are indicated.

License information:

https://creativecommons.org/licenses/by/4.0/

## Citation

If you use this Arabic C-STS dataset, please cite our paper:

```bibtex
@article{arabic_csts_2026,
  title   = {Conditional Semantic Textual Similarity in Arabic: Dataset Construction and Evaluation of Fine-Tuned Transformers and LLMs},
  author  = {},
  journal = {},
  year    = {2026}
}
```

Please also cite the C-STS-Reannotated resource:

```bibtex
@inproceedings{zhang-etal-2025-annotating,
  title     = {Annotating Training Data for Conditional Semantic Textual Similarity Measurement using Large Language Models},
  author    = {Zhang, Gaifan and Zhou, Yi and Bollegala, Danushka},
  booktitle = {Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing},
  year      = {2025},
  publisher = {Association for Computational Linguistics}
}
```

## Data Availability

The files provided in the `data/` directory correspond to the train, development, and test splits used in the experiments reported in the accompanying paper.
