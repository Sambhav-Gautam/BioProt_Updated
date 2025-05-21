# BIOPROTX

**BIOPROTX** is a newly created dataset and evaluation framework for assessing the planning capabilities of Large Language Models (LLMs) in generating biological experiment protocols. This project is inspired by and builds upon the methods described in the paper [*BioPlanner: Automatic Evaluation of LLMs on Protocol Planning in Biology*](https://arxiv.org/abs/2310.10632). After thoroughly studying the paper, I have replicated its procedures and developed an updated dataset that follows a similar structure to the original **BIOPROT**.

## Overview

The original **BIOPROT** dataset was designed to address the challenges in evaluating LLMs for generating accurate and executable biological protocols. It consists of:
- **Biological Protocols:** Detailed descriptions of experimental procedures.
- **Pseudocode Representations:** Structured pseudocode corresponding to the natural language protocols.

The evaluation framework operates in two key stages:
1. **Teacher Phase:** A teacher LLM converts natural language protocols into structured pseudocode.
2. **Student Phase:** A student LLM reconstructs the pseudocode from a high-level description and a predefined list of admissible pseudocode functions.

This structured evaluation helps quantify the planning abilities of LLMs and assess their robustness in complex protocol generation tasks. The original study demonstrated the method using GPT-3 and GPT-4, including a successful laboratory execution of a novel protocol generated via pseudocode retrieval.

## About BIOPROTX

**BIOPROTX** follows the methodology outlined in the original paper with several enhancements:
- **Updated Data Collection:** New protocols have been curated to expand the diversity of biological experiments.
- **Refined Pseudocode Conversion:** Enhanced techniques for converting natural language protocols into pseudocode, ensuring higher fidelity to the original experimental designs.
- **Extended Function Set:** An expanded set of admissible pseudocode functions, accommodating more nuanced experimental steps and conditions.
- **Reproducibility:** All procedures from the paper have been replicated, with additional validation tests to ensure that the generated protocols are robust and executable.

## Credits & Acknowledgments

This project is heavily inspired by the research presented in the paper:
- **Title:** *BioPlanner: Automatic Evaluation of LLMs on Protocol Planning in Biology*  
- **Link:** [https://arxiv.org/abs/2310.10632](https://arxiv.org/abs/2310.10632)

I have read and followed the procedures outlined in the paper, and this project represents an effort to replicate and extend their approach through the creation of **BIOPROTX**. All due credit goes to the authors of the original work for their pioneering contributions.
