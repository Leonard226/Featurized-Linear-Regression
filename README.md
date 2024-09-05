# Featurized-Linear-Regression
Please refer to `main.ipynb` for mathematical derivations, more details, and specific implementations; everything is documented there. 
<br>
<br>
Short description: <br>
Given a labeled data set $D_{train}=\{(x_i, y_i)\}_{i=1}^n$, where $x_i \in \mathbb R^d$, $y_i \in \mathbb R$, and $n \gg d$. We are given a feature map $\Phi : \mathbb R^d \to \mathbb R^p$ and make the prediction $w^T \phi(x) = y$, for a given $x \in \mathbb R^d$, where we apply linear regression in the feature space to find the optimal $w$. 
