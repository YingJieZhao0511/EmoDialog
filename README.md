# EmoDialog: A Large-Scale Dataset for Dynamic Emotion Description in Dialogue Speech

<p align="center">
  <a href="https://yingjiezhao0511.github.io/GDED/">
    <img src="https://img.shields.io/badge/🌐%20Demo-Online-blue" />
  </a>
  <img src="https://img.shields.io/badge/Language-English%20%7C%20Chinese-green" />
  <img src="https://img.shields.io/badge/Task-Speech%20Emotion%20Understanding-orange" />
  <img src="https://img.shields.io/badge/Status-Dataset%20Coming%20Soon-lightgrey" />
</p>


## 📢 Overview

Understanding emotions in human conversations requires more than recognizing isolated emotional states. In real-world dialogue, emotions dynamically evolve across multiple turns and are influenced by both **semantic context** and **paralinguistic expressions**, such as pitch, energy, and speaking rate.

However, existing emotion-related speech datasets mainly provide:

- discrete utterance-level emotion categories (e.g., MELD, IEMOCAP);
- coarse text-only dialogue summaries (e.g., SAMSum);
- single-utterance speech descriptions (e.g., Speechcraft).

Such supervision is insufficient for training Multimodal Large Language Models (MLLMs) to reason about **when, why, and how emotions change during conversations**.

To bridge this gap, we introduce:

# **GDED (Granular Dynamic Emotion Description)**

a large-scale bilingual multi-turn dialogue speech dataset that provides **fine-grained natural language descriptions of dynamic emotional evolution and paralinguistic attributes**.

GDED aims to enable a new generation of emotion-aware speech models that move beyond emotion classification toward **dynamic emotional understanding and reasoning**.


---

# 📊 Dataset Statistics

GDED contains:

| Statistic | Value |
|---|---:|
| Dialogues | **30,730** |
| Utterances | **405,081** |
| Speech Duration | **595 hours** |
| Languages | English & Chinese |
| Dialogue Type | Multi-turn conversation |


The dataset is constructed by aggregating and re-annotating three publicly available conversational speech datasets:

- **DailyTalk**
- **NCSSD**
- **MultiDialog**


After unified preprocessing and annotation, GDED provides rich multi-grained supervision for each dialogue.


---

# ✨ Dataset Highlights


## 1. Dynamic Emotional Evolution Description

Unlike traditional emotion datasets that only assign static emotion labels, GDED describes the **temporal evolution of emotions throughout a dialogue**.

Each dialogue contains:

- overall emotional atmosphere;
- emotional transition patterns;
- changes in emotional intensity;
- context-dependent emotional shifts.


Example:

> "The conversation begins with a relaxed atmosphere, gradually becomes more tense after a disagreement, and finally returns to a calmer state."


---

## 2. Fine-grained Speech Expression Description

GDED captures not only:

> **What is said**

but also:

> **How it is expressed**

including:

- pitch variation;
- energy changes;
- speaking rate;
- speaker attributes;
- emotional expression patterns.


---

## 3. Multi-grained Emotional Supervision

GDED provides complementary information at different levels:


| Level | Description |
|---|---|
| Dialogue-level | Dynamic emotional atmosphere and evolution |
| Utterance-level | Local emotion states |
| Acoustic-level | Speech expression characteristics |
| Semantic-level | Dialogue topics and content |


This enables research on both global emotional reasoning and fine-grained emotion recognition.



