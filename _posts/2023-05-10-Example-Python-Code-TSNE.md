# Example Python t-SNE code snippet

Here is an example code snippet for t-SNE in Python: 

```Python
from sklearn.manifold import TSNE
import matplotlib.pyplot as plt

X_embedded = TSNE(n_components=2).fit_transform(X)

plt.scatter(X_embedded[:,0], X_embedded[:,1])
plt.show()
```

Overview:
* use TSNE class from the `sklearn.manifold` module to perform t-SNE on the input data `X`. 
* The resulting 2D embedding is then plotted using `matplotlib`
