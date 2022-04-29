# Fractal network models
Supplementary material for the work titled *Two novel network models to better understand the origins of fractality* - E. Zakar-Polyák, M. Nagy, & R. Molontay

## How to Cite
```
@misc{zakarpolyak2022two,
  title={Two novel network models to better understand the origins of fractality},
  author={Zakar-Polyák, Enikő and Nagy, Marcell and Molontay, Roland},
  year={2022}
}
```


## Repulsion Based Fractal Model

The Repulsion Based Fractal (RBF) model is based on the Song-Havlin-Makse model, it also evolved through time, and we rewire edges to create repulsion among nodes. However, here the probability of an edge to be rewired is not fixed, but depends on the degree of its endpoints. In contrast to the Song-Havlin-Makse model, repulsion is always present in RBFM, moreover, with a predefined parameter we can specify the nodes that repel each other (e.g., hubs or small degree nodes).

## Lattice Small-world Transition Model

The Lattice Small-world Transition Model (LSwTM) utilizes the fractal nature of grid-like structures, and at the same time works against it with the preferential attachment mechanism.




## Supplementary material

### Stability analysis of the RBF model

![Stability analysis of the RBFM](https://github.com/marcessz/fractal-network-models/blob/main/figures/RBFM_stability.png)

The boxplots of four network metrics are displayed, which show the distribution of the given metric for different parameter settings of the Repulsion based fractal model. Each box is based on 30 generations of the model with the given parameters. Subfigure **(a)** is the boxplot of the normalized diameter (i.e. diameter divided by the logarithm of the size), **(b)** the average degree, **(c)**  the assortativity coefficient and **(d)** the average clustering coefficient. The parameter settings (*x*-axis) are shown in increasing order with respect to the size of the resulting networks.

### Stability analysis of the LSwTM
![Stability analysis of the LSwTM](https://github.com/marcessz/fractal-network-models/blob/main/figures/LSwTM_stability.png)

The distribution of four network metrics for different parameter settings of the LSwTM. Each boxplot is based on 30 generations of the model with the given parameters. Subfigure **(a)** is the boxplot of the normalized diameter (i.e. diameter divided by the logarithm of the size), **(b)** the average degree, **(c)** the assortativity coefficient and **(d)** the average clustering coefficient. The parameter settings (*x*-axis) are shown in increasing order with respect to the size of the resulting networks.
