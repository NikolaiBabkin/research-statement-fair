Dear Facebook AI Residency Recruiters!
 
I am so excited to have a chance to apply for the Facebook AI Residency program. Here I’d like to tell you more about me, some of my projects, my research interests and why I would like to participate in the AI Residency.
 
Having a specialist (bachelor + master) degree in Fundamental Mathematics with a major in Probability Theory, I always had a passion for research. Finding applied research most meaningful for me, I started my career as a research intern in the Biostatistics Laboratory National Institute for Medical Research working together with my university scientific adviser.
 
Later I joined the Hedge Fund and became a part of one of the most competitive research industry – algorithmic trading strategies research on the US Stock Market. It was a mix of research ideas generations, deep maths and high-quality coding.
 
In the Hedge Fund I mastered my skills in advocating my research, not giving up when you see that your several months of hard research does not work, and continuing to generate new research ideas.
 
With time passed I realized how important for me to collaborate with colleagues, having a debate and being able to share ideas. But unfortunately, all of this is not common practice in that industry. Also, I wanted to have a wider range of data to research. So, I moved to the Sberbank Modelling Research team.

In Sberbank my main research interest was related to Graph ML. One of the projects was Graph NN with the idea of predicting the probability of clients default by using not only personal clients purchases but information about their transfers. A huge (about 60M nodes) discrete-time dynamic social graph was built with bank clients as graph nodes and edges for clients with mutual transfers. The node attribute was the client’s purchases, edge attribute was the client's transfers. Combining ideas from GAT [[1]](#1) and EGNN [[2]](#2), an architecture was proposed that used node and edge features; it outperformed both GAT and EGNN. This architecture shows the best result in end-to-end training mode and the result significantly outperformed the existed probability of the default model.

Another project was to do semi-supervised clustering of Russian Economy. Russian companies were presented as a heterogeneous (knowledge) graph with more than 40 types of connections. Working on this project I had a chance to research in-depth graph embedding techniques. The general pipeline was first of all to extract graph nodes embeddings, then to cluster them. I used several approaches to extract embeddings from the heterogeneous graph. For embeddings in Euclidean space I used slightly modified ideas from DeepWalk [[3]](#3) of Node2Vec [[4]](#4). I was admired by Maximilian Nickel and Douwe Kiela’s idea [[5]](#5) to put embeddings to Poincare space. Also, I used ComplEx and TransE algorithms implemented in PyTorchBigGraph [[6]](#6). Thank you, Facebook Research team, for adding GPU training support for this library! I suffered from training it on the CPU. For extracted embeddings clustering I used dimension reduction if required, and then HDBSCAN [[7]](#7) clustering algorithm.
 
I also have experience in NLP: I developed the text messages classification and real-time clustering using Siamese Neural Network in Sberbank; and news analyses using GRU and Attention in Hedge Fund.
 
My main research interests lay in Graph ML. In particular I am interested in dynamic graph applications when both graph typology and edges/nodes embeddings change over continuous time. A good example of it is the recently published TIES model [[8]](#8) with applications for preventing spread of misinformation and fake account detection to enhance Facebook platform’s integrity. Another promising direction is Graph Representation Limits with series of works establishing the connection between GNN and graph isomorphism, the Weisfeiler-Lehman test, with the most recent paper proposed GSN architecture [[9]](#9) strictly more powerful than 2-WL and also more powerful than standard message passing GNN.
Also, there are a lot of interesting subjects for me to research both in NLP and Graph ML.
 
One more subject I would like to touch: the recent paper [10] with a very strong title shows that the combination of Label Propagation and MLP outperforms the performance of state-of-the-art GNNs. Despite the fact that the result was reached only on a transductive homophily graph, this important paper unintentionally points to the lack of high quality Graph ML benchmarks. Having a good foundation with [OGB](https://ogb.stanford.edu/), I hope with the IT corporations’ contributions it soon will be enriched by more complex and large graph datasets.
 
I am looking forward to seeing soon the same breakthrough in Graph ML as was in NLP and CV. I am definitely passionate about this subject and would be happy to have an opportunity to contribute to this research. I hope to find great colleagues and advisers in the Facebook Research team and hope to master how to conduct proper ML research. In collaboration with the Facebook Research team I wish to make a feasible research contribution for Facebook and the whole ML community.
 
 


### References
<a id="1">[1]</a> 
[Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, & Yoshua Bengio. (2018). Graph Attention Networks.](https://arxiv.org/abs/1710.10903)

<a id="2">[2]</a> 
[Liyu Gong, & Qiang Cheng. (2019). Exploiting Edge Features in Graph Neural Networks.](https://arxiv.org/abs/1809.02709)

<a id="3">[3]</a> 
[Perozzi, B., Al-Rfou, R., & Skiena, S. (2014). DeepWalkProceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining.](https://arxiv.org/abs/1403.6652)

<a id="4">[4]</a> 
[Aditya Grover, & Jure Leskovec. (2016). node2vec: Scalable Feature Learning for Networks.](https://arxiv.org/abs/1607.00653)

<a id="5">[5]</a> 
[Maximilian Nickel, & Douwe Kiela. (2017). Poincaré Embeddings for Learning Hierarchical Representations.](https://arxiv.org/abs/1705.08039)


<a id="6">[6]</a> 
[Adam Lerer, Ledell Wu, Jiajun Shen, Timothee Lacroix, Luca Wehrstedt, Abhijit Bose, & Alex Peysakhovich. (2019). PyTorch-BigGraph: A Large-scale Graph Embedding System.](https://arxiv.org/abs/1903.12287)

<a id="7">[7]</a> 
[Campello R.J.G.B., Moulavi D., Sander J. (2013) Density-Based Clustering Based on Hierarchical Density Estimates. In: Pei J., Tseng V.S., Cao L., Motoda H., Xu G. (eds) Advances in Knowledge Discovery and Data Mining. PAKDD 2013. Lecture Notes in Computer Science, vol 7819. Springer, Berlin, Heidelberg. https://doi.org/10.1007/978-3-642-37456-2_14](https://link.springer.com/chapter/10.1007/978-3-642-37456-2_14)

<a id="8">[8]</a>
[Nima Noorshams, Saurabh Verma, & Aude Hofleitner. (2020). TIES: Temporal Interaction Embeddings For Enhancing Social Media Integrity At Facebook.](https://arxiv.org/abs/2002.07917)


<a id="9">[9]</a>
[Giorgos Bouritsas, Fabrizio Frasca, Stefanos Zafeiriou, & Michael M. Bronstein. (2021). Improving Graph Neural Network Expressivity via Subgraph Isomorphism Counting.](https://arxiv.org/abs/2006.09252)

<a id="10">[10]</a>
[Qian Huang, Horace He, Abhay Singh, Ser-Nam Lim, & Austin R. Benson. (2020). Combining Label Propagation and Simple Models Out-performs Graph Neural Networks.](https://arxiv.org/abs/2010.13993)

