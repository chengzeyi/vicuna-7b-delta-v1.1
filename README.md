---
license: apache-2.0
inference: false
---

**NOTE: This "delta model" cannot be used directly.**  
Users have to apply it on top of the original LLaMA weights to get actual Vicuna weights.  
See https://github.com/lm-sys/FastChat#vicuna-weights for instructions.

<br>
<br>

# Vicuna Model Card

## Model details

**Model type:**
Vicuna is an open-source chatbot trained by fine-tuning LLaMA on user-shared conversations collected from ShareGPT.
It is an auto-regressive language model, based on the transformer architecture.

**Model date:**
Vicuna was trained between March 2023 and April 2023.

**Organizations developing the model:**
The Vicuna team with members from UC Berkeley, CMU, Stanford, and UC San Diego.

**Paper or resources for more information:**
https://vicuna.lmsys.org/

**License:**
Apache License 2.0

**Where to send questions or comments about the model:**
https://github.com/lm-sys/FastChat/issues

## Intended use
**Primary intended uses:**
The primary use of Vicuna is research on large language models and chatbots.

**Primary intended users:**
The primary intended users of the model are researchers and hobbyists in natural language processing, machine learning, and artificial intelligence.

## Training dataset
70K conversations collected from ShareGPT.com.

## Evaluation dataset
A preliminary evaluation of the model quality is conducted by creating a set of 80 diverse questions and utilizing GPT-4 to judge the model outputs. See https://vicuna.lmsys.org/ for more details.
