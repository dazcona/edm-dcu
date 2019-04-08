# Analysis on Student Data

## Data

| Number of students | Number of fields |
| :-------------: | :-------------:|
| 16,786 | 137 |

[List of fields](docs/fields.md)

## Notebooks

1. [EDA](notebooks/EDA.ipynb): Exploratory Data Analysis by looking at all the fields and their values
2. [Correlations & Scatter plots](notebooks/Scatter%20%26%20Correlations.ipynb): pair-wise correlations
3. [Features](notebooks/Features.ipynb): extract features from the fields
4. [Dimensionality Reduction]((notebooks/Dimensionality%20Reduction.ipynb)): PCA, tSNE, UMAP
5. [Split the data](notebooks/Split%20train%20%26%20test%20sets.ipynb): split the dataset into Train and Test sets
6. [Decision Tree](notebooks/Modelling%20a%20Decision%20Tree.ipynb): modelling a Decision Tree classifier
7. [Random Forest](notebooks/Modelling%20a%20Random%20Forest.ipynb): modelling a Random Forest classifier and analysing the power of their features
8. [Linear Models & Ablation studies](notebooks/Ablation%20Study.ipynb): fitting a Logistic Regression classifier and running ablation studies to measure the variance explained by the features

## Tutorials

* [Intro to NetworkX](notebooks/Intro%20to%20Networkx.ipynb)
* [Intro to UMAP](notebooks/Intro%20to%UMAP.ipynb)
* [Intro to Embeddings](notebooks/Intro%20to%Embeddings.ipynb)

You can always view a notebook using https://nbviewer.jupyter.org/

## Figures

**EDA**: Exploring CAO Points
![](figures/exploring_CAO_POINTS.png)

**Correlations**:
![](figures/correlations.png)

**Scatter plot**: CAO Points vs Leving Cert Math Points
![](figures/scatter_CAO_POINTS_LC_MATHS_POINTS.png)

**Decision Tree to predict the final RESULT**:
![](figures/tree_RESULT.png)

**Random Forest**: Top 10 Most Important Features
![](figures/modelling_Random_Forest_Top_10_Feature_Importances.png)

**Linear Model**: Ablation Study by Excluding Features
![](figures/linear_model_variance_explained_by_excluding_features.png)
