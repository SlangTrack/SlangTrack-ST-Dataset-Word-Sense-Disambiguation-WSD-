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
| **Mammy** | Their clothes came from a fashionable modiste, but I always said, ‘Oh, this is a little something Mammy ran up for me.’ So when I walked into the great hall at Winston, I… Mammy’s— There wasn’t any ‘mammy’ to it.” The words burst from Dessa. She knew, even as she said it, what the white woman meant. “Mammy” was a servant, a slave (Dorcas?), who had nursed the white woman, just as Carrie had nursed Young Mistress’s baby before it died. But, goaded by the white woman’s open mouth… | The eyes lit with laughter, yet for a moment Rufel sensed some hesitation, felt the dark eyes question, May I? Is it all right? Disturbed by the servant’s obvious assurance, Rufel was relieved by that hint of uncertainty; it made the woman seem more natural and herself a bit more comfortable. Rufel had been lonely, had felt herself ugly and awkward. Mammy talked with her, admired her hair and rather full-lipped smile, and showed her how to walk erectly. She praised where Mrs. Car…| The amount of clothes I just folded made me feel like I'm a "mammy" back in the deep south b...never againnn. |
| **Chronic** | The frustration in the community stemmed not from Hasidic Jews, but from the chronic lack of services and programs impacting everyone. Dressed in a Nehru suit and sporting ponytailed dreadlocks, he pointed out that their anger was being stoked by hatemongers like the Rev. Al Sharpton. Green, always navigating the scene, had helped set up the meeting to address these deep-seated, chronic tensions.| The post-1960s growth of a small but costly underclass has often been attributed to chronic structural problems such as systemic discrimination, vanishing industrial jobs, and the exodus of the Black middle class. Others argue that it stemmed from cultural shifts and the influence of changing ethnic dynamics. The Wilson team’s analysis examines these chronic issues in depth, seeking to untangle the interplay between economic structures and cultural transformations that perpetuate cycles of hardship. | @Real_Liam_Payne Why did the duvet cover fall into the camera case? Because he was a chronic guy. Follow me — I’m seriously random.|
| **Eat** | Pulling your leg, Mister. — Who was that? — Oh, just somebody. — What’d they want? — Nothing. Maybe Daddy’s got a girlfriend. You better watch it, Mom. — Yeah, maybe I better. — Well, do you, Dad? — What? — Have a girlfriend? Nah, nobody serious. But you know what? People out here just wanna eat you alive. They see what you’ve got, and they want a piece of it. | Just think of it as an acting lesson. — Cool. Right. — Tomorrow night at eleven o’clock. — Right. — It’ll work, right? Graveyard Gloria, right? — Right. — Cool, right? — Right. — You could be the biggest fairy of them all. — Eat my shorts. — Hey, it’s just a phrase. Don’t let it eat at you. You know how people like to talk. But I’m not one to let someone’s words eat me alive. Let them say what they want, but don’t let it eat away your confidence. And honestly, no one can eat up your pride unless you let them. | Esmi barked at the group, ‘We can’t stop! There are no restaurants out here, and you’ll just have to eat that fact for now.’ The bald man groaned, ‘Fine, but my stomach is ready to eat itself.|
| **BMW** | — | — | My BMW played lil' dude too ... BMW=black mexican white #pimpin lil' niggas |

| **Rodent** | — | — | My sister smells like a rodent. And I'm 10 feet away from her. |
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


