# DeepGAR
Analogical reasoning is the process of discovering and mapping correspondences from a target subject to a base subject. As the most well-known computational method of analogical reasoning, Structure-Mapping Theory (SMT) abstracts both target and base subjects into relational graphs and forms the cognitive process of analogical reasoning as finding a corresponding subgraph (i.e., correspondence) in the target graph that is aligned with the base graph. To enhance the generalization of Analogical Reasoning, we can adapt SMT for artificial intelligence. However, incorporating deep learning for SMT is still under-explored due to several obstacles: 1) the combinatorial complexity of searching for the correspondence in the target graph; 2) the correspondence mining is restricted by various cognitive theory-driven constraints; and 3) the hardness of attaining the correspondence directly by an objective function. To address these challenges, we propose a novel framework of Deep Graph Learning for Analogical Reasoning (DeepGAR) that identifies the correspondence between source and target domains by assuring cognitive theory-driven constraints. Specifically, we design a geometric constraint embedding space to induce subgraph relation from node embeddings for efficient subgraph search. Furthermore, we develop novel learning and optimization strategies that could end-to-end identify correspondences that are strictly consistent with constraints driven by the cognitive theory. Extensive experiments are conducted on synthetic and real-world datasets to demonstrate the effectiveness of the proposed DeepGAR over existing methods.

## Links
Paper: Chowdhury, Tanmoy, Yuyang Gao, and Liang Zhao. "Deep Multi-task Learning for Spatio-Temporal Incomplete Qualitative Event Forecasting." Submitted on IEEE Transactions on Knowledge and Data Engineering. At the second stage of revision.

## Instructions:
The code has been tested under Pytorch 1.8

To test the code, simply run the following command  
```
cd <submission>
python deepgar.py
```

## Citation
If you use this work, please cite the following paper:

Ling, Chen, Tanmoy Chowdhury, Junji Jiang, Junxiang Wang, Xuchao Zhang, Haifeng Chen, and Liang Zhao. "Deepgar: Deep graph learning for analogical reasoning." In 2022 IEEE International Conference on Data Mining (ICDM), pp. 1065-1070. IEEE, 2022.
