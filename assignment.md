---
layout: page
title: Assignment
description: Description of early assignment.
nav_exclude: false
nav_order: 4
---

## CS324 Introduction Assignment

### Overview

In this assignment, you will gain familiarity with prompting a wide range of foundation models using a Google Colab Notebook. Specifically, you’ll work with large language models (LLMs) such as [BLOOM](https://huggingface.co/bigscience/bloom) and [BLOOMZ](https://huggingface.co/bigscience/bloomz) (BigScience). Language model prompting is the process of providing a model with an input text, and then having the model generate a response as output. For example, one could provide a language model with the prompt "The sky is" and the model might generate the response "blue". 

Prompts can be used to complete a breadth of tasks such as summarization (e.g., “Summarize the following paragraph: \<paragraph written out here\> Summary:”) or extraction (e.g., “Extract the phone number from the user bio: \<bio written out here\>.”)


The assignment is divided into three parts:


1. **Task selection**: In the first part of the assignment, you will select a task and evaluation dataset, which you will use in the remainder of the assignment.

2. **Prompt development**: In the second part of the assignment, you will explore how to develop effective prompts for LLMs. As part of this process, you may encounter both the joys and pains of prompting.  
  * On one hand, the right prompt and model can magically solve a seemingly complicated and unrelated task (w.r.t. the model's *training objective*.)  
  * On the other, prompting can be a brittle technique, and it may require time, effort, and creativity to develop a sufficient prompt.

3. **Model comparisons**: In the final part of the assignment, you will compare the performance (qualitatively and quantitatively) of several LLMs. Model comparisons will be along two dimensions:

  * Model Size
  * Training Techniques (e.g., vanilla autoregressive vs. instruction-tuned) 

### Submission Instructions

Complete the following sections. Download and submit this notebook (as an .ipynb file) to Canvas by 11:59PM on 1/24/23. 

Link to the Colab Notebook: [https://colab.research.google.com/drive/13gyUcsX7KtkwSJ1PfW8MrlXQePVD_jFP](https://colab.research.google.com/drive/13gyUcsX7KtkwSJ1PfW8MrlXQePVD_jFP)
