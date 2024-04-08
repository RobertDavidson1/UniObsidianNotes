## Jupyter/Python Basics
- [ ] Importing Packages
- [ ] Ipython/Jupyter line/cell magic e.g. `%timeit`
- [ ] Help syntax
- [ ] Input/Output history

## Data Types and Numpy
- [ ] Static vs Dynamic typing
- [ ] Integer Type in Python vs Numpy
- [ ] Python List vs Numpy List
- [ ] Differences in Memory and Efficiency Python vs Numpy

## Numpy Syntax & Usage

- [ ] Values are generated within the half-open interval [start, stop) (in other words, the interval including start but excluding stop).
- [ ] Array creation
- [ ] `.zeros` and `.ones` and `.eye`
- [ ] `.full` and `.empty`
- [ ] `.arange([start, ]stop, [step, ])` and `.linspace(start, stop, num)`
- [ ] `.random*`
- [ ] Numpy Data Types {int*, uint*, float*, complex*}
- [ ] Comparison of Numpy/Python arrays
- [ ] Array Attributes
- [ ] `.dtype`
- [ ] `.shape`
- [ ] `.itemsize`
- [ ] `.nbytes`
- [ ] Indexing Numpy Arrays
- [ ] Slicing Numpy Arrays `[start:stop:step]`
- [ ] Array copying & Reshaping
- [ ] `.newaxis`
- [ ] `.split`
- [ ] Ufuncs
- [ ] Meaning & advantage
- [ ] Binary & Unary
- [ ] arithmetic/trig/exp/log
- [ ] Aggregates
- [ ] `.reduce`
- [ ] `.accumulate`
- [ ] `.sum` and `.prod`
- [ ] Broadcasting Rules
- [ ] Boolean Arrays
- [ ] via comparisons
- [ ] counting `.sum` and `.any` and `.all`
- [ ] Masks & use via fancy indexing
- [ ] Boolean Operators AND `&` and OR `|` and NOT `~` and XOR `^`
- [ ] Array `.sort` and `.argsort`

## Pandas Syntax & Usage
- [ ] Objects
- [ ] `.Series`
- [ ] `.DataFrame`
- [ ] (`.Index`)
- [ ] Series object properties
- [ ] `.values`
- [ ] `.index`
- [ ] Indexing without `.loc` and `.iloc`
- [ ] Indexing with `.loc` and `.iloc`
- [ ] DataFrame object properties
- [ ] `.value_counts`
- [ ] `.index`
- [ ] `.columns`
- [ ] Sub-dataframes using Masking, fancy indexing, and `.query`
- [ ] Missing values `Nan` and use of `.dropna`
- [ ] DataFrame as
- [ ] list of Series
- [ ] Dictionary of Series
- [ ] Array
- [ ] Index as an immutable ordered set
- [ ] Mathematical operations on DataFrames
- [ ] Index preservation
- [ ] Ufuncs or Pandas methods
- [ ] Join Operations on DataFrames
- [ ] `.concat` and `.merge`
- [ ] merge types
- [ ] 1-to-1,
- [ ] many-to-1,
- [ ] many-to-many
- [ ] `how=`
- [ ] inner (Intersection of Indices)
- [ ] outer (Union of Indices)
- [ ] Using `.dropna` `.isnull` `.any`
- [ ] `DataFrame.plot` (By default, matplotlib is used)

## Matplotlib Syntax & Usage
- [ ] `plt.plot(x,f(x))`
- [ ] `plt.scatter(x,y)`
- [ ] `plt.hist(data)`
- [ ] Subplots with `plt.subplots(i, j)`

## Machine Learning
- [ ] What is Machine Learning?
- [ ] What are the two types of of ML (with examples)?
- [ ] Supervised Learning
- [ ] Classification (e.g. using DecisionTreeClassifier or a Random Forest)
- [ ] Regression (e.g. using LinearRegression)
- [ ] Unsupervised Learning
- [ ] Dimensionality Reduction (using e.g. PCA)
- [ ] Clustering (using e.g. kMeans)
- [ ] Model Selection
- [ ] Overfitting
- [ ] Hyperparameters
- [ ] Bias/Variance & the Validation Curve
- [ ] Learning Curve
- [ ] Data Familiarization
- [ ] `DataFrame.shape`
- [ ] `DataFrame.describe`
- [ ] `pd.plotting.scatter_matrix` or `sns.pairplot`
- [ ] Outliers
- [ ] Scaling of Data
- [ ] Scikit-learn Syntax
- [ ] `train_test_split`
- [ ] `confusion_matrix`
- [ ] `.tree.DecisionTreeClassifier(max_depth=?)`
- [ ] `.linear_model.LinearRegression()` and `coef_` and `score(X_test, y_test)`
- [ ] `.decomposition.PCA(n_components=?)` `pca.explained_variance_ratio_`
- [ ] `.cluster.KMeans(n_clusters=?)` & Elbow Method
- [ ] Modern ML
- [ ] Basic idea of (Deep) Neural Networks