[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![License](https://img.shields.io/github/license/antoiloui/awesome-legal-nlp)

# Legal Natural Language Processing

## 🗂 Datasets

| Dataset | Task | Language | Size |
|---|---|---|---|
| [LexGLUE](https://github.com/coastalcph/lex-glue) [🤗](https://huggingface.co/datasets/lex_glue) [📄](https://arxiv.org/abs/2110.00976)  | Legal Language Understanding | 🇬🇧  |  |
| [Swiss-Judgment-Prediction](https://github.com/JoelNiklaus/SwissJudgementPrediction) [🤗](https://huggingface.co/datasets/swiss_judgment_prediction) [📄](https://arxiv.org/abs/2110.00806)  | Legal Judgment Prediction | 🇩🇪, 🇫🇷, 🇮🇹      | 85000 cases |
| [BSARD](https://github.com/maastrichtlawtech/bsard) [📄](https://arxiv.org/abs/2108.11792) | Statutory Article Retrieval | 🇫🇷  | 1108 questions, 22633 candidate articles |
| [GLC](https://github.com/christospi/glc-nllp-21) [🤗](https://huggingface.co/datasets/greek_legal_code) [📄](https://arxiv.org/abs/2109.15298)  | Legal Text Classification | 🇬🇷  | 47563 documents |
| [MultiEURLEX](https://github.com/nlpaueb/multi-eurlex) [🤗](https://huggingface.co/datasets/multi_eurlex) [📄](https://arxiv.org/abs/2109.00904)  | Legal Document Classification | 🇬🇧, 🇩🇪, 🇫🇷, 🇮🇹, 🇪🇸, 🇵🇱, 🇷🇴, 🇳🇱, 🇬🇷, 🇭🇺, 🇵🇹, 🇨🇿, 🇸🇪, 🇧🇬, 🇩🇰, 🇫🇮, 🇸🇰, 🇱🇹, 🇭🇷, 🇸🇮, 🇪🇪, 🇱🇻, 🇲🇹                                              | 65000 EU laws, 4591 labels |
| [CUAD](https://github.com/TheAtticusProject/cuad) [🤗](https://huggingface.co/datasets/cuad) [📄](https://arxiv.org/abs/2103.06268)  | Legal Contract Review | 🇬🇧  | 510 contracts, 13000 annotations |
| [ECtHR](https://archive.org/details/ECHR-ACL2019) [🤗](https://huggingface.co/datasets/ecthr_cases) [📄](https://arxiv.org/abs/2103.13084)  | Rationale Extraction | 🇬🇧  | 11000 cases |
| (i) [EU2UK](https://archive.org/details/eacl2021_regir_datasets) [📄](https://arxiv.org/abs/2101.10726)<br>(ii) [UK2EU](https://archive.org/details/eacl2021_regir_datasets) | Regulatory Information Retrieval | 🇬🇧  | (i) 2000 query documents, 52515 candidate documents<br>(ii) 2100 query documents, 3930 candidate documents |
| [JEC-QA](https://jecqa.thunlp.org/) [📄](https://arxiv.org/abs/1911.12011) | Legal Question Answering | 🇨🇳  | 26365 multiple-choice questions |
| [COLIEE-2020](https://sites.ualberta.ca/~rabelo/COLIEE2020/) [📄](https://sites.ualberta.ca/~rabelo/COLIEE2021/COLIEE_2020_summary.pdf) | (i) Case Law Retrieval<br>(ii) Case Law Entailment<br>(iii) Statutory Article Retrieval | (i) 🇬🇧<br>(ii) 🇬🇧<br>(iii) 🇬🇧, 🇯🇵  | (i) 650 base cases, 128000 candidate cases<br>(ii) 425 base cases<br>(iii) 808 questions, 768 candidate articles |
| [CAIL2019-SCM](https://github.com/china-ai-law-challenge/CAIL2019/tree/master/scm) [📄](https://arxiv.org/abs/1911.08962) | Similar Case Matching | 🇨🇳  | 8964 triplets of cases |
| [CJRC](https://github.com/china-ai-law-challenge/CAIL2019) [📄](https://arxiv.org/abs/1912.09156) | Judicial Reading Comprehension | 🇨🇳  | 50000 question-answers, 10000 documents |
| [EURLEX-57K](http://nlp.cs.aueb.gr/software_and_datasets/EURLEX57K/index.html) [📄](https://arxiv.org/abs/1906.02192) | Legal Document Classification | 🇬🇧  | 57000 EU laws, 4300 labels |
| [ECHR](https://archive.org/details/ECHR-ACL2019) [📄](https://arxiv.org/abs/1906.02059) | Legal Judgment Prediction | 🇬🇧  | 11478 documents |


## 🔥 Models

| Model | Task | Language | Size |
|---|---|---|---|
| [JuriBERT](http://master2-bigdata.polytechnique.fr/resources#juribert) [📄](https://arxiv.org/abs/2110.01485) | Language Modeling | 🇫🇷  | 6M, 15M, 42M, 110M |
| LEGAL-BERT [🤗](https://huggingface.co/nlpaueb/legal-bert-base-uncased) [📄](https://arxiv.org/abs/2010.02559)  | Language Modeling | 🇬🇧  | 35M, 110M |
| Greek-BERT [🤗](https://huggingface.co/nlpaueb/bert-base-greek-uncased-v1) [📄](https://arxiv.org/abs/2008.12014)  | Language Modeling | 🇬🇷  | 110M |


## 📚  Books

- [`2017`] *Artificial Intelligence and Legal Analytics: New Tools for Law Practice in the Digital Age*, K. Ashley. [[link]](https://www.cambridge.org/core/books/artificial-intelligence-and-legal-analytics/E7D705EEF392501A1DB180645917E7E0)


## 📄  Surveys

- [`2020-05`] *How Does NLP Benefit Legal System: A Summary of Legal Artificial Intelligence*, H. Zhong et al. [[pdf]](https://arxiv.org/pdf/2004.12158)
- [`2019-09`] *A Brief History of the Changing Roles of Case Prediction in AI and Law*, K. Ashley [[pdf]](https://journals.latrobe.edu.au/index.php/law-in-context/article/download/88/157)
- [`2018-12`] *Deep learning in law: early adaptation and legal word embeddings trained on large corpora*, I. Chalkidis et al. [[pdf]](https://link.springer.com/content/pdf/10.1007/s10506-018-9238-9.pdf)


## 🎙  Talks

- [`2019-06`] *Law as Data: The Promise and Challenges of Natural Language Processing for Legal Research*, A. Dyevre. [[slides]](https://drive.google.com/open?id=14zWlp2Hkm866MTup_oMZJa5T80fxsWtR)
- [`2019-04`] *Artificial Intelligence and Law – An Overview and History*, H. Surden. [[video]](https://www.youtube.com/watch?v=BG6YR0xGMRA)


## 🗓  Conferences & Workshops

- The Natural Legal Language Processing (NLLP) Workshop [[website]](https://nllpw.org/workshop/)
- The International Conference on Artificial Intelligence and Law (ICAIL) [[website]](https://dl.acm.org/doi/proceedings/10.1145/3322640#issue-downloads)
- The International Conference on Legal Knowledge and Information Systems (JURIX) [[website]](http://jurix.nl/)  
- The EXplainable AI in Law (XAILA) Workshop [[website]](https://www.geist.re/xaila:start)
- The International Workshop on Juris-informatics (JURISIN) [[website]](http://research.nii.ac.jp/~ksatoh/jurisin2020/)
- The Competition on Legal Information Extraction/Entailment (COLIEE) [[website]](https://sites.ualberta.ca/~rabelo/COLIEE2020/)
