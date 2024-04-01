# 荒瀬 由紀

[東京工業大学](https://www.titech.ac.jp/)  
[情報理工学院](https://www.titech.ac.jp/about/organization/schools/organization04)  
<!--- [ビッグデータ工学講座 (鬼塚研究室)](https://www.ist.osaka-u.ac.jp/japanese/)  -->
准教授  

Email: arase[at]ist.osaka-u.ac.jp  
Twitter: [@Yuki_arase](https://twitter.com/Yuki_arase)


2006年大阪大学工学部電子情報エネルギー工学科卒業。
2007年同大学院情報科学研究科博士前期課程、2010年同博士後期課程修了。博士（情報科学）。同年、北京のMicrosoft Researchに入社、自然言語処理に関する研究開発に従事。
2014年より大阪大学大学院情報科学研究科マルチメディア工学専攻准教授、2024年より東京工業大学情報理工学院教授、現在に至る。
言い換え表現認識および生成、それらを応用した言語学習支援、医療言語処理に興味を持つ。

博士後期課程学生を募集しています。興味のある方は業績リスト付きのCVをお送りください。
※ 研究生の募集はしていません。

***

[Publications](./publication.md) / [ACL Anthology](https://www.aclweb.org/anthology/people/y/yuki-arase/) / [Google Scholar](https://scholar.google.com/citations?user=uoL1Wr0AAAAJ&hl=en) / [Semantic Scholar](https://www.semanticscholar.org/author/Yuki-Arase/3043844)

***

## News
* 東京工業大学情報理工学院に着任しました。
* [『IT Text 自然言語処理の基礎』](https://www.ohmsha.co.jp/book/9784274229008/)（岡﨑 直観, 荒瀬 由紀, 鈴木 潤, 鶴岡 慶雅, 宮尾 祐介 共著）、オーム社より発売中

(Last update: 2024/04/01)


## Research
For more details, please see [Research](./research.md) page.

#### Paraphrase generation & recognition
Paraphrasing takes various forms of monolingual text transformations, such as text simplification, rewriting, and style transfer. 
We work on both recognition and generation. The core technologies are intelligent phrase alignment and controllable paraphrase generation. 

Related papers: [DIRECT](https://aclanthology.org/2021.findings-emnlp.170/), [phrase alignment](https://aclanthology.org/2020.emnlp-main.125/), [Round-trip translation for paraphrasing](https://ojs.aaai.org//index.php/AAAI/article/view/6314), [SAPPHIRE](https://aclanthology.org/2020.lrec-1.847/)

#### Representation learning
Vector representation of words, phrases, and sentences are the very basis for NLP research. We study
1. sophisticated representations for word meaning in context and multilingual sentences,
2. efficient pre-trained models for words and phrases, and
3. representations for few-shot learning.   

Related papers: [WiC representation](https://aclanthology.org/2021.findings-emnlp.49/), [disentangling sentence meaning](https://aclanthology.org/2021.emnlp-main.612/), [transfer fine-tuning](https://aclanthology.org/D19-1542/), [label representation for few-shot learning](https://aclanthology.org/2021.acl-short.105/), [tiny word embedding](https://aclanthology.org/2020.coling-main.103/)

#### NLP for language education & learning
As a central application of our research outcomes, we develop technologies for language learning and education supports. 
Our technology covers from fine-grained lexical-level transformations to coarse-grained text-level processing.

Related papers: [definition generation](https://aclanthology.org/2021.emnlp-main.194/), [controllable text simplification](https://aclanthology.org/P19-2036/), [CEFR-based lexical simplification](https://aclanthology.org/L18-1514/), [fill-in-the-blank quiz generation](https://aclanthology.org/P13-2043/)


## Selected Recent Publications
* R. Miyano, T. Kajiwara, Y. Arase. Self-Ensemble of N-best Generation Hypotheses by Lexically Constrained Decoding, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP 2023) (Dec. 2023).
* Y. Arase, H. Bao, and S. Yokoi. Unbalanced Optimal Transport for Unbalanced Word Alignment, in Proc. of the Annual Meeting of the Association for Computational Linguistics (ACL 2023), pp. 3966–3986 (July 2023).
* Y. Arase, S. Uchida, and T. Kajiwara. CEFR-based Sentence Difficulty Annotation and Assessment, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2022), pp. 6206-6219 (Dec. 2022).
* Y. Kuroda, T. Kajiwara, Y. Arase, and T. Ninomiya. Adversarial Training on Disentangling Meaning and Language Representations for Unsupervised Quality Estimation, in Proc. of International Conference on Computational Linguistics (COLING 2022), pp. 5240-5245 (Oct. 2022).
* 西原哲郎, 岩本裕司, 吉仲真人, 梶原智之, 荒瀬由紀, 二宮崇. 多言語雑音除去自己符号化器による教師なし品質推定. 自然言語処理 Vol. 29, No. 2, pp. 669-687 (2022年6月).
* 高山隼矢, 梶原智之, 荒瀬由紀. 対話における間接的応答と直接的応答からなる言い換えコーパスの構築と分析. 自然言語処理Vol. 29, No. 1, pp. 84-111 (2022年3月).
* H. Huang, T. Kajiwara, and Y. Arase. Definition Modelling for Appropriate Specificity, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2021), pp. 2499–2509 (Nov. 2021).
* N. Tiyajamorn, T. Kajiwara, Y. Arase, and M. Onizuka. Language-agnostic Representation from Multilingual Sentence Encoders for Cross-lingual Similarity Estimation, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2021), pp. 7764–7774 (Nov. 2021).
* Y. Arase and T. Kajiwara. Distilling Word Meaning in Context from Pre-trained Language Model, in Findings of the Association for Computational Linguistics: EMNLP 2021, pp. 534–546 (Nov. 2021). [code](https://github.com/yukiar/distil_wic)
* J. Takayama, T. Kajiwara, and Y. Arase. DIRECT: Direct and Indirect Responses in Conversational Text Corpus, in Findings of the Association for Computational Linguistics: EMNLP 2021, pp. 1980–1989 (Nov. 2021). [data](https://github.com/junya-takayama/DIRECT)
* S. Ohashi, J. Takayama, T. Kajiwara, and Y. Arase. Distinct Label Representations for Few-Shot Text Classification, in Proc. of the Annual Meeting of the Association for Computational Linguistics and International Joint Conference on Natural Language Processing (ACL-IJCNLP2021), pp. 831-836 (Aug. 2021).
* Y. Arase and J. Tsujii: Transfer Fine-Tuning of BERT with Phrasal Paraphrases, in Computer Speech & Language, Vol. 66 (Mar. 2021). [paper](https://www.sciencedirect.com/science/article/pii/S0885230820300978) 
* S. Ohashi, M. Isogawa, T. Kajiwara and Y. Arase: Tiny Word Embeddings Using Globally Informed Reconstruction, in Proc. of International Conference on Computational Linguistics (COLING2020), pp. 1199–1203 (Dec. 2020). 
* Y. Arase and J. Tsujii: Compositional Phrase Alignment and Beyond, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2020), pp. 1611–1623 (Nov. 2020). 
* J. Takayama and Y. Arase: Consistent Response Generation with Controlled Specificity. in Proc. of Findings of the Association for Computational Linguistics: EMNLP 2020, pp. 4418–4427 (Nov. 2020). 
* S. Ohashi, J. Takayama, T. Kajiwara, C. Chu, Y. Arase. Text Classification with Negative Supervision, in Proc. of Annual Meeting of the Association for Computational Linguistics (ACL 2020), pp. 351–357 (July 2020).
* T. Kajiwara, B. Miura, and Y. Arase. Monolingual Transfer Learning via Bilingual Translators for Style-Sensitive Paraphrase Generation, in Proc. of the AAAI Conference on Artificial Intelligence (AAAI 2020), pp. 8042-8049, (Feb. 2020).
* Y. Arase and J. Tsujii: Transfer Fine-Tuning: A BERT Case Study, Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2019), pp. 5396–5407 (Nov. 2019).
* J. Takayama, E. Nomoto, and Y. Arase: Dialogue Breakdown Detection Robust to Variations in Annotators and Dialogue Systems, Computer Speech & Language, Vol. 54, pp. 31-43 (Mar. 2019).
* Y. Arase and J. Tsujii: SPADE: Evaluation Dataset for Monolingual Phrase Alignment, in Proc. of Language Resources and Evaluation Conference (LREC 2018), (May 2018).

## Academic Service
* PC Chair: [IJCNLP-AACL2023](http://www.ijcnlp-aacl2023.org/), [SNL2021](http://www.am.sanken.osaka-u.ac.jp/SNL2021/index.html)
* Senior Area Chair: [ACL2023](https://2023.aclweb.org/committees/program/)
* Area Chair: ARR, ACL2020, 2021, EMNLP2021
* Publicity and Social Media Chair: ACL2024
* Publication Chair for ACL2020 
* Member-at-large: Asian Federation of Natural Language Processing(AFNLP)
* 言語処理学会 理事（2020年3月～）
* 情報処理学会自然言語処理研究会 幹事（2015年4月～2019年3月）
* 言語処理学会論文誌「自然言語処理」編集委員（2015年9月～2019年9月）
* Reviewer: ACL, EMNLP, NAACL, EACL, TACL, Computational Linguistics, etc.  

