# SlangTrack-ST-Dataset-Word-Sense-Disambiguation-WSD-
# 🧠 SlangTrack (ST) Dataset – Word Sense Disambiguation (WSD) Subset

> A fine-grained, annotated subset for evaluating Word Sense Disambiguation on slang and standard usage over time.

## 📚 Overview

**SlangTrack (ST)** is a manually annotated **subset** of the larger BD-LSC dataset, specifically designed for evaluating **Word Sense Disambiguation (WSD)** in a temporal, slang-rich context.

It includes 10 carefully selected words, each with up to 8 senses, annotated across **three distinct time periods**:
- **T1:** 1980–1999  
- **T2:** 2000–2009  
- **T3:** 2010–2020

Each word instance is labelled with the exact sense it conveys in context, enabling high-resolution tracking of sense evolution across decades.

---

## 📝 Data Format

Each instance is annotated with:
- The **target word**
- The **assigned sense** from a custom-built sense inventory
- The **time period** (T1, T2, or T3)
- The **sentence context**

**Example — Word: "Eat"**

| Time Period | Sentence                                                                 | Assigned Sense                                 |
|-------------|--------------------------------------------------------------------------|------------------------------------------------|
| T3          | “He eats up every opportunity that comes his way.”                      | To seize/make the most of an opportunity (S5)  |
| T1          | “She made him eat all his vegetables before dessert.”                   | Consuming food (S1)                            |

---
