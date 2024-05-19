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
* Best pratctices

### Metrics
* Classic n-gram metrics
* LLM-based metrics
* Reference-less metrics
* LLM as evaluators

### Manual Evaluation
* Is human evluation being abandoned?
* The alignment paradigm
* LLM-Human feedback loops

## Organizers
Leshem Choshen, Ariel Gera, Yotam Perlitz, Michal Shmueli-Scheuer and Gabriel Stanovsky
