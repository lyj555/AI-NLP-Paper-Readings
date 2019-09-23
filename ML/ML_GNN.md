# ML - Graph Neural Network (GNN)
|Paper|Conference|Remarks
|--|--|--|
|[The Emerging Field of Signal Processing on Graphs](https://ieeexplore.ieee.org/document/6494675)|IEEE Signal Processing Magazine 2013|1. Outline the main challenges of the area, discuss different ways to define graph spectral domains, which are the analogs to the classical frequency domain, and highlight the importance of incorporating the irregular structures of graph data domains when processing signals on graphs. 2. Review methods to generalize fundamental operations such as filtering, translation, modulation, dilation, and downsampling to the graph setting and survey the localized, multiscale transforms that have been proposed to efficiently extract information from high-dimensional data on graphs.|
|[Spectral Networks and Locally Connected Networks on Graphs](https://arxiv.org/abs/1312.6203)|ICLR 2014|1. Consider possible generalizations of CNNs to signals defined on more general domains without the action of a translation group. 2. Propose two constructions, one based upon a hierarchical clustering of the domain, and another based on the spectrum of the graph Laplacian. 3. Show that for low-dimensional graphs it is possible to learn convolutional layers with a number of parameters independent of the input size, resulting in efficient deep architectures.|
|[Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering](https://arxiv.org/abs/1606.09375)|NIPS 2016|1. Present a formulation of CNNs in the context of spectral graph theory, which provides the necessary mathematical background and efficient numerical schemes to design fast localized convolutional filters on graphs. 2. The proposed technique offers the same linear computational complexity and constant learning complexity as classical CNNs, while being universal to any graph structure.|
|[Neural Message Passing for Quantum Chemistry](https://arxiv.org/abs/1704.01212)|ICML 2017|Reformulate existing GNN models into a single common framework we call Message Passing Neural Networks (MPNNs) and explore additional novel variations within this framework.|
|[Geometric deep learning: going beyond Euclidean data](https://arxiv.org/pdf/1611.08097)|Arxiv 2017|Overview different examples of geometric deep learning problems and present available solutions, key difficulties, applications, and future research directions in this nascent field.|
|[Graph Signal Processing - Overview, Challenges, and Applications](https://ieeexplore.ieee.org/document/8347162)|Proceedings of the IEEE 2018|1. Provide an overview of core ideas in GSP and their connection to conventional digital signal processing, along with a brief historical perspective to highlight how concepts recently developed in GSP build on top of prior research in other areas. 2. Summarize recent advances in developing basic GSP tools, including methods for sampling, filtering, or graph learning. 3. Review progress in several application areas using GSP, including processing and analysis of sensor network data, biological data, and applications to image processing and machine learning.|
|[GaAN: Gated Attention Networks for Learning on Large and Spatiotemporal Graphs](https://arxiv.org/abs/1803.07294)|UAI 2018|1. Propose a new network architecture, Gated Attention Networks (GaAN), for learning on graphs, which uses a convolutional sub-network to control each attention head's importance. 2. Construct the Graph Gated Recurrent Unit (GGRU) to address the traffic speed forecasting problem with GaAN as a building block.|
|[Graph Attention Networks](https://arxiv.org/abs/1710.10903)|ICLR 2018|1. Present graph attention networks (GATs), novel neural network architectures that operate on graph-structured data, leveraging masked self-attentional layers to address the shortcomings of prior methods based on graph convolutions or their approximations. 2. Enable (implicitly) specifying different weights to different nodes in a neighborhood, without requiring any kind of costly matrix operation (such as inversion) or depending on knowing the graph structure upfront.|
|[A Comprehensive Survey on Graph Neural Networks](https://arxiv.org/abs/1901.00596)|Arxiv 2018|1. Propose a new taxonomy to divide the state-of-the-art graph neural networks into four categories, namely recurrent graph neural networks, convolutional graph neural networks, graph autoencoders and spatial-temporal graph neural networks. 2. Discuss the applications of graph neural networks across various domains and summarize the open source codes and benchmarks of the existing algorithms on different learning tasks. Finally, we propose potential research directions in this rapidly growing field.|
|[Deep Learning on Graphs: A Survey](https://arxiv.org/abs/1812.04202)|Arxiv 2018|1. Divide existing methods into three main categories: semi-supervised methods including Graph Neural Networks and Graph Convolutional Networks, unsupervised methods including Graph Autoencoders, and recent advancements including Graph Recurrent Neural Networks and Graph Reinforcement Learning. 2. Provide a comprehensive overview of these methods in a systematic manner following their history of developments. 3. Analyze the differences of these methods and how to composite different architectures. 4. Briefly outline their applications and discuss potential future directions.|
|[Graph Neural Networks - A Review of Methods and Applications](https://arxiv.org/abs/1812.08434)|Arxiv 2018|Provide a detailed review over existing graph neural network models, systematically categorize the applications, and propose four open problems for future research.|
|[Relational inductive biases, deep learning, and graph networks](https://arxiv.org/abs/1806.01261)|Arxiv 2018|1. Explore how using relational inductive biases within deep learning architectures can facilitate learning about entities, relations, and rules for composing them. 2. Present a new building block for the AI toolkit with a strong relational inductive bias--the graph network--which generalizes and extends various approaches for neural networks that operate on graphs, and provides a straightforward interface for manipulating structured knowledge and producing structured behaviors. 3. Discuss how graph networks can support relational reasoning and combinatorial generalization, laying the foundation for more sophisticated, interpretable, and flexible patterns of reasoning.|
|[Attention Models in Graphs - A Survey](https://arxiv.org/abs/1807.07984)|Arxiv 2018|1. Conduct a comprehensive and focused survey of the literature on the emerging field of graph attention models. 2. Introduce three intuitive taxonomies to group existing work, which are based on problem setting (type of input and output), the type of attention mechanism used, and the task (e.g., graph classification, link prediction, etc.). 3. Motivate the taxonomies through detailed examples and use each to survey competing approaches from a unique standpoint.|
|[How Powerful are Graph Neural Networks?](https://arxiv.org/abs/1810.00826)|ICLR 2019|1. Present a theoretical framework for analyzing the expressive power of GNNs to capture different graph structures. 2. Characterize the discriminative power of popular GNN variants, such as Graph Convolutional Networks and GraphSAGE, and show that they cannot learn to distinguish certain simple graph structures. 3. Develop a simple architecture that is provably the most expressive among the class of GNNs and is as powerful as the Weisfeiler-Lehman graph isomorphism test. 4. Empirically validate the theoretical findings on a number of graph classification benchmarks, and demonstrate that the proposed model achieves state-of-the-art performance.|
|[LanczosNet: Multi-Scale Deep Graph Convolutional Networks](https://arxiv.org/abs/1901.01484)|ICLR 2019|1. Propose the Lanczos network (LanczosNet), which uses the Lanczos algorithm to construct low rank approximations of the graph Laplacian for graph convolution. 2. The model efficiently exploit multi-scale information via fast approximated computation of matrix power and design learnable spectral filters. 3. Show the connection between our LanczosNet and graph based manifold learning methods, especially the diffusion maps.|
|[MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing](https://arxiv.org/abs/1905.00067)|ICML 2019|1. Propose a new model, MixHop, that can learn these relationships, including difference operators, by repeatedly mixing feature representations of neighbors at various distances. 2. Propose sparsity regularization that allows us to visualize how the network prioritizes neighborhood information across different graph datasets.|
|[Simplifying Graph Convolutional Networks](https://arxiv.org/abs/1902.07153)|ICML 2019|1. Reduce GNN complexity through successively removing nonlinearities and collapsing weight matrices between consecutive layers. 2. Theoretically analyze the resulting linear model and show that it corresponds to a fixed low-pass filter followed by a linear classifier. 3. Empirically show that these simplifications do not negatively impact accuracy in many downstream applications.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting](https://arxiv.org/abs/1707.01926)|ICLR 2018|1. Propose to model the traffic flow as a diffusion process on a directed graph and introduce Diffusion Convolutional Recurrent Neural Network (DCRNN), a deep learning framework for traffic forecasting that incorporates both spatial and temporal dependency in the traffic flow. 2. DCRNN captures the spatial dependency using bidirectional random walks on the graph, and the temporal dependency using the encoder-decoder architecture with scheduled sampling.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|
|[Revisiting Graph Neural Networks: All We Have is Low-Pass Filters](https://arxiv.org/abs/1905.09550)|Arxiv 2019|1. Develop a theoretical framework based on graph signal processing for analyzing graph neural networks. 2. Show that graph neural networks only perform low-pass filtering on feature vectors and do not have the non-linear manifold learning property. 3. Investigate their resilience to feature noise and propose some insights on GCN-based graph neural network design.|

[Back to index](../README.md)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI2MzEzNjk5MiwxODYwNjY0NTg5LDE2NT
M0Njc0NTFdfQ==
-->