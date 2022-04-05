# Research Projects

More information will be added soon. 

## Paraphrase generation & recognition
Paraphrasing takes various forms of monolingual text transformations, such as text simplification, rewriting, and style transfer. 
We work on both recognition and generation. The core technologies are intelligent phrase alignment and controllable paraphrase generation. 

Phrase alignment aims to identify phrasal paraphrases with syntactic structures. This technology is also valuable for estimating semantic similarities between texts for evaluating text generation models such as machine translation and automatic QA. 

Current text generation models perform mostly black-box; we don't know what comes out until the end. In paraphrasing, we are interested in realising controllability in text generation to allow fine-grained control of output texts. 

##### Publications
* J. Takayama, T. Kajiwara, and Y. Arase. DIRECT: Direct and Indirect Responses in Conversational Text Corpus, in Findings of the Association for Computational Linguistics: EMNLP 2021, pp. 1980–1989 (Nov. 2021). [data](https://github.com/junya-takayama/DIRECT)
* Y. Arase and J. Tsujii: Compositional Phrase Alignment and Beyond, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2020), pp. 1611–1623 (Nov. 2020). 
[code](https://github.com/yukiar/phrase_alignment_cted)
* J. Takayama and Y. Arase: Consistent Response Generation with Controlled Specificity. in Proc. of Findings of the Association for Computational Linguistics: EMNLP 2020, pp. 4418–4427 (Nov. 2020). 
* M. Yoshinaka, T. Kajiwara, and Y. Arase. SAPPHIRE: Simple Aligner for Phrasal Paraphrase with Hierarchical Representation, in Proc. of Language Resources and Evaluation Conference (LREC 2020), pp. 6861–6867 (May 2020).
* D. Nishihara, T. Kajiwara, and Y. Arase: Controllable Text Simplification with Lexical Constraint, in Proc. of Annual Meeting of the Association for Computational Linguistics: Student Research Workshop, pp. 260-266, (July 2019).
* T. Kajiwara, B. Miura, and Y. Arase. Monolingual Transfer Learning via Bilingual Translators for Style-Sensitive Paraphrase Generation, in Proc. of the AAAI Conference on Artificial Intelligence (AAAI 2020), pp. 8042-8049, (Feb. 2020).
* Y. Arase and J. Tsujii: SPADE: Evaluation Dataset for Monolingual Phrase Alignment, in Proc. of Language Resources and Evaluation Conference (LREC 2018), (May 2018).
* Y. Arase and J. Tsujii: Monolingual Phrase Alignment on Parse Forests, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP 2017), pp. 1-11 (Sept. 2017).

##### Datasets
We have created datasets for phrase alignment that (1) provide ground-truth tree structures (HPSG) and (2) provide ground-truth phrase alignments. 

* SPADE, an evaluation dataset with 201 paraphrasal sentence pairs: [LDC2018T09](https://catalog.ldc.upenn.edu/LDC2018T09).
* ESPADA, a training (most likely for fine-tuning pre-trained masked language models) dataset with 1,916 paraphrasal sentence pairs: [LDC2021T10](https://catalog.ldc.upenn.edu/LDC2021T10).

A parallel corpus of direct and indirect utterances is beneficial for natural language understanding in conversation systems and advancing paraphrase recognition in challenging and realistic settings. 
* DIRECT, a training and evaluation datasets with 71k pairs of direct and indirect utterances. [data](https://github.com/junya-takayama/DIRECT)


## Representation learning
Vector representation of words, phrases, and sentences are the very basis for NLP research. We study
1. sophisticated representations for word meaning in context and multilingual sentences,
2. efficient pre-trained models for words and phrases, and
3. representations for few-shot learning.   

##### Publications
* N. Tiyajamorn, T. Kajiwara, Y. Arase, and M. Onizuka. Language-agnostic Representation from Multilingual Sentence Encoders for Cross-lingual Similarity Estimation, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2021), pp. 7764–7774 (Nov. 2021).
* Y. Arase and T. Kajiwara. Distilling Word Meaning in Context from Pre-trained Language Model, in Findings of the Association for Computational Linguistics: EMNLP 2021, pp. 534–546 (Nov. 2021). [code](https://github.com/yukiar/distil_wic)
* S. Ohashi, J. Takayama, T. Kajiwara, and Y. Arase. Distinct Label Representations for Few-Shot Text Classification, in Proc. of the Annual Meeting of the Association for Computational Linguistics and International Joint Conference on Natural Language Processing (ACL-IJCNLP2021), pp. 831-836 (Aug. 2021).
* Y. Arase and J. Tsujii: Transfer Fine-Tuning of BERT with Phrasal Paraphrases, in Computer Speech & Language, Vol. 66 (Mar. 2021) [paper](https://www.sciencedirect.com/science/article/pii/S0885230820300978) [code & model](https://github.com/yukiar/TransferFT)
* S. Ohashi, M. Isogawa, T. Kajiwara and Y. Arase: Tiny Word Embeddings Using Globally Informed Reconstruction, in Proc. of International Conference on Computational Linguistics (COLING2020), pp. 1199–1203 (Dec. 2020). 
* S. Ohashi, J. Takayama, T. Kajiwara, C. Chu, Y. Arase. Text Classification with Negative Supervision, in Proc. of Annual Meeting of the Association for Computational Linguistics (ACL 2020), pp. 351–357 (July 2020).
* Y. Arase and J. Tsujii: Transfer Fine-Tuning: A BERT Case Study, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2019), pp. 5396–5407 (Nov. 2019).
* K. Ashihara, T. Kajiwara, Y. Arase and S. Uchida: Contextualized context2vec, in Proc. of Workshop on Noisy User-generated Text (W-NUT 2019), pp. 397–406 (Nov. 2019).

## NLP for language education & learning
As a central application of our research outcomes, we develop technologies for language learning and education supports. 
Our technology covers from fine-grained lexical-level transformations to coarse-grained text-level processing.

##### Publications
* H. Huang, T. Kajiwara, and Y. Arase. Definition Modelling for Appropriate Specificity, in Proc. of Conference on Empirical Methods in Natural Language Processing (EMNLP2021), pp. 2499–2509 (Nov. 2021).
* K. Ashihara, T. Kajiwara, Y. Arase and S. Uchida: Contextualized context2vec, in Proc. of Workshop on Noisy User-generated Text (W-NUT 2019), pp. 397–406 (Nov. 2019).
* D. Nishihara, T. Kajiwara, and Y. Arase: Controllable Text Simplification with Lexical Constraint, in Proc. of Annual Meeting of the Association for Computational Linguistics: Student Research Workshop, pp. 260-266, (July 2019).
* S. Uchida, S. Takada and Y. Arase: CEFR-based Lexical Simplification Dataset, in Proc. of Language Resources and Evaluation Conference (LREC 2018), (May 2018).
* K. Sakaguchi, Y. Arase, and M. Komachi: Discriminative Approach to Fill-in-the-blank Quiz Generation for Language Learners, in Proc. of Annual Meeting of the Association for Computational Linguistics (ACL 2013), pp. 238-242 (Aug. 2013).

##### Datasets
* [CEFR-LP: CEFR-based lexical substitution dataset](../share/CEFR-LP.zip)
* [CEFR-LS: CEFR-based lexical simplification dataset](../share/lex-simplification.zip)