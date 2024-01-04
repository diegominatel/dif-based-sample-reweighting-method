# DIF-SR: A Differential Item Functioning-Based Sample Reweighting Method

This repository is the official implementation of the paper entitled "DIF-SR: A Differential Item Functioning-Based Sample Reweighting Method".

## BibTeX Citation

```latex
@inproceedings{minatel2023dif,
  title={DIF-SR: A Differential Item Functioning-Based Sample Reweighting Method},
  author={Minatel, Diego and Parmezan, Antonio RS and C{\'u}ri, Mariana and de A. Lopes, Alneu},
  booktitle={Iberoamerican Congress on Pattern Recognition},
  pages={630--645},
  year={2023},
  organization={Springer}
}
```

## Abstract

In recent years, numerous machine learning-based systems have actively propagated discriminatory effects and harmed historically disadvantaged groups through their decision-making. This undesired behavior highlights the importance of research topics such as fairness in machine learning, whose primary goal is to include fairness notions into the training process to build fairer models. In parallel, Differential Item Functioning (DIF) is a mathematical tool often used to identify bias in test preparation for candidate selection; DIF detection assists in identifying test items that disproportionately favor or disadvantage candidates solely because they belong to a specific sociodemographic group. This paper argues that transposing DIF concepts into the machine learning domain can lead to promising approaches for developing fairer solutions. As such, we propose DIF-SR, the first DIF-based Sample Reweighting method for weighting samples so that the assigned values help build fairer classifiers. DIF-SR can be seen as a data preprocessor that imposes more importance on the most auspicious examples in achieving equity ideals. We experimentally evaluated our proposal against two baseline strategies by employing twelve datasets, five classification algorithms, four performance measures, one multicriteria measure, and one statistical significance test. Results indicate that the sample weight computed by DIF-SR can guide supervised machine learning methods to fit fairer models, simultaneously improving group fairness notions such as demographic parity, equal opportunity, and equalized odds.

## Full text of the paper

Access the full text of this paper at: https://link.springer.com/chapter/10.1007/978-3-031-49018-7_45
