# Dampier Lab Computational Journal Club

Welcome to the Computational Journal Club at Drexel University College of Medicine.

## Upcoming

| Date | Title | Link | Presenter |
|------|-------|------|-------|
| 03/29/2019 | Deep learning enables accurate clustering a 1 nd batch effect removal in single-cell RNA-seq analysis | [Biorxiv](https://www.biorxiv.org/content/biorxiv/early/2019/01/25/530378.full.pdf) | Robert Link |
| 03/01/2019 | Identification and localization of Sea Lion anatomical features using transfer learning |  | Will Dampier | 
| TBD | TBD | TBD |  |
| TBD | Privacy-preserving generative deep neural networks support clinical data sharing | [BioArxiv](https://www.biorxiv.org/content/early/2017/11/15/159756) | Jessica Eager | 
| TBD | TBD | TBD |  |
| TBD | DeepGO: predicting protein functions from sequence and interactions using a deep ontology-aware classifier | [iSCB](https://academic.oup.com/bioinformatics/article/34/4/660/4265461) | Angela Tomita |


## Archive

* [**Generative Models**](#generative-models)
* [**CRISPR/Cas9**](#crisprcas9)
* [**Gene Expression**](#xgene-expression)
* [**Gene Ontology**](#gene-ontology)

| Date | Paper | Link | Presenter |
|------|-------|------|-------|
| 02/08/19 |GOATOOLS: A Python library for Gene Ontology analyses|[Scientific Reports](https://www.nature.com/articles/s41598-018-28948-z.pdf)| [DV Klopfenstein](slidedecks/2019-02-08-GOEA/Klopfenstein-2018.ipynb) | 
| 02/01/19 | Predicting the mutations generated by repair of Cas9-induced double-strand breaks |[Nature Biotechniques](https://www.ncbi.nlm.nih.gov/pubmed/?term=30480667)| [Will Dampier](slidedecks/2019-02-01-crispr-edits/Allen-2018.ipynb) | 
| 01/25/19 | dna2vec: Consistent vector representations of variable-length k-mers; Continuous Distributed Representation of Biological Sequences for Deep Proteomics and Genomics | [arxiv](https://arxiv.org/pdf/1701.06279.pdf) [arxiv](https://arxiv.org/ftp/arxiv/papers/1503/1503.05140.pdf) | [Angela Tomita](slidedecks/2019-01-25-sequence-embedding/embedding.ipynb) |
| 01/18/19 | Predicting mRNA abundance directly from genomic sequence using deep convolutional neural networks | [BioArxiv](https://www.biorxiv.org/content/biorxiv/early/2018/10/12/416685.full.pdf) |  [Robert Link](slidedecks/2019-01-18-Xpresso/2019_01_18_Xpresso.ipynb) | 
| 01/11/19 | Synergizing CRISPR/Cas9 Off-Target Predictions for Ensemble Insights and Practical Applications | [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/30169558) | [Cheng-Han Chung](slidedecks/2019-01-11-crispr-ensemble/Zhang-2018June.ipynb) |
| 11/16/18 | Generating and designing DNA with deep generative models | [Arxiv](https://arxiv.org/abs/1712.06148) | [Will Dampier](slidedecks/2018-11-16-generative-dna/Killoran-2017.ipynb) | 



### Generative Models

#### Generating and designing DNA with deep generative models [[Arxiv](https://arxiv.org/abs/1712.06148)]
Nathan Killoran, Leo J. Lee, Andrew Delong, David Duvenaud, Brendan J. Frey 

An exploration of a GANN architecture for creating novel DNA segments. The paper explores the biological nature of model. It has abiity to replicate complementarity. It has smooth transitions in sequence-space when interpolating in Z-space. They then explore applications for this in designing DNA probes with idealized binding properties.

Presented by Will Dampier. [Slides](slidedecks/2018-11-16-generative-dna/Killoran-2017.ipynb)

### CRISPR/Cas9

#### Predicting off-target cleavage sites using ensemble learning with scoring matrices.
Shixiong Zhang, Xiangtao Li, Qiuzhen Lin and Ka-Chun Wong

A basic benchmark of prediction ability among classification algorithms and combinations of them. The ensemble model using CFD, MIT, MIT Website score, Cropit and CCTop altogether had the highest AUC-ROC and AUC-PRC. 

Presented by Cheng-Han Chung. [Slides](slidedecks/2019-01-11-crispr-ensemble/Zhang-2018June.ipynb)

#### Predicting the mutations generated by repair of Cas9-induced double-strand breaks.
Felicity Allen, Luca Crepaldi, Clara Alsinet, Alexander J. Strong, Vitalii Kleshchevnikov, Pietro De Angeli, Petra Páleníková, Anton Khodak, Vladimir Kiselev, Michael Kosicki, Andrew R. Bassett, Heather Harding, Yaron Galanty, Francisco Muñoz-Martínez, Emmanouil Metzakopian, Stephen P. Jackson & Leopold Parts.

This paper discusses how the gRNA and target influence the type and distribution of Cas9 editing outcomes. They use a clever plasmid system to measure the editing consequences at scale. The authors find that these editing profiles are repoducible within the same gRNA, diverse across different gRNAs, and are predictable when the target sequence is known.

Presented by Will Dampier. [Slides](slidedecks/2019-02-01-crispr-edits/Allen-2018.ipynb)


### Gene Expression

#### Predicting mRNA abundance directly from genomic sequence using deep convolutional neural networks. [BioArxiv](https://www.biorxiv.org/content/biorxiv/early/2018/10/12/416685.full.pdf)
Vikram Agarwal & Jay Shendure

A convolutional neural network (CNN) designed to predict mRNA steady-state abundance from promoter sequence and mRNA half-life proxy. It explains 59% of the variation in expression for humans and 71% of the expression for mice, more than doubling the performance accuracy of previous models attempting to explain transcription. 

Presented by Robert Link. [Slides](slidedecks/2019-01-18-Xpresso/2019_01_18_Xpresso.ipynb)

### Embedding - word2vec-based encodings for biological sequences

#### dna2vec: Consistent vector representations of variable-length k-mers.
Patrick Ng

#### Continuous Distributed Representation of Biological Sequences for Deep Proteomics and Genomics
Ehsaneddin Asgari, Mohammad R. K. Mofrad

Embeddings are popular in the deep learning community as inputs to models, and these two specific tools are designed for processing and representing dna/protein sequences. The vector arithmetic for dna2vec representations is analogous to nucleotide concatenation using (Spearman = 0.831), and ProtVec protein classification accuracy is 93%.

Presented by Angela Tomita. [Slides](slidedecks/2019-01-25-sequence-embedding/embedding.ipynb)

### Gene Ontology

#### GOATOOLS: A Python library for Gene Ontology analyses. [Scientific Reports](https://www.nature.com/articles/s41598-018-28948-z.pdf)
D. V. Klopfenstein, Liangsheng Zhang, Brent S. Pedersen, Fidel Ramírez, Alex Warwick Vesztrocy, Aurélien Naldi, Christopher J. Mungall, Jeffrey M. Yunes, Olga Botvinnik, Mark Weigel, Will Dampier, Christophe Dessimoz, Patrick Flick, Haibao Tang

Gene Ontology (GO) is used to describe gene products in a computationally acessible manner. This paper describes a Python library and a set of scripts used to query the GO, run enrichment analyses on sets of genes, and describes a novel method for grouping GO terms.

Presented by DV Klopfenstein. [Slides](slidedecks/2019-02-08-GOEA/Klopfenstein-2018.ipynb)

Copyright 2018-2019, Dampier Lab. All rights reserved.
