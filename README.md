# HuSST

This is the home repository for the Hungarian version of the Stanford Sentiment Treebank. This dataset is also part of the Hungarian Language Understanding Evaluation Benchmark Kit [HuLU](https://hulu.nytud.hu/). The corpus was created by translating and re-annotating the full sentences of the SST. 

## Data

The files are in the 'data' folder. The dataset contains 11 683 sentences. Each sentence is annotated for its sentiment on a three-point scale.

The train, validation and test sets contain 9 347, 1 168 and 1 168 sentences, respectively. The test set is distributed without the labels; to evaluate your model please contact us (ligeti-nagy.noemi@nytud.hu) or visit [HuLU's website](https://hulu.nytud.hu/) for an automatic evaluation (under construction). The metric of the evaluation is accuracy.

## Data format

The data files are in json format. The keys are the following:

`Sent_id`: unique id of the instances;

`Sent`: the sentence;

`Label`: the sentiment label of the sentence: "negative", "neutral" or "positive".

## Guidelines

The annotation guidelines (in Hungarian) are in the 'guidelines' folder. 

## License and usage


## Citation

If you use this resource or any part of its documentation, please refer to:

Noémi Ligeti-Nagy, Gergő Ferenczi, Enikő Héja, László János Laki, Noémi Vadász, Zijian Győző Yang, and Tamás Váradi. 2024. HuLU: Hungarian Language Understanding Benchmark Kit. In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), pages 8360–8371, Torino, Italia. ELRA and ICCL.

```
@inproceedings{ligeti-nagy-etal-2024-hulu-hungarian,
    title = "{H}u{LU}: {H}ungarian Language Understanding Benchmark Kit",
    author = "Ligeti-Nagy, No{\'e}mi  and
      Ferenczi, Gerg{\H{o}}  and
      H{\'e}ja, Enik{\H{o}}  and
      Laki, L{\'a}szl{\'o} J{\'a}nos  and
      Vad{\'a}sz, No{\'e}mi  and
      Yang, Zijian Gy{\H{o}}z{\H{o}}  and
      V{\'a}radi, Tam{\'a}s",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.733",
    pages = "8360--8371",
}
```
and to:

Ligeti-Nagy, N., Ferenczi, G., Héja, E., Jelencsik-Mátyus, K., Laki, L. J., Vadász, N., Yang, Z. Gy. and Váradi, T. (2022) HuLU: magyar nyelvű benchmark adatbázis kiépítése a neurális nyelvmodellek kiértékelése céljából [HuLU: Hungarian benchmark dataset to evaluate neural language models]. In: Berend, G., Gosztolya, G. and Vincze, V. (eds), XVIII. Magyar Számítógépes Nyelvészeti Konferencia. Szeged, Szegedi Tudományegyetem, Informatikai Intézet. 431–446.

```
@inproceedings{ligetinagy2022hulu,
  title={HuLU: magyar nyelvű benchmark adatbázis kiépítése a neurális nyelvmodellek kiértékelése céljából},
  author={Ligeti-Nagy, N. and Ferenczi, G. and Héja, E. and Jelencsik-Mátyus, K. and Laki, L. J. and Vadász, N. and Yang, Z. Gy. and Váradi, T.},
  booktitle={XVIII. Magyar Számítógépes Nyelvészeti Konferencia},
  year={2022},
  pages = {431--446},
  editors = {Berend, G. and Gosztolya, G. and Vincze, V.},
  address = {Szeged},
  publisher = {Szegedi Tudományegyetem, Informatikai Intézet}
}
```
and 

Richard Socher, Alex Perelygin, Jean Wu, Jason Chuang, Christopher Manning, Andrew Ng and Christopher Potts (2013), Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank. In: Proceedings of the 2013 Conference on Empirical Methods in Natural Language Processing. 1631--1642.
```
@inproceedings{socher-etal-2013-recursive,
    title = "Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank",
    author = "Socher, Richard  and
      Perelygin, Alex  and
      Wu, Jean  and
      Chuang, Jason  and
      Manning, Christopher D.  and
      Ng, Andrew  and
      Potts, Christopher",
    booktitle = "Proceedings of the 2013 Conference on Empirical Methods in Natural Language Processing",
    month = oct,
    year = "2013",
    address = "Seattle, Washington, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D13-1170",
    pages = "1631--1642",
}
