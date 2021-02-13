
### What is NOT machine learning?

- Deep learning
- Data science
- Data mining
- Big data
- Statistics
- Artificial intelligence

### What is machine learning?

- Machine learning is the next Internet (Tony Tether, Former Director, DARPA)
- Machine learning is the hot new thing (John Hennessy, President, Standford)
- Field of study that gives computers the ability to learn without explicitly programmed (Arthur Samuel, AI pioneer)
- Machine learning us concerned to the question of how to sruct computer programs that automatically improve with experience (Tom Mitchell, scientist, MIT


Traditional programming:
```
Requirements  ___________           ___________
------------->|         | Algorithm |          |  Output
Data          | Human   |---------->| Computer |---------->
------------->|_________|           |__________|
                                        ^Input

```

Machine learning:
```
Requirements  ___________           ___________
------------->|         |  Output   |          |  Algorithm
Data          | Human   |---------->| Computer |---------->
------------->|_________|           |__________|
                                        ^Input

```

Human is bottleneck, when:
- Data/requirements changes quickly
- Human expertise is absent
- [Moravec's paradox](https://en.wikipedia.org/wiki/Moravec's_paradox)  
- Data size is too large

### Study plan: Supervised learning

- Linear and non-linear models
- Discriminative and Generative models
- Neural networks, backpropagation

### Study plan: Unsupervised learning

- Clustering
- Dimensionality reduction
- Manifold learning

### Study plan: Reinforcement learning

- Adaptive control
- Marcov's decision process
- Q-learning

### Study plan: Deep learning

- Autoencoders
- GANs
- Transfer learning 
- Adversarial attacks

### Study plan: Learning theory

- Regularization
- Optimization
- Evaluation
- Parametric/non-parametric learning
- Ensemble learning

### Pre-requisites

- Deep learning book
- youtube 3Blue1Brown
- Standford's Refresher (or something like that)

### Linear Algebra

- Vectors, matrices, tensors
- Linear and non-linear transformations
- Dot product, matrix multiplication
- Matrix Inverse
- Eigenvectors and Eigenvalues
- Singular Value Decomposition

### Probability Theory

- Bayes Theorem
- Joint, Marginal, Conditional probability
- Probability distributions
- Variance, covariance, deviation, expectation
- Sample, statistics, estimation

### Python

- Jupyter: interactive development environment (Google CoLab)
- NumPy: linear algebra in python
- pandas: data analysis
- Scikit Learn: Machine Learning in Python (recommended: scikit-learn User Guide)
- TensorFlow: end-to-end machine learning
- Keras: API

### Context: Data Science

### Data science project workflow 

Making value from data

[CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)


```

          ________________      ________________
          | Buisiness    |----->|    Data       |
          | Understanding|<-----| Understanding |---|
          |______________|      |_______________|   |
                ^                                   |
                |___________________                V
                                   |              ______________
____________          ________     |             | Data        |
|Deployment |         | Data |     |             | Preparation |
|___________|         |______|     |             |_____________|
    ^                              |                |^
    |                              |                V|
    |                              |               __________
    |                              |              | Modeling |<---- Machine Learning here
    |                              |              |__________|
    |                  _____________                  |
    -------------------| Evaluation |<----------------|
                       |____________|


```

### Buisiness understanding:

...

- [mlflow](https://mlflow.org/)
- [automl](https://cloud.google.com/automl)


[Feature selection](https://en.wikipedia.org/wiki/Feature_selection)
