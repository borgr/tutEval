<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Navigating the Modern Evaluation Landscape: Considerations in Benchmarks and Frameworks for Large Language Models](#navigating-the-modern-evaluation-landscape-considerations-in-benchmarks-and-frameworks-for-large-language-models)
  - [Outline](#outline)
    - [Introduction to LLM Benchmarking](#introduction-to-llm-benchmarking)
    - [Prompts](#prompts)
    - [Efficient Benchmark Design](#efficient-benchmark-design)
    - [Metrics](#metrics)
    - [Manual Evaluation](#manual-evaluation)
  - [Materials](#materials)
  - [Citing](#citing)
  - [Organizers](#organizers)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Navigating the Modern Evaluation Landscape: Considerations in Benchmarks and Frameworks for Large Language Models

General-Purpose language models have changed the world of natural language processing, if not the world itself. The evaluation of such versatile models, while supposedly similar to evaluation of text-generation models before them, in fact presents a host of new evaluation challenges and opportunities. This tutorial welcomes people from diverse backgrounds and assumes little familiarity with metrics, datasets, prompts and benchmarks. It will lay the foundations and explain the basics and their importance, while touching on the major points and breakthroughs of the recent era of evaluation. We will contrast new to old approaches, from evaluating on multi-task benchmarks rather than on dedicated datasets to efficiency constraints, and from testing stability and prompts on in-context learning to using the models themselves as evaluation metrics. Finally, we will present a host of open research questions in the field of robsut, efficient, and reliable evaluation.


## Outline

### Introduction to LLM Benchmarking
* What do we want evaluate?
* What are the main challenges? or, why it is not trivial?
* Common and important tasks
* Benchmarking paradigms - fine-tuning, zero shot learner, few shot leaner
* Popular LLM benchmarks

### Prompts
* Common practice: evaluation against a single prompt
* Current evaluations and findings are very brittle
* Mitigation approaches

### Efficient Benchmark Design
* Survey of compute requirements
* Common ways to reduce compute
* Best practices

### Metrics
* Classic n-gram metrics
* LLM-based metrics
* Reference-less metrics
* LLM as evaluators

### Manual Evaluation
* Important properties of human annotators
* Reproducibility issues
* Is human evaluation being abandoned?

## Materials
You can find all of the tutorial slides here: https://github.com/borgr/tutEval/blob/main/LREC24%20Evaluation%20Tutorial.pdf

## Citing

```
@inproceedings{choshen-etal-2024-navigating,
    title = "Navigating the Modern Evaluation Landscape: Considerations in Benchmarks and Frameworks for Large Language Models ({LLM}s)",
    author = "Choshen, Leshem  and
      Gera, Ariel  and
      Perlitz, Yotam  and
      Shmueli-Scheuer, Michal  and
      Stanovsky, Gabriel",
    editor = "Klinger, Roman  and
      Okazaki, Naozaki  and
      Calzolari, Nicoletta  and
      Kan, Min-Yen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024): Tutorial Summaries",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-tutorials.4",
    pages = "19--25",
    abstract = "General-Purpose Language Models have changed the world of Natural Language Processing, if not the world itself. The evaluation of such versatile models, while supposedly similar to evaluation of generation models before them, in fact presents a host of new evaluation challenges and opportunities. In this Tutorial, we will start from the building blocks of evaluation. The tutorial welcomes people from diverse backgrounds and assumes little familiarity with metrics, datasets, prompts and benchmarks. It will lay the foundations and explain the basics and their importance, while touching on the major points and breakthroughs of the recent era of evaluation. It will also compare traditional evaluation methods {--} which are still widely used {--} to newly developed methods. We will contrast new to old approaches, from evaluating on many-task benchmarks rather than on dedicated datasets to efficiency constraints, and from testing stability and prompts on in-context learning to using the models themselves as evaluation metrics. Finally, the tutorial will cover practical issues, ranging from reviewing widely-used benchmarks and prompt banks to efficient evaluation.",
}
```

## Organizers
Leshem Choshen, Ariel Gera, Yotam Perlitz, Michal Shmueli-Scheuer and Gabriel Stanovsky

