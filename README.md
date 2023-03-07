# QA Datasets

This repo aims to facilitate NLP researchers to find relevant QA datasets.
Welcome to correct any mistakes, add new datasets, or provide any type of suggestions.

Note: Currently Visual QA, Conversational QA and Table QA are far from complete.

## Cloze-style

| Dataset (paper) | Domain | Source | \# QA pairs | \# Passages | Blanks | Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| TempLAMA ([Dhingra et al., 2022](https://arxiv.org/abs/2106.15110)) | Open | Wikidata | 50K | 50K | Entity | EN | Q:template; A: time-dependent
| SCDE ([Kong et al., 2020](https://aclanthology.org/2020.acl-main.502/)) | Exam | Lang Exams | 30K | 6k | Sentences | EN | Q: human created
| CLOTH ([Xie et al., 2018](https://aclanthology.org/D18-1257/)) | Exam | Lang Exams | 99K | 7K | Words | EN | Q: human created
| Quasar-S ([Dhingra et al., 2017](https://arxiv.org/abs/1707.03904)) | StackOverflow  | StackOverflow | 37K | 37K | Software entity | EN | 
| Story Cloze Test ([Mostafazadeh et al., 2017](https://aclanthology.org/W17-0906/)) | Story | Commonsense stories | 102K | 102K | Sentences | EN | based on ROCStories 
| LAMBADA ([Paperno et al., 2016](https://arxiv.org/abs/1606.06031)) | Novel | Books | 10K |10K | Words | EN | 
| ROCStories ([Mostafazadeh et al., 2016](https://aclanthology.org/N16-1098/)) | Story | Commonsense stories | 50K | 50K | Sentences | EN | Ending prediction
| People Daily & CFT ([Cui et al., 2016](https://aclanthology.org/C16-1167/)) | News | People Daily & Children’s Fairy Tale | 873K | 60K | Words | ZH | 
| BookTest ([Bajgar et al., 2016](https://arxiv.org/pdf/1610.00956.pdf)) | Book | Books | 14M | 14K | Words | EN |
| CNN & Daily Mail ([Hermann et al., 2015](https://proceedings.neurips.cc/paper/2015/hash/afdec7005cc9f14302cd0474fd0f3c96-Abstract.html)) | News | CNN & Daily Mail | 1.4M | 301K | Entity | EN |
| CBT ([Hill et al., 2015](https://arxiv.org/pdf/1511.02301.pdf)) | Book | Children’s books | 687K | 687K | Words | EN | 


## Multiple choice

| Dataset (paper) | Domain | Source | \# QA pairs | Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| CaseHOLD ([Zheng et al., 2021](https://arxiv.org/abs/2104.08671)) | Legal | Law | 53K | EN | 
| LogiQA ([Liu et al., 2020](https://arxiv.org/abs/2007.08124)) | Exam | Exams | 8.6K | EN | Logical reasoning
| PubMedQA ([Jin et al., 2021](https://aclanthology.org/D19-1259/)) | Biomedical | Research article | 211K | EN | A: yes/no & long answer
| PIQA ([Bisk et al., 2020](https://arxiv.org/abs/1911.11641)) | Physical commonsense | https://www.instructables.com | 21K | EN | Physical commonsense
| ReClor ([Yu et al., 2020](https://arxiv.org/abs/2002.04326)) | Exam | Exams | 6K | EN | Logical reasoning
| CosmosQA ([Huang et al., 2019](https://aclanthology.org/D19-1243/)) | Commonsense | Personal narratives | 36K | EN | 
| SocialIQa ([Sap et al., 2019](https://arxiv.org/pdf/1904.09728.pdf)) | Social & emotional | [ATOMIC](https://arxiv.org/pdf/1811.00146.pdf) | 38K | EN |
| BoolQ ([Clark et al., 2019](https://arxiv.org/abs/1905.10044)) | Wikipedia| Wikipedia | 16K | EN | Q: from NQ; A: yes/no
| QASC ([Khot et al., 2020](https://ojs.aaai.org//index.php/AAAI/article/view/6319)) | Science | Science facts | 10K | EN | Multi-hop
| CommonsenseQA ([Talmor et al., 2019](https://aclanthology.org/N19-1421/)) | Commonsense | Q: ConceptNet | 12K | EN | 
| WikiHop ([Welbl et al., 2018](https://aclanthology.org/Q18-1021/)) | Wikipedia| Wikipedia | 51K | EN | Multi-hop
| MedHop ([Welbl et al., 2018](https://aclanthology.org/Q18-1021/)) | Molecular biology | Research article | 2.5K | EN | Multi-hop
| SWAG ([Zellers et al., 2018](https://aclanthology.org/D18-1009/)) | Commonsense | Video Captions | 113K | EN | 
| OpenBookQA ([Mihaylow et al., 2018](https://arxiv.org/abs/1809.02789)) | Science | Science facts | 6K | EN | Multi-hop
| MultiRC ([Khashabi et al., 2018](https://aclanthology.org/N18-1023/)) | Multiple | Multiple | 6K | EN | Multi-sentence reasoning
| ARC ([Clark et al., 2018](https://arxiv.org/abs/1803.05457)) | Science | Science | 14M | EN |
| RACE ([Lai et al., 2017](https://aclanthology.org/D17-1082/)) | Exam | Exams | 98K | EN | 
| WikiQA ([Yang et al., 2015](https://aclanthology.org/D15-1237/)) | Open | Q: Bing query logs  | 3K | EN | 
| MCTest ([Richardson et al., 2013](https://aclanthology.org/D13-1020/)) | Story | Fictional stories  | 2K | EN | 
| COPA [Roemmele et al., 2011](https://people.ict.usc.edu/~gordon/copa.html)) | Commonsense | Q: Weblogs and library | 1K | EN |

## Span Extraction

| Dataset (paper) | Domain | Source | \# QA pairs | Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| MultiSpanQA ([Li et al., 2022](https://multi-span.github.io)) | Wikipedia | Wikipedia (NQ) | 6K | EN | Q: from NQ; A: multi-span 
| TimeQA ([Chen et al., 2021](https://arxiv.org/abs/2108.06314)) | Wikipedia | Q:Wikidata | 40K | EN | Temporal reasoning
| ConditionalQA ([Sun et al., 2021](https://aclanthology.org/2022.acl-long.253.pdf)) | Public Policy | Government website | 3.1K | EN | A: conditional
| QASPER ([Dasigi et al., 2021](https://aclanthology.org/2021.naacl-main.365.pdf)) | Scitific | NLP papers | 5K | EN | A: span & free from & bool; table reasoning
| NLQuAD ([Soleimani et al., 2021](https://aclanthology.org/2021.eacl-main.106/)) | News | BBC News | 31K | EN | Q: non-factoid; A: long (175 words)
| WikiHowQA ([Cui et al., 2021](https://arxiv.org/abs/2110.11692)) | Open | www.wikihow.com |247K | EN | Q: non-factoid; A: list 
| WebQA ([Cui et al., 2021](https://arxiv.org/abs/2110.11692)) | Open | Chinese QA websites | 40K | ZH | Q: non-factoid; A: list 
| 2WikiMultiHopQA ([Ho et al., 2020](https://aclanthology.org/2020.coling-main.580/)) | Wikipedia| Wikipedia | 193K | EN | Multi-hop; KB
| AmbigQA ([Min et al., 2020](https://aclanthology.org/2020.emnlp-main.466/)) | Wikipedia| Wikipedia (NQ) | 14K | EN | Q: ambigious 
| Quoref ([Dasigi et al., 2019](https://aclanthology.org/D19-1606/)) | Wikipedia | Wikipedia | 24K | EN | Resolve coreference
| NQ ([Kwiatkowski et al., 2019](https://ai.google.com/research/NaturalQuestions)) | Open | Wikipedia | 307K | EN | D: Long; A: long (192 words) & short
| DROP ([Dua et al., 2019](https://aclanthology.org/N19-1246/)) | Wikipedia | Wikipedia | 96K | EN | Discrete reasoning
| HotpotQA ([Yang et al., 2018](https://aclanthology.org/D18-1259/)) | Wikipedia | Wikipedia | 113K | EN | Multi-hop 
| DuoRC ([Saha et al., 2018](https://aclanthology.org/P18-1156/)) | Movie | Wikipedia & IMDB | 186K | EN | 
| SQuAD 2.0 ([Rajpurkar et al., 2018](https://aclanthology.org/P18-2124/)) | Open | Wikipedia | 151K | EN |
| TriviaQA ([Joshi et al., 2017](https://aclanthology.org/P17-1147/)) | Open | Q: Trivia quizzes | 96K | EN |
| NewsQA ([Trischler et al., 2017](https://aclanthology.org/W17-2623/)) | News | CNN articles | 120K | EN |
| SearchQA ([Dunn et al., 2017](https://arxiv.org/abs/1704.05179)) | Jeopardy! | Q: Jeopardy! | 140k | EN |
| SQuAD ([Rajpurkar et al., 2016](https://aclanthology.org/D16-1264/)) | Wikipedia | Wikipedia | 108K | EN |

## Free From

| Dataset (paper) | Domain | Source | \# QA pairs | Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| SituatedQA ([Zhang et al., 2021](https://arxiv.org/abs/2109.06157)) | Open | Multiple | 9K | EN | A:context-dependent
| JDProductQA ([Gao et al., 2019](https://arxiv.org/abs/1901.07696)) | Commercial | Product info | 470K | ZH | D: reviews & attributes
| ELI5 ([Fan et al., 2019](https://facebookresearch.github.io/ELI5/)) | Reddit | Reddit | 272K | EN | A:long (130 words)
| TweetQA ([Xiong et al, 2019](https://arxiv.org/pdf/1907.06292.pdf)) | Social media | Tweets | 14K | EN
| DuReader ([He et al., 2018](https://arxiv.org/pdf/1711.05073.pdf)) | Open | Baidu Zhidao | 200K | ZH
| NarrativeQA ([Koˇcisky ́ et al., 2018](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00023/43442/The-NarrativeQA-Reading-Comprehension-Challenge)) | Story | Book & movie | 47K | EN
| MS Marco ([Nguyen et al., 2016](https://ceur-ws.org/Vol-1773/CoCoNIPS_2016_paper9.pdf)) | Open | Q: Bing query logs | 100K | EN


## Knowledge-based QA

| Dataset (paper) | Domain | Source | \# QA pairs | Lang | KB | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |
| LC-QuAD 2.0 ([Dubey et al., 2019](http://lc-quad.sda.tech/)) | DBpedia & Wikidata | Q: templates | 30K | EN | Wikidata & DBpedia | Q: SPARQL
| ComplexWebQ ([Talmor and Berant, 2018](https://www.tau-nlp.sites.tau.ac.il/compwebq)) | Freebase | Q: WebQSP | 35K | EN | Freebase | Q: SPARQL
| QAngaroo ([Welbl et al., 2018](https://aclanthology.org/Q18-1021/)) | Open & Medical | Wikipedia & PubMed | 54K | EN | |
| MetaQA ([Zhang et al., 2018](https://arxiv.org/abs/1709.04071)) | Movie | Wikipedia (Movie) | 400K | EN | Self-construct | Multi-hop; text & audio data
| LC-QuAD ([Trivedi et al., 2017](https://github.com/AskNowQA/LC-QuAD)) | DBpedia & Wikidata | Q: templates | 5K | EN | DBpedia | Q:SPARQL
| WikiMovies ([Miller et al., 2016](https://arxiv.org/abs/1606.03126)) | Movie | Wikipedia (Movie) | 100K | EN | Self-construct | 
| WebQSP ([Yih et al., 2016](https://aclanthology.org/P16-2033/)) | Freebase | Q: WebQuestions | 4.7K | EN | Freebase | Q:SPARQL
| WebQuestions ([Berant et al., 2013](https://aclanthology.org/D13-1160/)) | Freebase | Q: Google suggest API | 5.8K | EN | Freebase | Q: SPARQL

## Visual QA 

| Dataset (paper) | Domain | Source | \# QA pairs | Lang | Anawer Type | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |
| WebQA ([Chang et al., 2021](https://arxiv.org/abs/2109.00590))
| DocVQA ([Mathew et al., 2021](https://arxiv.org/pdf/2007.00398.pdf))
| VCR ([Zellers et al., 2019](https://arxiv.org/abs/1811.10830))
| Social-IQ ([Zadeh et al., 2019](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zadeh_Social-IQ_A_Question_Answering_Benchmark_for_Artificial_Social_Intelligence_CVPR_2019_paper.pdf)) | Social | Social | 7.5K | EN | Multi-choice
| GQA ([Hudson and Manning, 2019](https://arxiv.org/abs/1902.09506))
| TallyQA ([Acharya et al., 2019](https://arxiv.org/abs/1810.12440))
| TextVQA ([Singh et al,. 2019](https://arxiv.org/abs/1904.08920))
| KVQA ([Shah et al., 2019](https://ojs.aaai.org/index.php/AAAI/article/view/4915))
| CRIC ([Gao et al., 2019](https://arxiv.org/pdf/1908.02962.pdf))
| RecipeQA ([Yagcioglu et al., 2018](https://aclanthology.org/D18-1166/))
| CLEVR ([Johnson et al., 2017](https://arxiv.org/abs/1612.06890))
| VQA2.0 ([Goyal et al., 2017](https://arxiv.org/abs/1612.00837))
| HowMany-QA ([Trott et al., 2017](https://arxiv.org/abs/1712.08697))
| FVQA ([Wang et al., 2017](https://arxiv.org/abs/1606.05433))
| Visual Genome ([Krishna et al., 2017](https://arxiv.org/abs/1602.07332))
| TDIUC ([Kafle and Kanan, 2017](https://arxiv.org/abs/1703.09684))
| Visual7W ([Zhu et al., 2016](https://arxiv.org/pdf/1511.03416.pdf))
| MovieQA ([Tapaswi et al., 2016](https://openaccess.thecvf.com/content_cvpr_2016/papers/Tapaswi_MovieQA_Understanding_Stories_CVPR_2016_paper.pdf)) | Movie | Movie | 21K | EN | Multi-choice 

## Conversational QA

| Dataset (paper) | Domain | Source | \# QA pairs | \# Dialogues | Lang | Answer Type | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| MuTual ([Cui et al., 2020](https://aclanthology.org/2020.acl-main.130/)) | Exam | Exam | 8.8K | 8.8K | EN | Multi-choice | A: ending 
| DREAM ([Sun et al., 2019](https://aclanthology.org/Q19-1014/)) | Exam | Exam | 10K | 6.4K | EN | Multi-choice | 
| ShARC ([Saeidi et al., 2018](http://aclanthology.lst.uni-saarland.de/D18-1233.pdf)) | Multiple | Rules | 32K | 948 | EN | Multi-choice | Mode: dialog tree
| CoQA ([Reddy et al., 2018](https://stanfordnlp.github.io/coqa/)) | Open | Multiple | 127K | 8.4K | EN | Free from |

## Table QA 

| Dataset (paper) | Domain | Source | \# QA pairs | \# Tables | Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |
| FinQA ([Chen et al., 2020](https://aclanthology.org/2021.emnlp-main.300/)) | Financial | Financial reports | 8.3K | 2.8K | EN | D: table & text
| HybridQA ([Chen et al., 2020](https://aclanthology.org/2020.findings-emnlp.91/)) | Wikipedia | Wikipedia | 70K | 13K | EN | D: table & text; Multi-hop
| WikiSQL ([Zhong et al., 2017](https://arxiv.org/abs/1709.00103)) | Wikipedia | Wikipedia | 81K | 2.4K | EN | Q:NL & SQL
| WikiTableQ ([Pasupat et al., 2015](https://aclanthology.org/P15-1142/)) | Wikipedia | Wikipedia  | 22K | 2K | EN | 

## Multilingual QA 
| Dataset (paper) | Domain | Source | \# QA pairs | \# Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| MKQA([Longpre et al., 2021](https://arxiv.org/abs/2007.15207)) | Open | NQ | 260K | 26 | No D; Q-A aligned across lang (human translate)
| XOR QA([Asai et al., 2020](https://arxiv.org/abs/2010.11856)) | Open | TydiQA | 40K | 7 | A: only cross-lang answers
| TydiQA ([Clark et al., 2020](https://arxiv.org/abs/2003.05002)) | Open | Wikipedia | 240K | 11 | Q,A: from original language
| XQuAD ([Artetxe et al., 2020](https://aclanthology.org/2020.acl-main.421/)) | Wikipedia | SQuAD | 13K | 11 | Q,A,D: aligned cross lang (human translate)
| MLQA ([Lewis et al., 2020](https://aclanthology.org/2020.acl-main.653/)) | Wikipedia | Wikipedia | 47K | 8 | Avg 4-way parallel (Q,A: human translate)
| XQA ([Liu et al., 2019](https://aclanthology.org/P19-1227/)) | Wikipedia | Wikipedia | 60K | 9 | training set: EN only

## Arabic QA
| Dataset (paper) | Domain | Source | \# QA pairs in AR | Passage | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| MKQA([Longpre et al., 2021](https://arxiv.org/abs/2007.15207)) | Open | NQ | 10K | No | Q-A aligned across lang (human translate)
| XOR QA([Asai et al., 2020](https://arxiv.org/abs/2010.11856)) | Open | TydiQA | 3K | Yes | A: only cross-lang answers
| TydiQA ([Clark et al., 2020](https://arxiv.org/abs/2003.05002)) | Open | Wikipedia | 26K | Yes | Q,A: from original language
| XQuAD ([Artetxe et al., 2020](https://aclanthology.org/2020.acl-main.421/)) | Wikipedia| SQuAD | 1.2 K | Yes | Q,A,D: aligned cross lang (human translate)
| MLQA ([Lewis et al., 2020](https://aclanthology.org/2020.acl-main.653/)) | Wikipedia | Wikipedia | 6K | Yes | Avg 4-way parallel (Q,A: human translate)
| ARCD ([Mozannar et al., 2019](https://arxiv.org/pdf/1906.05394.pdf)) | Wikipedia | Wikipedia | 1.4K | Yes |
| Arabic-SQuAD ([Mozannar et al., 2019](https://arxiv.org/pdf/1906.05394.pdf)) | Wikipedia | SQuAD | 48K | Yes | Machine translate

## Others

| Dataset (paper) | Domain | Source (Domain) | \#QA pairs | Lang | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| ANTIQUE ([Hashemi et al., 2020](https://arxiv.org/abs/1905.08957)) | Open-domain | Q: Community web | 34K (2.6K questions) | EN | Retrieval-based QA (CQA)
| TourismQA ([Contractor et al., 2020](https://arxiv.org/abs/1909.03527)) | Tourism | Tourism | 47K | EN | Retrieval-based QA
| Mathmatics ([Saxton et al., 2019](https://arxiv.org/abs/1904.01557)) | Math | Math | 2.1M | EN |Test calculation ability

