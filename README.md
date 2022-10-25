# Cross-lingual learning

**Syllabus**\
**WS 22/23**

Instructor: Mareike Hartmann (mareikeh@lst.uni-saarland.de) \
Meetings: Thursdays 14:15 - 15:45, C7.1 Room U15 \
Office Hours: by appointment \
\
Cross-lingual learning is a form of transfer learning, and refers to methods which learn from a task in one language and transfer this knowledge to a task in another language, which is particularly helpful to solve tasks in languages with few training resources. In this seminar, we will discuss different methods for cross-lingual learning, focusing on transfer via multilingual word embeddings and pre-trained multilingual language models, and cover recent applications for cross-lingual transfer.\
\
**Prerequisites:** Background in natural language processing and deep learning is required.\
\
**Topics and papers to be discussed:**\

| **Topic**  | **Readings** |

| Multilingual word embeddings  | Mikolov et al. (2013b): [Exploiting Similarities among Languages for Machine Translation](https://arxiv.org/pdf/1309.4168.pdf) <br /> Faruqui and Dyer (2014b): [Improving Vector Space Word Representations Using Multilingual Correlation](https://aclanthology.org/E14-1049.pdf) <br /> Mrkšić et al. (2017): [Semantic Specialization of Distributional Word Vector Spaces using Monolingual and Cross-Lingual Constraints](https://aclanthology.org/Q17-1022.pdf) <br /> <br /> **Additional background material:** <br /> Ruder et al. (2019): [A Survey of Cross-lingual Word Embedding Models](https://jair.org/index.php/jair/article/view/11640/26511)|

| Inducing multilingual word embeddings from comparable data  | Bergsma and van Durme (2011): [Learning Bilingual Lexicons Using the Visual Similarity of Labeled Web Images](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI11/paper/view/3239/3743) <br /> Kiela et al. (2015): [Visual Bilingual Lexicon Induction with Transferred ConvNet Features](https://aclanthology.org/D15-1015.pdf)<br /> Rapp (1999): [Automatic Identification of Word Translations from Unrelated English and German](https://aclanthology.org/P99-1067.pdf)|

| Multilingual word embeddings: Unsupervised approache  | Conneau et al. (2018): [Word translation without parallel data](https://openreview.net/pdf?id=H196sainb)<br /> Artetxe et al. (2018): [A robust self-learning method for fully unsupervised cross-lingual mappings of word embeddings](https://aclanthology.org/P18-1073.pdf)<br /> Søgaard et al. (2019): [On the Limitations of Unsupervised Bilingual Dictionary Induction](https://aclanthology.org/P18-1072.pdf)|

| Evaluating multilingual word embeddings | Upadhyay et al. (2016): [Cross-lingual Models of Word Embeddings: An Empirical Comparison](https://aclanthology.org/P16-1157.pdf)<br /> Glavaš et al. (2019): How to (Properly) Evaluate Cross-Lingual Word Embeddings: On Strong Baselines, Comparative Analyses, and Some Misconceptions](https://aclanthology.org/P19-1070.pdf)|

| Transformer-based multilingual language models | Conneau and Lample (2019): [Cross-lingual Language Model Pretraining](https://proceedings.neurips.cc/paper/2019/file/c04c19c2c2474dbf5f7ac4372c5b9af1-Paper.pdf)<br /> Conneau et al. (2020): [Unsupervised Cross-lingual Representation Learning at Scale](https://aclanthology.org/2020.acl-main.747.pdf) |

| Cross-lingual effectiveness of multilingual language models | Wu and Dredze (2019): [Beto, Bentz, Becas: The Surprising Cross-Lingual Effectiveness of BERT](https://aclanthology.org/D19-1077.pdf)<br /> Pires et al. (2019): [How Multilingual is Multilingual BERT?](https://aclanthology.org/P19-1493.pdf)|

|  Essential elements for multilinguality|   Karthikeyan et al. (2020): [Cross-Lingual Ability of Multilingual BERT: An Empirical Study](https://openreview.net/pdf?id=HJeT3yrtDr) <br /> Dufter and Schütze (2020): [Identifying Elements Essential for BERT’s Multilinguality](https://aclanthology.org/2020.emnlp-main.358.pdf)<br /> Conneau et al. (2020): [Emerging Cross-lingual Structure in Pretrained Language Models](https://aclanthology.org/2020.acl-main.536.pdf)<br /> Muller et al. (2021): [First Align, then Predict: Understanding the Cross-Lingual Ability of Multilingual BERT](https://aclanthology.org/2021.eacl-main.189.pdf)<br /> Lin et al. (2019): [Choosing Transfer Languages for Cross-Lingual Learning
](https://aclanthology.org/P19-1301.pdf)|

| Seq2seq multilingual language models | Xue et al. (2021): [mT5: A Massively Multilingual Pre-trained Text-to-Text Transformer](https://aclanthology.org/2021.naacl-main.41.pdf)<br /> Chi et al. (2021): [mT6: Multilingual Pretrained Text-to-Text Transformer with Translation Pairs](https://aclanthology.org/2021.emnlp-main.125.pdf) |

|  Limitations of multilingual language models|  Lauscher et al. (2020): [From Zero to Hero: On the Limitations of Zero-Shot Language Transfer with Multilingual Transformers](https://aclanthology.org/2020.emnlp-main.363.pdf) <br /> Wu and Dredze (2020): [Are All Languages Created Equal in Multilingual BERT?
](https://aclanthology.org/2020.repl4nlp-1.16.pdf)|

|  Benchmarks for evaluating cross-lingual transfer| Hu et al. (2020): [XTREME: A Massively Multilingual Multi-task Benchmark for Evaluating Cross-lingual Generalisation](https://proceedings.mlr.press/v119/hu20b.html)<br /> Liang et al. (2020): [XGLUE: A New Benchmark Dataset for Cross-lingual Pre-training, Understanding and Generation](https://aclanthology.org/2020.emnlp-main.484.pdf)<br /> Ruder et al. (2021): [XTREME-R: Towards More Challenging and Nuanced Multilingual Evaluation](https://aclanthology.org/2021.emnlp-main.802.pdf)|

| Applications for cross-lingual transfer learning | de Vries et al (2022): [Make the Best of Cross-lingual Transfer: Evidence from POS Tagging with over 100 Languages](https://aclanthology.org/2022.acl-long.529.pdf)<br /> Riabi et al. (2021): [Synthetic Data Augmentation for Zero-Shot Cross-Lingual Question Answering](https://aclanthology.org/2021.emnlp-main.562.pdf)<br />Perez-Beltrachini and Lapata (2021): [Models and Datasets for Cross-Lingual Summarisation](https://aclanthology.org/2021.emnlp-main.742.pdf)<br />Kondratyuk and Straka (2019): [75 Languages, 1 Model: Parsing Universal Dependencies Universally](https://aclanthology.org/D19-1279.pdf)<br />Müller-Eberstein et al. (2021): [Genre as Weak Supervision for Cross-lingual Dependency Parsing](https://aclanthology.org/2021.emnlp-main.393.pdf)<br />Zhang et al. (2021): [On the Benefit of Syntactic Supervision for Cross-lingual Transfer in Semantic Role Labeling](https://aclanthology.org/2021.emnlp-main.503.pdf)<br /> Chen et al. (2021): [Zero-Shot Cross-Lingual Transfer of Neural Machine Translation with Multilingual Pretrained Encoders](https://aclanthology.org/2021.emnlp-main.2.pdf)|




