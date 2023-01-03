# QA-Datasets

This repo aims to facilitate NLP researchers to find relevant QA datasets.
Welcome to correct any mistakes, add new datasets, or provide any type of suggestions.

Note: Currently Visual QA, Conversational QA and Table QA are far from complete.

## Cloze-style

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | \# Passages | Blanks | Language | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| TempLAMA | [Dhingra et al., 2022](https://arxiv.org/abs/2106.15110) | Wikidata | 50K | 50K | Entity | EN | Q:template; A: time-dependent
| SCDE | [Kong et al., 2020](https://aclanthology.org/2020.acl-main.502/) | Language Exams | 30K | 6k | Sentences | EN | Q: human created
| CLOTH | [Xie et al., 2018](https://aclanthology.org/D18-1257/) | Language Exams | 99K | 7K | Words | EN | Q: human created
| Quasar-S | [Dhingra et al., 2017](https://arxiv.org/abs/1707.03904) | StackOverflow | 37K | 37K | Software entity | EN | 
| Story Cloze Test | [Mostafazadeh et al., 2017](https://aclanthology.org/W17-0906/) | Commonsense stories | 102K | 102K | Sentences | EN | based on ROCStories 
| LAMBADA | [Paperno et al., 2016](https://arxiv.org/abs/1606.06031) | Books | 10K |10K | Words | EN | 
| ROCStories | [Mostafazadeh et al., 2016](https://aclanthology.org/N16-1098/) | Commonsense stories | 50K | 50K | Sentences | EN | Ending prediction
| People Daily & CFT | [Cui et al., 2016](https://aclanthology.org/C16-1167/) | People Daily & Children’s Fairy Tale | 873K | 60K | Words | ZH | D: News
| BookTest | [Bajgar et al., 2016](https://arxiv.org/pdf/1610.00956.pdf) | Books | 14M | 14K | Words | EN |
| CNN & Daily Mail | [Hermann et al., 2015](https://proceedings.neurips.cc/paper/2015/hash/afdec7005cc9f14302cd0474fd0f3c96-Abstract.html) | CNN & Daily Mail | 1.4M | 301K | Entity | EN |
| CBT | [Hill et al., 2015](https://arxiv.org/pdf/1511.02301.pdf) | Children’s books | 687K | 687K | Words | EN | 


## Multiple choice

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | Language | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| CaseHOLD | [Zheng et al., 2021](https://arxiv.org/abs/2104.08671) | Law | 53K | EN | 
| LogiQA | [Liu et al., 2020](https://arxiv.org/abs/2007.08124) | Exams | 8.6K | EN | Logical reasoning
| PubMedQA | [Jin et al., 2021](https://aclanthology.org/D19-1259/) | Medical | 211K | EN | A:yes/no & long answer
| PIQA | [Bisk et al., 2020](https://arxiv.org/abs/1911.11641)| Physical | 21K | EN | Physical commonsense
| ReClor | [Yu et al., 2020](https://arxiv.org/abs/2002.04326) | Exams | 6K | EN | Logical reasoning
| CosmosQA | [Huang et al., 2019](https://aclanthology.org/D19-1243/) | Personal narratives | 36K | EN | Commonsense
| SocialIQa | [Sap et al., 2019](https://arxiv.org/pdf/1904.09728.pdf) | Social & emotional | 38K | EN |
| BoolQ | [Clark et al., 2019](https://arxiv.org/abs/1905.10044) | Wikipedia | 16K | EN | Q: from NQ; A: yes/no
| QASC | [Khot et al., 2020](https://ojs.aaai.org//index.php/AAAI/article/view/6319) | Q: Science | 10K | EN |
| CommonsenseQA | [Talmor et al., 2019](https://aclanthology.org/N19-1421/) | Q: ConceptNet | 12K | EN | Commonsense
| WikiHop | [Welbl et al., 2018](https://aclanthology.org/Q18-1021/) | Wikipedia | 51K | EN | Multi-hop
| MedHop | [Welbl et al., 2018](https://aclanthology.org/Q18-1021/) | Molecular biology | 2.5K | EN | Multi-hop
| SWAG | [Zellers et al., 2018](https://aclanthology.org/D18-1009/) | Video Captions | 113K | EN | Commonsense
| OpenBookQA | [Mihaylow et al., 2018](https://arxiv.org/abs/1809.02789) | Q: Science | 6K | EN | Multi-hop
| MultiRC | [Khashabi et al., 2018](https://aclanthology.org/N18-1023/) | Multiple | 6K | EN | Multi-sentence reasoning
| ARC | [Clark et al., 2018](https://arxiv.org/abs/1803.05457) | Q: Science | 14M | EN |
| RACE | [Lai et al., 2017](https://aclanthology.org/D17-1082/) | Exams | 98K | EN | 
| WikiQA | [Yang et al., 2015](https://aclanthology.org/D15-1237/) | Q: Bing query logs  | 3K | EN | 
| MCTest | [Richardson et al., 2013](https://aclanthology.org/D13-1020/) | Fictional stories  | 2K | EN | 
| COPA |[Roemmele et al., 2011](https://people.ict.usc.edu/~gordon/copa.html) | Q: Weblogs and library | 1K | EN |

## Span Extraction

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | Language | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| MultiSpanQA | [Li et al., 2022](https://multi-span.github.io) | Wikipedia (NQ) | 6K | EN | Q: from NQ; A: multi-span 
| TimeQA | [Chen et al., 2021](https://arxiv.org/abs/2108.06314) | Q:Wikidata | 40K | EN | Temporal reasoning
| ConditionalQA | [Sun et al., 2021](https://aclanthology.org/2022.acl-long.253.pdf) | Government website | 3.1K | EN | A: conditional
| QASPER | [Dasigi et al., 2021](https://aclanthology.org/2021.naacl-main.365.pdf) | NLP papers | 5K | EN | A: span & free from & bool; table reasoning
| NLQuAD | [Soleimani et al., 2021](https://aclanthology.org/2021.eacl-main.106/) | BBC News | 31K | EN | Q: non-factoid; A: long (175 words) 
| WikiHowQA | [Cui et al., 2021](https://arxiv.org/abs/2110.11692) | www.wikihow.com |247K | EN | Q: non-factoid; A: list 
| WebQA | [Cui et al., 2021](https://arxiv.org/abs/2110.11692) | Chinese QA websites | 40K | ZH | Q: non-factoid; A: list 
| 2WikiMultiHopQA | [Ho et al., 2020](https://aclanthology.org/2020.coling-main.580/) | Wikipedia | 193K | EN | Multi-hop; KB
| AmbigQA | [Min et al., 2020](https://aclanthology.org/2020.emnlp-main.466/) | Wikipedia (NQ) | 14K | EN | Q: ambigious 
| Quoref | [Dasigi et al., 2019](https://aclanthology.org/D19-1606/) | Wikipedia | 24K | EN | Resolve coreference
| NQ | [Kwiatkowski et al., 2019](https://ai.google.com/research/NaturalQuestions) | Wikipedia | 307K | EN | D: Long; A: long (192 words) & short
| DROP | [Dua et al., 2019](https://aclanthology.org/N19-1246/) | Wikipedia | 96K | EN | Discrete reasoning
| HotpotQA | [Yang et al., 2018](https://aclanthology.org/D18-1259/) | Wikipedia | 113K | EN | Multi-hop 
| DuoRC | [Saha et al., 2018](https://aclanthology.org/P18-1156/) | Wikipedia & IMDB | 186K | EN | Q&D: Movie
| SQuAD 2.0 | [Rajpurkar et al., 2018](https://aclanthology.org/P18-2124/) | Wikipedia | 151K | EN |
| TriviaQA | [Joshi et al., 2017](https://aclanthology.org/P17-1147/) | Q: Trivia quizzes | 96K | EN |
| NewsQA | [Trischler et al., 2017](https://aclanthology.org/W17-2623/) | CNN articles | 120K | EN |
| SearchQA | [Dunn et al., 2017](https://arxiv.org/abs/1704.05179) | Q: Jeopardy! | 140k | EN |
| SQuAD | [Rajpurkar et al., 2016](https://aclanthology.org/D16-1264/) | Wikipedia | 108K | EN |

## Free From

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | Language | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| SituatedQA | [Zhang et al., 2021](https://arxiv.org/abs/2109.06157) | Multiple | 9K | EN | A:context-dependent
| JDProductQA | [Gao et al., 2019](https://arxiv.org/abs/1901.07696) | E-commerce | 470K | ZH | D: reviews & attributes
| ELI5 | [Fan et al., 2019](https://facebookresearch.github.io/ELI5/) | Reddit | 272K | EN | A:long (130 words)
| TweetQA | [Xiong et al, 2019](https://arxiv.org/pdf/1907.06292.pdf) | Tweets | 14K | EN
| DuReader | [He et al., 2018](https://arxiv.org/pdf/1711.05073.pdf) | Baidu Zhidao | 200K | ZH
| NarrativeQA | [Koˇcisky ́ et al., 2018](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00023/43442/The-NarrativeQA-Reading-Comprehension-Challenge) | Book & movie | 47K | EN
| MS Marco | [Nguyen et al., 2016](https://ceur-ws.org/Vol-1773/CoCoNIPS_2016_paper9.pdf) | Q: Bing query logs | 100K | EN


## Knowledge-based QA

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | Language | KB | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |
| LC-QuAD 2.0 | [Dubey et al., 2019](http://lc-quad.sda.tech/) | Q: templates | 30K | EN | Wikidata & DBpedia | Q: SPARQL
| ComplexWebQ | [Talmor and Berant, 2018](https://www.tau-nlp.sites.tau.ac.il/compwebq) | Q: WebQSP | 35K | EN | Freebase | Q: SPARQL
| QAngaroo | [Welbl et al., 2018](https://aclanthology.org/Q18-1021/) | Wikipedia & PubMed | 54K | EN | |
| MetaQA | [Zhang et al., 2018](https://arxiv.org/abs/1709.04071) | Wikipedia (Movie) | 400K | EN | Self-construct | Multi-hop; text & audio data
| LC-QuAD | [Trivedi et al., 2017](https://github.com/AskNowQA/LC-QuAD) | Q: templates | 5K | EN | DBpedia | Q:SPARQL
| WikiMovies | [Miller et al., 2016](https://arxiv.org/abs/1606.03126) | Wikipedia (Movie) | 100K | EN | Self-construct | 
| WebQSP | [Yih et al., 2016](https://aclanthology.org/P16-2033/) | Q: WebQuestions | 4.7K | EN | Freebase | Q:SPARQL
| WebQuestions | [Berant et al., 2013](https://aclanthology.org/D13-1160/) | Q: Google suggest API | 5.8K | EN | Freebase | Q: SPARQL

## Visual QA 

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | Language | Anawer Type | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |
| Social-IQ | [Zadeh et al., 2019](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zadeh_Social-IQ_A_Question_Answering_Benchmark_for_Artificial_Social_Intelligence_CVPR_2019_paper.pdf) | Social | 7.5K | EN | Multi-choice
| MovieQA | [Tapaswi et al., 2016](https://openaccess.thecvf.com/content_cvpr_2016/papers/Tapaswi_MovieQA_Understanding_Stories_CVPR_2016_paper.pdf) | Movie | 21K | EN | Multi-choice 


## Conversational QA

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | \# Dialogues | Language | Answer Type | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| MuTual | [Cui et al., 2020](https://aclanthology.org/2020.acl-main.130/) | Exam | 8.8K | 8.8K | EN | Multi-choice | A: ending 
| DREAM | [Sun et al., 2019](https://aclanthology.org/Q19-1014/) | Exam | 10K | 6.4K | EN | Multi-choice | 
| ShARC | [Saeidi et al., 2018](http://aclanthology.lst.uni-saarland.de/D18-1233.pdf) | Rules | 32K | 948 | EN | Multi-choice | Mode: dialog tree
| CoQA | [Reddy et al., 2018](https://stanfordnlp.github.io/coqa/) | Multiple | 127K | 8.4K | EN | Free from |

## Table QA 

| Dataset (paper) | Paper (Website) | Source | \# QA pairs | \# Tables | Language | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |:----- |
| FinQA | [Chen et al., 2020](https://aclanthology.org/2021.emnlp-main.300/) | Financial | 8.3K | 2.8K | EN | D: table & text
| HybridQA | [Chen et al., 2020](https://aclanthology.org/2020.findings-emnlp.91/) | Wikipedia | 70K | 13K | EN | D: table & text; Multi-hop
| WikiSQL | [Zhong et al., 2017](https://arxiv.org/abs/1709.00103) | Wikipedia | 81K | 2.4K | EN | Q:NL & SQL
| WikiTableQ| [Pasupat et al., 2015](https://aclanthology.org/P15-1142/) | Wikipedia  | 22K | 2K | EN | 

## Others

| Dataset (paper) | Paper (Website) | Source (Domain) | \#QA pairs | Language | Note
| ------------- |:----- |:----- |:----- |:----- |:----- |
| ANTIQUE | [Hashemi et al., 2020](https://arxiv.org/abs/1905.08957) | Open-domain | 34K (2.6K questions) | EN | Retrieval-based QA (CQA)
| TourismQA | [Contractor et al., 2020](https://arxiv.org/abs/1909.03527) | Tourism | 47K | EN | Retrieval-based QA
| Mathmatics | [Saxton et al., 2019](https://arxiv.org/abs/1904.01557) | Math | 2.1M | EN |Test calculation ability

