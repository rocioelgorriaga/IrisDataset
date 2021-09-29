# IrisDataset

The **Iris flower data set** or **Fisher's Iris data set** is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis. It is sometimes called **Anderson's Iris data set** because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus".  

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other.  

The dataset contains a set of 150 records under five attributes - sepal length, sepal width, petal length, petal width and species.  

Example of the dataset in Python:   

```python **from** **sklearn.datasets** **import** load_iris  iris = load_iris() iris ```  

This code gives:  

```python {'data': array([[5.1, 3.5, 1.4, 0.2],                 [4.9, 3. , 1.4, 0.2],                 [4.7, 3.2, 1.3, 0.2],                 [4.6, 3.1, 1.5, 0.2],... 'target': array([0, 0, 0, ... 1, 1, 1, ... 2, 2, 2, ... 'target_names': array(['setosa', 'versicolor', 'virginica'], dtype='&lt;U10'),  ...}  ```
