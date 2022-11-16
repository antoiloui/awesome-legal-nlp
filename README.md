[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![License](https://img.shields.io/github/license/antoiloui/awesome-legal-nlp)

# Legal Natural Language Processing

## 🗂 Datasets

#### Legal Judgement Prediction (LJP)

| Dataset | Links | Domain | Language | Size |
|---|---|---|---|---|
| FSCS (Niklaus et al., 2021) | [📄](https://arxiv.org/abs/2110.00806) [🤗](https://huggingface.co/datasets/swiss_judgment_prediction) [💻](https://github.com/JoelNiklaus/SwissJudgementPrediction) | Swiss court judgments | 🇩🇪 🇫🇷 🇮🇹 | 85K cases w/ 2 outcomes |
| ECtHR (Chalkidis et al., 2021) | [📄](https://arxiv.org/abs/2103.13084) [🤗](https://huggingface.co/datasets/ecthr_cases) | EU court judgments | 🇬🇧  | 11K cases w/ 11 outcomes |
| ECHR (Aletras et al., 2019) | [📄](https://arxiv.org/abs/1906.02059) [💾](https://archive.org/details/ECHR-ACL2019) | EU court judgments | 🇬🇧 | 11.5K cases w/ 11 outcomes |
| CAIL (Xiao et al., 2018) | [📄](https://arxiv.org/abs/1807.02478) [💻](https://github.com/china-ai-law-challenge/CAIL2018) | Chinese court judgements | 🇨🇳 | 2.6M cases w/ 6 outcomes |

#### Legal Topic Classification (LTC)

| Dataset | Links | Domain | Language | Size |
|---|---|---|---|---|
| GLC (Papaloukas et al., 2021) | [📄](https://arxiv.org/abs/2109.15298) [🤗](https://huggingface.co/datasets/greek_legal_code) [💻](https://github.com/christospi/glc-nllp-21) | Greek legislation | 🇬🇷  | 47.5K laws w/ 2.7K labels |
| CUAD (Hendrycks et al., 2021) | [📄](https://arxiv.org/abs/2103.06268) [🤗](https://huggingface.co/datasets/cuad) [💻](https://github.com/TheAtticusProject/cuad)| Contracts | 🇬🇧  | 510 contracts w/ 41 labels |
| MultiEURLEX (Chalkidis et al., 2021) | [📄](https://arxiv.org/abs/2109.00904) [🤗](https://huggingface.co/datasets/multi_eurlex) [💻](https://github.com/nlpaueb/multi-eurlex) | EU legislation | 🇬🇧 🇩🇪 🇫🇷 🇮🇹 🇪🇸 (18+) | 65,000 laws w/ 4,591 labels |
| EURLEX-57K (Chalkidis et al., 2019) | [📄](https://arxiv.org/abs/1906.02192) [💾](http://nlp.cs.aueb.gr/software_and_datasets/EURLEX57K/index.html) | EU legislation | 🇬🇧  | 57,000 laws w/ 4,300 labels |
| Unfair-ToS (Lippi et al., 2018) | [📄](https://arxiv.org/abs/1805.01217) | Contracts | 🇬🇧 | 9.4K sentences w/ 9 labels |

#### Legal Information Retrieval (LIR)

| Dataset | Links | Domain | Language | Size |
|---|---|---|---|---|
| BSARD (Louis et al., 2022) | [📄](https://arxiv.org/abs/2108.11792) [🤗](https://huggingface.co/datasets/antoiloui/bsard) [💻](https://github.com/maastrichtlawtech/bsard) | Belgian legislation | 🇫🇷  | 1.1K questions w/ 22.6K candidate statutory articles |
| EU2UK (Chalkidis et al., 2021) | [📄](https://arxiv.org/abs/2101.10726) [💾](https://archive.org/details/eacl2021_regir_datasets) | EU & UK legislation |🇬🇧  | 2K query documents w/ 52.5K candidate documents |
| UK2EU (Chalkidis et al., 2021) | [📄](https://arxiv.org/abs/2101.10726) [💾](https://archive.org/details/eacl2021_regir_datasets) | EU & UK legislation |🇬🇧  | 2.1K query documents w/ 3.9K candidate documents |
| COLIEE-Case-Law-Retrieval (Rabelo et al., 2020) | [📄](https://sites.ualberta.ca/~rabelo/COLIEE2021/COLIEE_2020_summary.pdf) [💾](https://sites.ualberta.ca/~rabelo/COLIEE2020/) | Canadian precedents | 🇬🇧 |  650 query cases w/ 128K candidate cases |
| COLIEE-Statute-Law-Retrieval (Rabelo et al., 2020) | [📄](https://sites.ualberta.ca/~rabelo/COLIEE2021/COLIEE_2020_summary.pdf) [💾](https://sites.ualberta.ca/~rabelo/COLIEE2020/) | Japanese legislation | 🇬🇧 🇯🇵 |  808 questions w/ 768 candidate statutory articles |
| CAIL2019-SCM (Xiao et al., 2019) | [📄](https://arxiv.org/abs/1911.08962) [💻](https://github.com/china-ai-law-challenge/CAIL2019/tree/master/scm) | Chinese court judgements | 🇨🇳 | 8.9K triplets of cases |

#### Legal Question Answering (LQA)

| Dataset | Links | Domain | Language | Size |
|---|---|---|---|---|
| CaseHOLD (Zheng et al., 2021) | [📄](https://arxiv.org/abs/2104.08671) [💻](https://github.com/reglab/casehold) | US case holdings | 🇬🇧 | 53.1K multiple-choice questions |
| JEC-QA (Zhong et al., 2019) | [📄](https://arxiv.org/abs/1911.12011) [💾](https://jecqa.thunlp.org/) | Chinese law | 🇨🇳  | 26.3K multiple-choice questions |
| CJRC (Duan et al., 2019) | [📄](https://arxiv.org/abs/1912.09156) [💻](https://github.com/china-ai-law-challenge/CAIL2019) | Chinese court judgements | 🇨🇳 | 50K question-answers from 10K documents |

#### Legal Textual Entailment (LTE)

| Dataset | Links | Domain | Language | Size |
|---|---|---|---|---|
| COLIEE-Case-Law-Entailment (Rabelo et al., 2020) | [📄](https://sites.ualberta.ca/~rabelo/COLIEE2021/COLIEE_2020_summary.pdf) [💾](https://sites.ualberta.ca/~rabelo/COLIEE2020/) | Canadian precedents | 🇬🇧 |  425 cases w/ related case |
| COLIEE-Statute-Law-Entailment (Rabelo et al., 2020) | [📄](https://sites.ualberta.ca/~rabelo/COLIEE2021/COLIEE_2020_summary.pdf) [💾](https://sites.ualberta.ca/~rabelo/COLIEE2020/) | Japanese legislation | 🇬🇧 🇯🇵 |  808 questions w/ related statutory article |

#### Legal Language Modeling (LLM)

| Dataset | Links | Language | Size |
|---|---|---|---|
| Pile of Law (Henderson et al., 2022) | [📄](https://arxiv.org/abs/2207.00220) [🤗](https://huggingface.co/datasets/pile-of-law/pile-of-law) [💻](https://github.com/Breakend/PileOfLaw) | 🇬🇧 | ~256GB of legal and administrative legal text |

#### Benchmarks

| Dataset | Task | Language | Tasks |
|---|---|---|---|
| FairLex (Chalkidis et al., 2022) | [📄](https://arxiv.org/abs/2203.07228) [🤗](https://huggingface.co/datasets/coastalcph/fairlex) [💻](https://github.com/coastalcph/fairlex) | 🇬🇧 🇩🇪 🇫🇷 🇮🇹 🇨🇳 | Clasification (x1), legal judgement prediction (x3) |
| LexGLUE (Chalkidis et al., 2022) | [📄](https://arxiv.org/abs/2110.00976) [🤗](https://huggingface.co/datasets/lex_glue) [💻](https://github.com/coastalcph/lex-glue) | 🇬🇧  | Classsification (x6), multiple-choice QA (x1) |

## 🔥 Models

| Model | Links | Language | Size |
|---|---|---|---|
| PoL-BERT-Large (Henderson et al., 2022) | [📄](https://arxiv.org/abs/2207.00220) [🤗](https://huggingface.co/pile-of-law/legalbert-large-1.7M-1) [💻](https://github.com/Breakend/PileOfLaw) | 🇬🇧 | 336M |
| Italian-LEGAL-BERT (Licari and Comande, 2022) | [📄](https://ceur-ws.org/Vol-3256/km4law3.pdf) [🤗](https://huggingface.co/dlicari/Italian-Legal-BERT)| 🇮🇹 | 110M |
| JuriBERT (Douka et al., 2021) | [📄](https://arxiv.org/abs/2110.01485) [💾](http://master2-bigdata.polytechnique.fr/resources#juribert) | 🇫🇷  | {6M, 15M, 42M, 110M} |
| Custom-LEGAL-BERT (Zheng et al., 2021) | [📄](https://arxiv.org/abs/2104.08671) [🤗](https://huggingface.co/zlucia/custom-legalbert) [💻](https://github.com/reglab/casehold) | 🇬🇧  | 110M |
| LEGAL-BERT (Chalkidis et al., 2020) | [📄](https://arxiv.org/abs/2010.02559) [🤗](https://huggingface.co/nlpaueb/legal-bert-base-uncased) | 🇬🇧  | {35M, 110M} |
| LEGAL-GPT-{1,2} (Borchmann et al., 2020) | [📄](https://arxiv.org/abs/1911.03911) [💻](https://github.com/applicaai/contract-discovery) | 🇬🇧  | {117M, 1.5B} |

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
- The International Workshop on Legal Information Retrieval [[website]](https://tmr.liacs.nl/legalIR/)
