Dear Facebook AI Residency Recruiters!
 
I am so excited to have a chance to apply for the Facebook AI Residency program. Here I’d like to tell you more about me, some of my projects, my research interests and why I would like to participate in the AI Residency.
 
Having a specialist (bachelor + master) degree in Fundamental Mathematics with a major in Probability Theory, I always had a passion for research. Finding applied research most meaningful for me, I started my career as a research intern in the Biostatistics Laboratory National Institute for Medical Research working together with my university scientific adviser.
 
Later I joined the Hedge Fund and became a part of one of the most competitive research industry – algorithmic trading strategies research on the US Stock Market. It was a mix of research ideas generations, deep maths and high-quality coding.
 
In the Hedge Fund I mastered my skills in advocating my research, not giving up when you see that your several months of hard research does not work, and continuing to generate new research ideas.
 
With time passed I realized how important for me to collaborate with colleagues, having a debate and being able to share ideas. But unfortunately, all of this is not common practice in that industry. Also, I wanted to have a wider range of data to research. So, I moved to the Sberbank Modelling Research team.

In Sberbank my main research interest was related to Graph ML. One of the projects was Graph NN with the idea of predicting the probability of clients default by using not only personal clients purchases but information about their transfers. A huge (about 60M nodes) discrete-time dynamic social graph was built with bank clients as graph nodes and edges for clients with mutual transfers. The node attribute was the client’s purchases, edge attribute was the client's transfers. Combining ideas from GAT [1] and EGNN [2], an architecture was proposed that used node and edge features; it outperformed both GAT and EGNN. This architecture shows the best result in end-to-end training mode and the result significantly outperformed the existed probability of the default model.

Another project was to do semi-supervised clustering of Russian Economy. Russian companies were presented as a heterogeneous (knowledge) graph with more than 40 types of connections. Working on this project I had a chance to research in-depth graph embedding techniques. The general pipeline was first of all to extract graph nodes embeddings, then to cluster them. I used several approaches to extract embeddings from the heterogeneous graph. For embeddings in Euclidean space I used slightly modified ideas from DeepWalk [3] of Node2Vec [4]. I was admired by Maximilian Nickel and Douwe Kiela’s idea [5] to put embeddings to Poincare space. Also, I used ComplEx and TransE algorithms implemented in PyTorchBigGraph [6]. Thank you, Facebook Research team, for adding GPU training support for this library! I suffered from training it on the CPU. For extracted embeddings clustering I used dimension reduction if required, and then HDBSCAN [7] clustering algorithm.
 
I also have experience in NLP: I developed the text messages classification and real-time clustering using Siamese Neural Network in Sberbank; and news analyses using GRU and Attention in Hedge Fund.
 
My main research interests lay in Graph ML. In particular I am interested in dynamic graph applications when both graph typology and edges/nodes embeddings change over continuous time. A good example of it is the recently published TIES model [8] with applications for preventing spread of misinformation and fake account detection to enhance Facebook platform’s integrity. Another promising direction is Graph Representation Limits with series of works establishing the connection between GNN and graph isomorphism, the Weisfeiler-Lehman test, with the most recent paper proposed GSN architecture [9] strictly more powerful than 2-WL and also more powerful than standard message passing GNN.
Also, there are a lot of interesting subjects for me to research both in NLP and Graph ML.
 
One more subject I would like to touch: the recent paper [10] with a very strong title shows that the combination of Label Propagation and MLP outperforms the performance of state-of-the-art GNNs. Despite the fact that the result was reached only on a transductive homophily graph, this important paper unintentionally points to the lack of high quality Graph ML benchmarks. Having a good foundation with OGB, I hope with the IT corporations’ contributions it soon will be enriched by more complex and large graph datasets.
 
I am looking forward to seeing soon the same breakthrough in Graph ML as was in NLP and CV. I am definitely passionate about this subject and would be happy to have an opportunity to contribute to this research. I hope to find great colleagues and advisers in the Facebook Research team and hope to master how to conduct proper ML research. In collaboration with the Facebook Research team I wish to make a feasible research contribution for Facebook and the whole ML community.
 
 
 
[1] Petar Velickovic, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, and Yoshua Bengio. 2018. Graph Attention Networks.
[2] Liyu Gong and Qiang Cheng. 2018. Exploiting Edge Features for Graph Neural Networks.
[3] Aditya Grover and Jure Leskovec. 2016. node2vec: Scalable feature learning for networks.
[4] Bryan Perozzi, Rami Al-Rfou, and Steven Skiena. Deepwalk: Online learning of social representations.
[5] Nickel, M. and Kiela, D. (2017). Poincare embeddings ´ for learning hierarchical representations.
[6] Adam Lerer, Ledell Wu, Jiajun Shen, Timothee Lacroix, Luca Wehrstedt, Abhijit Bose, and Alex Peysakhovich. Pytorch-biggraph: A large-scale graph embedding system.
[7] Campello R.J.G.B., Moulavi D., Sander J. (2013) Density-Based Clustering Based on Hierarchical Density Estimates.
[8] M. Noorshams, S. Verma, and A. Hofleitner, TIES: Temporal Interaction Embeddings for enhancing social media integrity at Facebook (2020).
[9] Giorgos Bouritsas, Fabrizio Frasca, Stefanos Zafeiriou, and Michael M Bronstein. Improving graph neural network expressivity via subgraph isomorphism counting
[10] Qian Huang, Horace He, Abhay Singh, Ser-Nam Lim, and Austin R Benson. Combining label propagation and simple models out-performs graph neural networks.

