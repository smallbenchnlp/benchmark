# Small-Bench NLP: Benchmark for small single GPU trained models in Natural Language Processing

Small-Bench NLP, is a benchmark for small efficient neural language models trained on a single GPU. The benchmark comprises of eight NLP tasks on the publicly available [GLUE](https://arxiv.org/pdf/1804.07461.pdf) datasets and a leaderboard to track the progress of the community.

***Models and Code will be published very soon. Thanks for being patient with us.***


## Leaderboard
The overall average (AVG) is used to rank the performance of models over the GLUE tasks.

| Rank | Model | CoLA | SST | MRPC | STS | QQP | MNLI |	QNLI | RTE | AVG |
| ---- | ----- | ---- | --- | ---- | --- | --- | ---- | ---- | ---  | --- |
| 1	| [ELECTRA-DeBERTa](https://github.com/smallbenchnlp/ELECTRA-DeBERTa) |	**57.50** |	**90.40** |	88.22 |	86.74 |	**90.44** | **81.78** | **88.10** |	**69.09** |	**81.53** |
| 2	| ELECTRA |	56.8 | 88.30 | 87.40 | **86.80** | 88.30 | 78.90 | 87.90 | 68.50 | 80.36 |
| 3 | DeBERTa |	47.82 |	90.36 | **88.49** |	84.62 |	88.31 |	78.11 | 86.67 |	67.87 | 79.03 |
| 4 | RoBERTa |	44.72 | 89.45 |	85.30 | 84.02 | 89.84 |	79.51 | 87.39 |	66.42 | 78.33 |
| 5 | BERT | 45.00 | 90.14 | 86.27 | 84.46 | 88.59 | 79.58 | 87.22 | 65.70 | 78.37 |

### Contact us

Meanwhile, if you have any questions, you can reach out to us at smallbenchnlp@gmail.com.

### Citation
To read more about Small-Benclh NLP benchmark paper, click [here](https://arxiv.org/abs/2109.10847).

To cite our paper -
```bibtex
@misc{kanakarajan2021smallbench,
      title={Small-Bench NLP: Benchmark for small single GPU trained models in Natural Language Processing},
      author={Kamal Raj Kanakarajan and Bhuvana Kundumani and Malaikannan Sankarasubbu},
      year={2021},
      eprint={2109.10847},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
