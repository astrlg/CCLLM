# Conceptual Categories in Large Language Models (CCLLM)

## Overview

This repository provides code and data for analyzing how state-of-the-art large language models (LLMs) organize semantic categories. It evaluates whether LLMs reflect human-like patterns by assessing category properties predicted by Prototype Theory.

Abstract: 
The increasing ability of large language models (LLMs) to emulate human behavior has driven growing research into investigating their psychological properties. Categorization in particular is considered to be one of the most basic human cognitive processes. Investigating categorization in LLMs has implications for both theory and application: it highlights their potential as models of human cognition while raising important questions about bias, representational limits, and the role of non-textual information in shaping semantic categories. This work examines how state-of-the-art LLMs organize word categories, focusing on whether they exhibit human-like patterns predicted by Prototype Theory. %Drawing on machine psychology, cognitive modeling, and linguistic theory, we investigate whether prototypical effects emerge in models trained solely on textual data.% 
 To this end, we conduct experiments inspired by classic human categorization studies and complement them with feature-vector analyses for computational comparability. Our findings show that LLMs display clear prototypicality effects, including graded category membership, strong within-category similarity, and meaningful distinctions between categories. While these effects vary across models and domains, they consistently align more closely with Prototype Theory than with an alternative account of categorization. We can conclude that despite relying only on text, LLMs develop nuanced category structures resembling human semantic organization. More broadly, the study contributes to an expanding interdisciplinary effort to integrate methods from psychology and Natural Language Processing to better understand the behavior of LLMs.

## Contents

- `data/` - This folder contains all the data used in the experiments, including input datasets and any generated outputs.
- `notebooks/` - Jupyter notebooks for all data preprocessing, data collection and analysis, as well as models' performance evaluations. 
All Jupyter Notebooks are found in the "notebooks" folder and are numerically organized (with alphabetical subdivisions) as follows:
- 00 (a-b) - Preliminary Prompts Experiment
- 01 (a-c) - Part_A: Building LLM-specific Categories (Collecting Category Members)
- 02 (a-c) - Part_A: Building LLM-specific Categories (Collecting Category Features)
- 03 (a-f) - Part_B: Testing Prototypicality
Notebooks should be run sequentially, following first numerical and then alphabetical order.

## Installation

### Prerequisites

Make sure you have the following software installed:

- Python (version 3.10.8 was used for all analyses)
- Required Python libraries (can be installed via `requirements.txt`)


### Setup

Clone this repository and install required packages:

```bash
git clone https://github.com/astrlg/CCLLM.git
cd CCLLM
pip install -r requirements.txt

