# dimension-reduction-technique

	•	Many datasets (like images, text, genetics, finance) have hundreds or thousands of features.
	•	Not all features are useful — some are redundant (correlated with others) or noisy (random, not adding information).
	•	Dimension reduction is the process of transforming high-dimensional data into a smaller set of features while keeping as much useful information as possible.

Think of it as
Summerizing a big dataset into fewer dimensions,like condensing a long book into a short summary but still keeping the main idea.
Why do we need this ?
1 . Visualization :
Humans can't visualize 100 dimensional data , but we can only see 2D/3D plots only.

Dimension reduction allows us to plot and explore clusters.

2.Speed and efficiency:
Fewer features = faster training of ML models
3. Noise Reduction:
Removes irrelevant features that may confuse the model.
4.Avoid Overfitting:
Reducing features helps models generalize better.
For supervised we use feature selection
Correlation ,Chi Squared ,Mutual Infomation
Wrapper Method
Pros: Keeps interpretability (Fetures stay the same) .

Cons: Might miss hidden combination of fetures.

For unsupervised Feature extraction.
Transform the original data into smaller set of new variables.
The new features are combinations of the old ones.
Techniques:
PCA(Principle Component Analysis).
LDA (Linear Discriminant Analysis).
t-SNE (t-Distributed Stochastic Neighbor Embedding ).
UMAP (Uniform Manifold Approximation and Projection).
Autoencoders (Neural Networks for compression).
Pros:Captures hidden structure , powerfull for visualiztion.

Cons: New features are harder to interpret.

PCA(Principle Component Analysis)
Goal : Find new axes (Called Principle Component) that captures the most variance in the data
Example:

Supposed we have height and weight ,They are correlated.
PCA will crate a new axisi libe "Body Size" that combines both into one.
Used for:Visualiztion
