# 🧠 SlangTrack (ST) Dataset – Word Sense Disambiguation (WSD)

## 📚 Overview
- The SlangTrack (ST)– Word Sense Disambiguation (WSD) dataset is a manually annotated **subset** subset of the larger Bi-Directional Lexical Semantic Change (BD-LSC) dataset     specifically designed for evaluating **Word Sense Disambiguation (WSD)** in a temporal, slang-rich context.
- It provides instance-level annotations for 10 carefully chosen words that exhibit both standard and slang senses.
- Each occurrence of a target word is annotated with the most appropriate sense, enabling high-resolution WSD evaluation.
- The dataset captures how slang and standard word meanings shift over time across three distinct periods




It includes 10 carefully selected words, each with up to 8 senses, annotated across **three distinct time periods**:
- **T1:** 1980–1999  
- **T2:** 2000–2009  
- **T3:** 2010–2020

Each word instance is labelled with the exact sense it conveys in context, enabling high-resolution tracking of sense evolution across decades.

---
📦 Data Sources
Historical English: Corpus of Historical American English (COHA)
Contemporary English: Twitter corpus (2010–2020)
Sense Inventories:
Oxford English Dictionary (standard senses)
Urban Dictionary, Green’s Dictionary of Slang, Online Slang Dictionary (slang senses)

---
## 📝 Data Format

Each instance is annotated with:
- The **target word**
- The **assigned sense** from a custom-built sense inventory
- The **time period** (T1, T2, or T3)
- The **sentence context**

---
## 📊 Word Counts by Time Period

Below is the distribution of sentence instances per word across T1, T2, and T3, extracted from the dataset:

| word     |   T1 |   T2 |   T3 |  
|:---------|-----:|-----:|-----:|
| BMW      |   91 |  141 |  865 | 
| Brownie  |   73 |   72 |  819 |  
| Chronic  |  482 |  380 |  823 |   
| Climber  |   75 |   50 |  517 |   
| Cucumber |   74 |   85 |  892 |   
| Eat      |    0 |    0 |    0 |  
| Germ     |  112 |   70 |  650 |   
| Mammy    |  172 |   22 |  876 |    
| Rodent   |  101 |   67 |  905 |   
| Salty    |  214 |  165 |  887 |    

---

**Example — Word: "Eat"**

| Time Period | Sentence                                                                 | Assigned Sense                                 |
|-------------|--------------------------------------------------------------------------|------------------------------------------------|
| T3          | “He eats up every opportunity that comes his way.”                      | To seize/make the most of an opportunity (S5)  |
| T1          | “She made him eat all his vegetables before dessert.”                   | Consuming food (S1)                            |

---
## 📁 Access

The dataset is **available upon request** from the corresponding author of the original paper.  
