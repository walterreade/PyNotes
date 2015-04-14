
# PyCon 2015 Tutorials

## Machine Learning with Scikit-Learn (I) 

* By: Jake VanderPlas
* [Youtube Video](https://www.youtube.com/watch?v=L7R4HUQ-eQ0)
* [iPython Notebooks](https://github.com/walterreade/PyCon2015-Machine-Learning-I)

```python
# set seaborn plot defaults.
import seaborn as sns; sns.set()
import numpy as np
import matplotlib.pyplot as plt
from sklearn.datasets import load_iris

iris = load_iris()

x_index = 0
y_index = 1

# this formatter will label the colorbar with the correct target names
formatter = plt.FuncFormatter(lambda i, *args: iris.target_names[int(i)])

plt.scatter(iris.data[:, x_index], iris.data[:, y_index],
            c=iris.target, cmap=plt.cm.get_cmap('RdYlBu', 3))
plt.colorbar(ticks=[0, 1, 2], format=formatter)
plt.clim(-0.5, 2.5)
plt.xlabel(iris.feature_names[x_index])
plt.ylabel(iris.feature_names[y_index]);
```

## Machine Learning with Scikit-Learn (II)

* By: Olivier Grisel
* [Youtube Video](https://www.youtube.com/watch?v=oGqGxvqA9-k)
* [iPython Notebooks](https://github.com/walterreade/PyCon2015-Machine-Learning-II)

## Statistical Inference in Python

* By: Allen Downey
* [Youtube Video](https://www.youtube.com/watch?v=5Vjrqnk7Igs)
* [Presentation Slides](https://docs.google.com/presentation/d/1imQAEmNg4GB3bCAblauMOOLlAC95-XvkTSKB1_dB3Tg/edit?hl=en#slide=id.p)
* [iPython Notebooks](https://github.com/AllenDowney/CompStats)
