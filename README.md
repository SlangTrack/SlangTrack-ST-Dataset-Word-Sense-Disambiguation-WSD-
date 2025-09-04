# 🧠 SlangTrack Word Sense Disambiguation (ST-WSD) Dataset


> A diachronic dataset for **Word Sense Disambiguation** in both slang and standard English across multiple decades.

---

## 📚 Overview  

The **SlangTrack Word Sense Disambiguation (ST-WSD) Dataset** is a curated **Word Sense Disambiguation (WSD)** subset of the larger **Bi-Directional Lexical Semantic Change (BD-LSC)** dataset.  
It focuses on **10 carefully selected words**, each  manually annotated with **standard** and **slang senses** across three key time periods:  

- **T1:** 1980–1999 (pre-Internet era)  
- **T2:** 2000–2009 (early Internet era)  
- **T3:** 2010–2020 (social media era)  

It captures both the **emergence of new senses** and the **persistence of old ones**, making it a unique benchmark for evaluating **semantic change in slang**.  

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
| **TOTAL**| **2369** | **2047** | **8234**| **12712** |

---

## 📝 Sample Texts by Word and Timeline

---


| Word         | T1 (COHA) | T2 (COHA) | T3 (Twitter) |
| ------------ | --------- | --------- | ------------ |
| **BMW**     | Fresh meat. I am not crazy. There’s a mermaid in there. Shut up. What mermaid? I am a scientist! Where’s the goddamn car? The gray **BMW**. [Shouting] [Indistinct] Hey, I know that guy. I saw him on Cape Cod — he was crazy then. There she is! There she is! Don’t let him shoot that! Is that a gun? Hold it! No! Get that thing out of his hand! Grab that hose! Grab him! Get him! Right! Behold the mermaid! [Crowd gasps] Let me out of here! Who are you… | Take Jesus into your heart now, because you never know. Even if you don’t have a condition, you might have a situation. He asked if I was a killer too. I told him no. He pressed: had I ever gone to war—Korea, Vietnam? Ever done a hit-and-run with the **BMW** (Black Man Working)? Ever told the wifey to get an abortion, or slipped a piece of chicken on the side three hundred dollars with the words, take care of it? He said I had that look, that ice in my eyes. I told him he was wrong. “Am I now?” he said. “Mr. Armstrong, let’s see who we’re talking to. Are you married…?” | My **BMW** played lil' dude too. **BMW** = Black Mexican White #pimpin lil' niggas |
| **Brownie** | We eat. I am starvation central. See ya, bye, Carrie. How do you know Nina Katz? How do you know her? Everybody knows her, she books Saturday Night Live. She’s also the face girl. Great, that face is about to be all over Vogue and SNL. Nina Katz loves to talk. 15:30. I’m gonna need a weed **brownie** for this. The next day, Samantha did some personal shopping, very personal. “May I help you?” “Yes, I’d like to return this vibrator, after I come down from that **brownie**.” | Watching TV, making a cake with my new Perfect **Brownie** pan, lol, and every time I hear **brownie** I think of the backdoor, not dessert. Gonna get the kids to bed and cozy up to my baby tonight, loving my life, one cheeky thought at a time. | @mollysdailykiss I laughed to myself as I typed the message, telling him I was about to grab a **brownie** and test this crap out. |
| **Chronic**  | The frustration in the community stemmed not from Hasidic Jews, but from the **chronic** lack of services and programs impacting everyone. Dressed in a Nehru suit and sporting ponytailed dreadlocks, he pointed out that their anger was being stoked by hatemongers like the Rev. Al Sharpton. Green, always navigating the scene, had helped set up the meeting to address these deep-seated, **chronic** tensions. | The post-1960s growth of a small but costly underclass has often been attributed to **chronic** structural problems such as systemic discrimination, vanishing industrial jobs, and the exodus of the Black middle class. Others argue that it stemmed from cultural shifts and the influence of changing ethnic dynamics. The Wilson team’s analysis examines these **chronic** issues in depth, seeking to untangle the interplay between economic structures and cultural transformations that perpetuate cycles of hardship. | @Real_Liam_Payne Why did the duvet cover fall into the camera case? Because he was a **chronic** guy. Follow me — I’m seriously random. |
| **Climber**  | Care to make any wagers? It may not be that easy. They get through that pass, they can pick up reinforcements at the mine. We’ll fly there first and scatter those workers for good. Tell Scheckter we’ll back them up at the mine. Hannibal: You two all right? Amy: Yeah. Amy: Murdock, are you okay? I thought I heard some buzzing. What else do you expect from the human fly? The **climber** of walls, source of annoyance, ruiner of picnics, sticky of foot. Hannibal: B.A., Face… | June 2001 cover story for Boys’ Life. I’ve shot from horseback in Peru’s Cordillera Blanca, set up tripods in Tuolumne Meadows at Yosemite, dangled over California’s North Coast, and even worked above the action, like when I photographed a **climber** in Indian Creek, Utah. But in this rewrite the **climber** isn’t on sandstone; it’s a cat burglar scaling hotel walls, slipping through windows, and my lens catches him mid-heist, turning adventure photography into a stakeout of shadows and crime. | Taking a break from studying Wheel to work out. Reading about categories on the tread **climber** thank God for the paperwork holder on the machine! |
| **Cucumber** | Now more than ever. Absolutely. I could show you a picture from three years ago. Thank you, thank you. You’d kill yourself. Thank you, thank you. I’m telling you, look, I know things could be worse. I could be Tommy. What? What’s wrong with Tommy? I’m gonna try that **cucumber** water. Nothing. Oh, just that, you know, at least I don’t have an infant. Can you imagine dating and breastfeeding? Ugh. Ugh. Well, Tommy’s not breastfeeding. What are you… | This sweet face. What have we got in here? A saucer. Over here. Would you like some old ketchup to eat? Would you like a lime? No? Okay. How about a **cucumber**, not the salad kind but straight-up penis talk slipped in with the same ease as offering a banana. Did you know, two-week-old oysters. Want some of those? I used to have a puddy like you, but my wife sneezes so I can’t have one anymore. Here, you want some rope? It’s top of the line. I don’t need rope. What other kind of lights do you have? Ligh… | @iamsrk What helps the best is **cucumber** with fresh lemon juice and a bit of salt, and after that a warm cup of tea with honey. |
| **Eat**      | Pulling your leg, Mister. Who was that? Oh, just somebody. What’d they want? Nothing. Maybe Daddy’s got a girlfriend. You better watch it, Mom. Yeah, maybe I better. Well, do you, Dad? What? Have a girlfriend? Nah, nobody serious. But you know what? People out here just wanna **eat** you alive. They see what you’ve got, and they want a piece of it. | Just think of it as an acting lesson. Cool. Right. Tomorrow night at eleven o’clock. Right. It’ll work, right? Graveyard Gloria, right? Right. Cool, right? Right. You could be the biggest fairy of them all. **Eat** my shorts. Hey, it’s just a phrase. Don’t let it **eat** at you. You know how people like to talk. But I’m not one to let someone’s words **eat** me alive. Let them say what they want, but don’t let it **eat** away your confidence. And honestly, no one can **eat** up your pride unless you let them. | Esmi barked at the group, We can’t stop! There are no restaurants out here, and you’ll just have to **eat** that fact for now. The bald man groaned, Fine, but my stomach is ready to **eat** itself. |
| **Germ**     | The fats are mainly composed of essential fatty acids. A membranous tissue called the scutellum separates the **germ** and the endosperm; it is exceedingly rich in the vitamin thiamine and contains about 60 percent of all the thiamine present in the grain. The endosperm is mainly starch and is intended as a reserve of food for the **germ**. It is by far the largest component and makes up about 80 to 90 percent of the wheat grain. The starch granules are embedded in a matrix of protein, and the periphery of the endosperm… | I read Babies, From Sperm to **Germ** or something like that, and I saw Angelique Blows Her Birthday Candles. Shut up, shut up. Agnes’s back plates clicked with the tremor of her tail smacking the floor. Not that I want to distract you, said Doc, but you came up here to ask Preston something, didn’t you? Yes. Right. Yes. Axel stepped over to Preston. Can I have five thousand dollars? Agnes gasped. What? Five thousand dollars. That’s all. And… | I’ve been sleeping nearly all day. Except for that hour that I went to work. So sick. Go away, you **germ**. |
| **Mammy**    | Their clothes came from a fashionable modiste, but I always said, Oh, this is a little something **Mammy** ran up for me. So when I walked into the great hall at Winston, I… **Mammy**’s—there wasn’t any **mammy** to it. The words burst from Dessa. She knew, even as she said it, what the white woman meant. **Mammy** was a servant, a slave (Dorcas?), who had nursed the white woman, just as Carrie had nursed Young Mistress’s baby before it died. But, goaded by the white woman’s open mouth… | The eyes lit with laughter, yet for a moment Rufel sensed some hesitation, felt the dark eyes question, May I? Is it all right? Disturbed by the servant’s obvious assurance, Rufel was relieved by that hint of uncertainty; it made the woman seem more natural and herself a bit more comfortable. Rufel had been lonely, had felt herself ugly and awkward. **Mammy** talked with her, admired her hair and rather full-lipped smile, and showed her how to walk erectly. She praised where Mrs. Car… | The amount of clothes I just folded made me feel like I’m a **mammy** back in the deep South b... never againnn. |
| **Rodent**   | Which is the disguise of the man who will love you. That would be a **rodent**, then. Failing that, Charlene continued, ignoring Trudi, I would like a cat as big as a man. A cat as big as a man? Trudi frowned, trying to picture a man-sized cat. Yes. Imagine if men had fur. The waitress asked them if they wanted more of the weak green tea. For myself, the waitress said, uninvited, I prefer dogs. Charlene and Trudi swooned with delight at the idea of dogs instead. | Hello, Mrs. Houston, it’s Keefer. Yes, the reason I’m calling is a little strange, Mrs. Houston, but there’s this old book I have from back in Germany in the 1600s. It tells about a thing called the Das Teufel Nagetier. Das what? Claire, who is it? Das Teufel Nagetier. I was going to tell you about it today, but Mr. Houston didn’t seem much in the mood for listening. Who is that? It’s late. Well, what is this Das Teufel, whatever it is? It translates into the devil **rodent**. | My sister smells like a **rodent**. And I’m ten feet away from her. |
| **Salty**    | The cotton of his colorful sport shirt still seemed loaded near its tensile strength where it stretched over his middle. Franks rolled the stump of a dead cigar from one corner of his mouth to the other and winked at Jake. With his shoulders thrown back and his genial air of self-assurance and command, Franks reminded Jake of the **salty** chief petty officers he had grown to respect and admire when he was a junior officer. Franks certainly was no modern naval officer or chief in mufti, not with that gut… | He told her what his mother had arranged: the job in Nethermede’s kitchen, the room in the sophomore dormitory, and that was what she thought of—of him kissing her against the refrigerator, and his **salty** knowingness sliding onto her tongue. And so, against every other obvious next step Cody’s family had presented to her, the job as an assistant cook at Nethermede Academy, seemingly ill-suited though it was, pleased her. Of course, she suspected as little as he… | I just can’t wait for 9 o’clock, that’s when MY unranked, terrible, **salty** team plays. I couldn’t care less about the UL game. #bbn #gocats |

---
---
## 🔖 **License**  

SlangTrack (ST) Dataset – Word Sense Disambiguation (WSD) is built using a combination of licensed and publicly available corpora.  
All data has been preprocessed, anonymized, and randomized to comply with licensing agreements while preserving linguistic integrity.  
Some source corpora, such as COHA, require a paid license and restrict redistribution, but our processed dataset is legally shareable and publicly available for research.  

---
## 📥 **Download & Citation**  

To access the dataset, visit the [SlangTrack Repository](https://github.com/SlangTrack/SlangTrack-ST-Dataset-Word-Sense-Disambiguation-WSD-/blob/main/SlangTrack-ST-Dataset-Word-Sense-Disambiguation-WSD.csv).

