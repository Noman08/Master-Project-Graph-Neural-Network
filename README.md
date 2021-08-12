# Final Prototype of ML Master Project

# Project Goal and achievement
Initially our goal was to participate in the KDD Cup. The task of the KDD Cup was to build a model for Node Classification based on MAG240M-LSC (200 GB) Dataset. Due to hardware limitations and some issues in the Deep Graph Library, we forfeit the idea of participate in the KDD Cup. Although we would love to compete in the KDD Cup, we did not foresee the challenge of handling extremely large dataset.  

Then we shifted our focus on OGBN-MAG (1GB) dataset. The task was to predict the venue (conference or journal) of each paper, given its content, references, authors, and authors’ affiliations. Though this dataset was not quite as large as the previous one, but both dataset are closely resembled. We worked with RGCN and HAN model. Regarding RGCN, we concentrated with two varient a) Prefilling missing feature with zero value b) Featureless Embedding. We also did experiment with HAN model. However we also encountred the same difficulties regarding resources limitation and DGL issue like previous dataset. Our RGCN Model variant with Prefilling missing feature achieved 28% test accuracy.

Finally, we worked with ACM Dataset. The task was to predict the conference of a paper. Compared to two previous dataset, here we achieved fairly good results. We wrote two models, a) RGCN (Featureless embedding) b) HAN with 2 meta path. Both models achieved more than 85% test accuracy.  

