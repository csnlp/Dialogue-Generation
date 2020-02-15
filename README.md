This repository is to document the papers focusing on dialogue generation. I will also include their code implementation if possible. 

# Contents
   * [Contents](#contents)
   * [Open-Domain Dialogue Generation](#open-domain-dialogue-generation)
      * [Open-Domain Dialogue Datasets](#open-domain-dialogue-datasets)
      * [Seq2Seq Model for Dialogue Generation](#seq2seq-model-for-dialogue-generation)
      * [Reinforcement Learning Approaches for Dialogue Generation](#reinforcement-learning-approaches-for-dialogue-generation)
      * [Adversarial Learning Approaches for Dialogue Generation](#adversarial-learning-approaches-for-dialogue-generation)
      * [Context-aware Dialogue Generation:Hierarchy Methods](#context-aware-dialogue-generationhierarchy-methods)
      * [Evaluation Methods](#evaluation-methods)
      * [Papers about The Safe Response Problem](#papers-about-the-safe-response-problem)
      * [Curriculum Learning Approaches](#curriculum-learning-approaches)
      * [Incorporate External Knowledge into Dialogue Generation](#incorporate-external-knowledge-into-dialogue-generation)
   * [Task-oriented Dialogue Generation](#task-oriented-dialogue-generation)
      * [Datasets for Task-oriented Dialogue Systems](#datasets-for-task-oriented-dialogue-systems)
      * [Multi-Domain Dialogue Generation](#multi-domain-dialogue-generation)
   * [Academic Conferences and Workshops](#academic-conferences-and-workshops)


# Open-Domain Dialogue Generation

## Open-Domain Dialogue Datasets
1. The Ubuntu Dialogue Corpus, SIGDIAL: [paper](https://www.aclweb.org/anthology/W15-4640/), [dataset](http://dataset.cs.mcgill.ca/ubuntu-corpus-1.0/)
2. Cornell Movie Dialogs Corpus, [dataset](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
3. A Survey Paper about Datasets of Collection from McGill & UdeM, [dataset](https://breakend.github.io/DialogDatasets/)
4. NLPCC 2017(chinese): Emotional Dialogue Generation, [datasets](http://tcci.ccf.org.cn/conference/2017/dldoc/taskgline04.pdf)
5. OpenSubtitles2016: Extracting Large Parallel Corpora from Movie and TV Subtitles, LREC 2016. [paper](https://www.aclweb.org/anthology/L16-1147.pdf), [dataset](http://opus.nlpl.eu/OpenSubtitles-v2016.php)
6. DailyDialog, IJCNLP. [paper](https://www.aclweb.org/anthology/I17-1099.pdf), [dataset](http://yanran.li/dailydialog) 
7. Twitter Customer Service. [dataset](https://www.kaggle.com/thoughtvector/customer-support-on-twitter)
8. Douban Corpus(chinese), ACL 2017. [dataset](https://github.com/MarkWuNLP/MultiTurnResponseSelection), [paper](https://www.aclweb.org/anthology/P17-1046.pdf)

## Seq2Seq Model for Dialogue Generation
Actually, almost all of the existing generative approach use the Seq2Seq model. 
1. Neural Responding Machine for Short-Text Conversation, ACL 2015. [paper](https://www.aclweb.org/anthology/P15-1152.pdf).
2. A Neural Conversational Model, arxiv. [paper](http://pub-tools-public-publication-data.storage.googleapis.com/pdf/44925.pdf)

## Personalized Dialogue Generation
1. A Pre-training Based Personalized Dialogue Generation Model with Persona-sparse Data, AAAI 2020. [paper](https://arxiv.org/pdf/1911.04700.pdf)
2. 

## Reinforcement Learning Approaches for Dialogue Generation
1. Deep Reinforcement Learning for Dialogue Generation, [paper](https://www.aclweb.org/anthology/D16-1127.pdf)
2. Hierarchical Reinforcement Learning for Open-Domain Dialog, AAAI 2020. [paper](https://arxiv.org/pdf/1909.07547.pdf)

## Adversarial Learning Approaches for Dialogue Generation
1. Adversarial Learning for Neural Dialogue Generation, [paper](https://www.aclweb.org/anthology/D17-1230.pdf)


## Context-aware Dialogue Generation:Hierarchy Methods
1. A Hierarchical Recurrent Encoder-Decoder for Generative Context-Aware Query Suggestion, **the first HRED model**, CIKM 2015. [paper](http://hjemmesider.diku.dk/~kwn804/publications/CIKM15.pdf)
2. Building End-To-End Dialogue Systems Using Generative Hierarchical Neural Network Models, *the famous HRED model*.  [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11957/12160).
3. A Hierarchical Latent Variable Encoder-Decoder Model for Generating Dialogues, *VHRED model*, AAAI 2017. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14567/14219).
4. Hierarchical Variational Memory Network for Dialogue Generation,WWW 2018. [paper](https://dl.acm.org/doi/abs/10.1145/3178876.3186077)

## Evaluation Methods
1. How NOT To Evaluate Your Dialogue System: An Empirical Study of Unsupervised Evaluation Metrics for Dialogue Response Generation, **A empirical study**. [paper](https://www.aclweb.org/anthology/D16-1230.pdf)
2. Predictive Engagement: An Efficient Metric for Automatic Evaluation of Open-Domain Dialogue Systems, AAAI 2020. [paper](https://arxiv.org/pdf/1911.01456.pdf).
3. Learning from Easy to Complex: Adaptive Multi-curricula Learning for Neural Dialogue Generation, AAAI 2020. 

## Papers about The Safe Response Problem
1. A Diversity-Promoting Objective Function for Neural Conversation Models(*MMI*), NAACL-HLT 2016. [paper](https://www.aclweb.org/anthology/N16-1014.pdf)
2. Learning Discourse-level Diversity for Neural Dialog Models using Conditional Variational Autoencoders, ACL 2017. [paper](https://www.aclweb.org/anthology/P17-1061.pdf)
3. Topic Aware Neural Response Generation, AAAI 2017. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16455/15753) 
4. Generating Informative and Diverse Conversational Responses via Adversarial Information Maximization, NIPS 2018. [paper](http://papers.neurips.cc/paper/7452-generating-informative-and-diverse-conversational-responses-via-adversarial-information-maximization.pdf)

## Curriculum Learning Approaches
1. Learning from Easy to Complex: Adaptive Multi-curricula Learning for Neural Dialogue Generation, AAAI 2020. 

## Incorporate External Knowledge into Dialogue Generation
1. Improving Knowledge-aware Dialogue Generation via Knowledge Base Question Answering, AAAI 2020. [paper](https://arxiv.org/pdf/1912.07491.pdf)

# Task-oriented Dialogue Generation

## Datasets for Task-oriented Dialogue Systems
1. FRAMES Corpus. [paper](https://www.aclweb.org/anthology/W17-5526v2.pdf), [dataset](https://www.microsoft.com/en-us/research/project/frames-dataset/#!download)
2. Towards Scalable Multi-Domain Conversational Agents: The Schema-Guided Dialogue Dataset, AAAI 2020. [paper](https://arxiv.org/pdf/1909.05855.pdf). **A large dataset containing over 16k multi-domain conversations spanning 16 domains.**

## Multi-Domain Dialogue Generation
1. MALA: Cross-Domain Dialogue Generation with Action Learning, AAAI 2020. [paper](https://arxiv.org/pdf/1912.08442.pdf)
2. 
## Others
1. End-to-End Trainable Non-Collaborative Dialog System, AAAI 2020. [paper](https://arxiv.org/pdf/1911.10742.pdf)
# Academic Conferences and Workshops
1. ACL 20xx
2. EMNLP 20xx
3. NAACL-HLT 20xx
4. COLING 20xx
5. SIGDIAL 20xx

