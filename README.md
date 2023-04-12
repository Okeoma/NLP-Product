# NLP-Product
Application of Text Transformers in the Education Sector

# HyperionDev-DS-Final_Capstone_PCA_Clustering
This is the final capstone of the HyperionDev Data Science bootcamp programme. This final project was on the application of Unsupervised Machine Learning (Clustering) techniques on a US arrest dataset containing three major crimes of Murder, Assault, and Rape per a thousand residents with their Urban population in percentage during a statistic done in 1973 for each of the 50 states in the US.

### Description
The project used the application of two clustering techniques; Hierarchical also known as Agglomerative clustering and K-means clustering to analyze the USArrest dataset in the grouping of states according to the degree of crime (either high crime zone or low crime zone). 

This project is important because it shows how to look at a problem in a simplified form especially when there are a lot of features in a dataset thereby making it difficult to manually check and select the most impactful features that are required for further analysis. This is why a reduction analysis was introduced in the process. Although the dataset used did not have a lot of columns (only five), it was only for demonstration of the process of feature reduction.

Before the clustering models was applied on the dataset, a technique used for feature reduction, Principal Component Analysis (PCA) was applied to reduce the features to two instead of the initial four to ease the process of the machine learning application. The two selected features that showed the most positive impact on the dataset after the PCA and other exploratory analysis was carried out was ‘Murder’ and ‘Assault’. These two features were further explored using the two selected clustering techniques, and the results gotten from their analysis was a representation of the full dataset.  

## Table of Contents

- [Dataset](#Dataset)
- [Goals of Analysis](#Goals-of-Analysis)
- [Installation](#installation)
- [Libraries](#Libraries)
- [Usage](#usage)
- [Credits](#credits)

## Dataset

The USArrest.csv dataset contains statistics, in arrest per 100,000 residents for assault, murder and rape in each of the 50 US States in 1973. The percentage of the population living in urban areas is also given.

## Goals of Analysis
**The aim of the Analysis are as follows:**

- To explore the dataset in order to gain insights on the relationships between the features of the dataset and draw inferences.
- To investigate the impact of each individual feature in the dataset using PCA to understand it's impact and to decide if it should be dropped or be used for further analysis.
- Apply two major Unsupervised Machine Learning methods/ Clustering technigues (Agglomerative and K-means both from Scikit Learn library) on the selected features to give a clearer picture of the crime rates in the states using the most effective parameters and group them according to crime zones; high or low.
- Finally, compare the two Clustering methods used to see their similarities and differences.

## Installation
**To run the application, follow the steps below. If you have Jupyter notebook installed, ignore the first step.**
It is expected that python is already installed on your system.
-  Installing Jupyter with pip. Open command prompt or terminal and type the following: 
`pip3 install --upgrade pip`; to ensure that you have the current version of pip;
`pip3 install jupyter`; to install Jupyter Notebook.
- Clone or download the repository into your system.
- Navigate or cd into the folder containing the files of the program in command prompt or terminal
- Install the required libraries needed for the application if they are not already installed (See libraries section.
- Run the command: `jupyter notebook` or python `python -m notebook` to open the notebook in the browser. Select the jupyter file to see the program to start running the application `final_capstone.ipynb`. 

## Libraries
**Install the following libraries from the command prompt/terminal if not already installed or directly from the jupyter notebook cells:**
- `pip install numpy`
- `pip install pandas`
- `pip install seaborn`
- `pip install matplotlib`
- `pip install sklearn`
- `pip install pca`
- `pip install scipy`

## Usage
After installing all the libraries and opening the jupyter notebook in a browser (except if you are using the Anaconda version), You can view the outcome of the program directly by running the cells of the notebook from top to bottom. Below are some of the screen shots of the application.
1. Heatmap showing relationships of the features.

![figure 1](Screenshots/01_Corr_Heat_Map.jpg)
Figure 1

2. Boxplot showing the different distribution of the features.

![figure 2](Screenshots/02_Data_Dist_Boxplot.jpg)
Figure 2

3. Cummulative variance showing threshold of Principal Components.

![figure 3](Screenshots/03_Cumm_Var_Showing_Threshold.jpg)
Figure 3

4. Barplot showing the variations of the two Principal Components.

![figure 4](Screenshots/04_Var_Explained_Barplot.jpg)
Figure 4

5. Chart showing the PCA for all the features.

![figure 5](Screenshots/05_PCA_Chart.jpg)
Figure 5

6. Chart showing Dandograms of Agglomerative clustering.

![figure 6](Screenshots/06_Selected_Dand.jpg)
Figure 6

7. Boxplot of Agglomerative clustering features.

![figure 7](Screenshots/07_Agglo-Bloxplot.jpg)
Figure 7

8. Scatterplot of Agglomerative clustering features showing High and Low crime zones.

![figure 8](Screenshots/08_Agglo_Scatterplot.jpg)
Figure 8

9. Elbow lineplot for indicating optimum number of K-means clustering features.

![figure 9](Screenshots/09_K_means_Elbow.jpg)
Figure 9

10. Boxplot of K-means clustering features.

![figure 10](Screenshots/10_K_means_Boxplot.jpg)
Figure 10

11. Scatterplot of K-means clustering features showing High and Low crime zones.

![figure 11](Screenshots/11_K_means_Scatter_plot.jpg)
Figure 11

12. Scatterplot of Agglomerative clustering indicating states of either High or Low crime zones.

![figure 12](Screenshots/12_Agglo_Finalscatter.jpg)
Figure 12

13. Scatterplot of K-means clustering indicating states of either High or Low crime zones.

![figure 13](Screenshots/13_K_means_Finalscatter.jpg)
Figure 13

## Credits

This Project was created by Okeoma Ihunwo as a Final Capstone for HyperionDev Data Science Bootcamp - February 2023 [GitHub profile](https://github.com/Okeoma/)

