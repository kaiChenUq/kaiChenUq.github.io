# T-SNE Glossary Table

| Parameter | Description |
| --- | --- |
| N Components | Dimension of the embedded space |
| Perplexity | The perplexity is related to the number of nearest neighbors that is used in other manifold learning algorithms. Larger datasets usually require a larger perplexity. Consider selecting a value between 5 and 50. |
| Early Exaggeration | Controls how tight natural clusters in the original space are in the embedded space and how much space will be between them. For larger values, the space between natural clusters will be larger in the embedded space. |
| Learning Rate | The learning rate for t-SNE is usually in the range [10.0, 1000.0]. If the learning rate is too high, the data may look like a 'ball' with any point approximately equidistant from its nearest neighbors. If the learning rate is too low, most points may look compressed in a dense cloud with few outliers. |
| Max Number of iteration | Usually be at least 250. |
| Min Grad Form | If the gradient norm is below this threshold, the optimization will be stopped. |
| metric | The metric to use when calculating distance between instances in a feature array. |
| Metric parameters | Additional parameters to pass to the metric function. |
| Initialization | Initialization of embedding - with common options are 'random' and 'pca'. |
