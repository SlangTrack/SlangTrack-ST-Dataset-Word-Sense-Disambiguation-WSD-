# 🧠 SlangTrack (ST) Dataset – Word Sense Disambiguation (WSD) Subset

> A diachronic dataset for **Word Sense Disambiguation** in both slang and standard English across multiple decades.

---

## 📚 Overview  

The **SlangTrack (ST)** dataset is a curated **Word Sense Disambiguation (WSD)** subset of the larger **Bi-Directional Lexical Semantic Change (BD-LSC)** dataset.  
It focuses on **10 carefully selected words**, each  manually annotated with **standard** and **slang senses** across three key time periods:  

- **T1:** 1980–1999 (pre-Internet era)  
- **T2:** 2000–2009 (early Internet era)  
- **T3:** 2010–2020 (social media era)  

ST captures both the **emergence of new senses** and the **persistence of old ones**, making it a unique benchmark for evaluating **semantic change in slang**.  

---

## 🔑 Key Features  

- **10 Target Words** annotated for all occurrences in their contexts.  
- **Three Timelines:** T1, T2, T3, covering 40 years of language evolution.  
- **12,712 total instances** across the dataset.  
- **Fine-grained sense annotation** with slang and standard senses.  
- **High annotation quality:** Inter-annotator agreement ranging from 76% to 89%.  

---

## 🌍 Significance of the Dataset  

- First **temporal WSD dataset** to include **slang senses** explicitly.  
- Enables benchmarking of **supervised, unsupervised, and LLM-based WSD models**.  
- Supports research in **lexical semantic change**, **slang evolution**, and **sociolinguistics**.  
- Provides empirical evidence of **language change influenced by digital culture**.  

---

## 🎯 Target Word Selection  

Words were selected based on:  
- Evidence of both **slang and standard senses**.  
- Coverage across **different semantic domains** (food, drugs, people, feelings, etc.).  
- Rich usage in corpora over multiple decades.  

**Target words:** *BMW, Brownie, Chronic, Climber, Cucumber, Eat, Germ, Mammy, Rodent, Salty*  

---

## 📂 Data Sources and Collection  

- **COHA (Corpus of Historical American English)** – for T1 and T2  
- **Twitter corpus (2010–2020)** – for T3  
- **Sense inventories** were built from:  
  - Oxford English Dictionary (standard senses)  
  - Urban Dictionary, Green’s Dictionary of Slang, Online Slang Dictionary (slang senses)  

---

## 📊 Data Statistics  

**Instance counts across timelines (Total = 12,712):**

| Word     |   T1 |   T2 |   T3 | TOTAL |
|----------|-----:|-----:|-----:|------:|
| BMW      |   91 |  141 |  865 |  1097 |
| Brownie  |   73 |   72 |  819 |   964 |
| Chronic  |  482 |  380 |  823 |  1685 |
| Climber  |   75 |   50 |  517 |   642 |
| Cucumber |   74 |   85 |  892 |  1051 |
| Eat      |  975 |  995 | 1000 |  2970 |
| Germ     |  112 |   70 |  650 |   832 |
| Mammy    |  172 |   22 |  876 |  1070 |
| Rodent   |  101 |   67 |  905 |  1073 |
| Salty    |  214 |  165 |  887 |  1266 |
| **TOTAL**| 2369 | 2047 | 8234 | 12712 |

---

## 📝 Sample Texts from the Dataset  

Here are **sample contexts** from each timeline for each target word (illustrative examples):  
## 📝 Sample Texts by Word and Timeline (Full Instances)

| Word | T1 (COHA) | T2 (COHA) | T3 (Twitter/Online) |
|------|-----------|-----------|----------------------|
| **Mammy** | “too -- the Winstons was related to royalty or maybe it was only just a knight . ... Master sold Jeete ...” | “their clothes came from a fashionable modiste , but I always said , Oh , this a little something Mammy ran up for me . ... white woman 's open-mouth ...” | “@ThePBG Calling her Nanny Watkins makes sense. But she's calling her Mammy Watkins. And it's the 80s. Um. no.” |
| **Mammy** | — | — | “The amount of clothes I just folded made me feel like I'm a "mammy" back in the deep south b...never againnn” |
| **Chronic** | “The post-1960s growth of a small but expensive underclass has often been attributed to chronic structural problems ... perpetuate cycles of hardship.” | “The frustration in the community stemmed not from Hasidic Jews but from the chronic lack of services and programs impacting everyone. ... chronic tensions.” | “@Real_Liam_Payne why did the duvet cover fall into the camera case?because he was a chronic guy.. Follow me I'm seeeriously random :)” |
| **Chronic** | “She worried her chronic shyness was going to get the better of her once again. ... Beauty crises had defined their friendship.” | “In this story, Park spoke on condition that her real name not be used. ... indicative of the chronic tension between the state's rigid control and the people's growing desire for financial freedom.” | “That chronic is the strongest weed around.” |
| **Eat** | “Just think of it as an acting lesson. ... Let them say what they want, but don't let it eat away your confidence. And honestly, no one can eat up your pride unless you let them.” | “Pulling your leg, Mister. ... The world’s hungry, and they’ll eat you whole if you’re not careful.” | — |
| **Eat** | “They also, as older collectors have ruefully discovered, eat into your savings quickly, ... "Fine, but my stomach is ready to eat itself” | — | — |
| **BMW** | — | — | “My BMW played lil' dude too ... BMW=black mexican white #pimpin lil' niggas” |
| **BMW** | — | — | “@stuchbery I have a feeling you're up there..... Don't say ish bout my BMW. It's just a front lol....” |
| **Rodent** | — | — | “Thank GOD someone gets what a dog is NOT :-) RT @semanticwill This is not a dog. This is lipstick on a rodent http://yfrog.com/3ic42j” |
| **Rodent** | — | — | “@dagray50 Outpatient you say? haha Oh and i didn't know that rodent intelligence has progressed as far as mad gaming skills. tut tut” |
| **Rodent** | — | — | “I really need a piece of gum. My mouth tastes like rodent death.” |
| **Rodent** | — | — | “Today I heard, for the first time, a short scientific talk given by a man dressed as a rodent...! An interesting experience” |
| **Rodent** | — | — | “You can't tell me what a horrible rodent problem you have and then expect me to eat your banana bread .... God!” |
| **Rodent** | — | — | “My sister smells like a rodent. And I'm 10 feet away from her.” |
| **Rodent** | — | — | “i feel like a certain rodent-loving girl doesn't want anything to do with me ... if that makes sense” |
| **Rodent** | — | — | “@lovely_taurus88 see how she do me I was just wanting to try it and she told me to scram like I was a rodent or something” |
| **Rodent** | — | — | “Where is my kia rodent @mjg007? Ain't heard from him in a minute.” |
| **Rodent** | — | — | “@alice_dewsbery ;-) Rodent woman to the rescue haha! No worries :D cant wait to see the babies tomorrowww” |
| **Rodent** | — | — | “"i'm not bright, big words confuse me, i have the attention span of a rodent, and wanda loves me anyway" fairly odd parents is too cute” |
| **Rodent** | — | — | “The rodent speaks! Yatsenyuk says russian equipment arrives in Ukraine. If Kiev continue bombing civilians,there will no doubt be a lot more” |
| **Germ** | — | — | “my mom is really starting to get on my fucken nerves being the germ freak she is.” |
| **Germ** | — | — | “I've been sleeping nearly all day. Except for that hour that I went to work. So sick. Go away you germ. üòî” |
| **Germ** | — | — | “In my first class of the day my professor called us all "little germ incubators". So that's how my day is going.” |
| **Germ** | — | — | “@CedarsSinai Keep a small hand sanitizer on you… Common germ spreaders: building door handles, ... Don’t be a germ—stay clean” |
| **Salty** | — | — | “@eg4sheezy face turned salty so fast when he seen @burnrubberrick in them 6s yesterday lmao he's a cool ass dude tho #realtalk” |
| **Salty** | — | — | “I just can't wait for 9 o'clock, that's when MY "unranked, terrible, salty" team plays. I couldn't care less about the UL game. #bbn #gocats” |


---

## 🔖 License  


---

## 📥 Download & Citation  


