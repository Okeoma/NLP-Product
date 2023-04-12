# NLP-Product
Application of Text Transformers in the Education Sector

# Data Science Product Development on Text Transformers in the Educational Sector
This is the final Assignment which is a follow-up of the first Assignment on Literature Review. This project is on developing a data science product prototype and it cumulated with a write-up of a report about the design, development and management of the prototype and development of the project.

### Description
The Data science NLP product was built with text transformers. There are suitable NLP machine learning models that are effective for use in the education sector. Some of them were used in developing the product.

The programming language that was used for developing the NLP product is Python. This is because Python is a versatile language that can be used for a wide range of tasks, from data processing and web development to scientific computing and machine learning. This flexibility makes it easy to integrate different aspects of a project into a cohesive whole.

In addition, Streamlit was used to design the user interface. This is due to its ease of deployment of machine learning applications onto the web. Streamlit enables developers to deploy their applications to a web server with only a few lines of code, making sharing their work easier. 
The Data exploration and machine learning was ran using Google Colab notebook. The models were saved in the local system and the streamlit application was built with .py scripts. The saved models was later used in the streamlit app for processing text and displaying the required results.

## Table of Contents

- [Dataset](#Dataset)
- [Goals of Analysis](#Goals-of-Analysis)
- [Installation](#installation)
- [Libraries](#Libraries)
- [Usage](#usage)
- [Credits](#credits)

## Dataset

Dataset used is the IMDb dataset. The Internet Movie Database contains movie reviews that were used to train text transformers on sentiment analysis. The dataset can be downloaded from the IMDb website: https://huggingface.co/datasets/imdb. The dataset was used to train  pre-train transformer models, “distilbert-base-cased” and “bert-base-cased” and any of the two models is to be used for sentiment analysis for text classification.

## Goals of Analysis
**The aim of the Analysis are as follows:**

- To explore the dataset in order to gain insights on the relationships between the feature variable - 'text' and the outcome variable - 'label' of the dataset and draw inferences.
- To investigate the size of the dataset to ascertain the amount of the dataset required and to decide the amount of data that should be dropped or be used for further analysis.
- Apply two major Supervised Machine Learning methods for transformers employed for Sentiment Analysis (“distilbert-base-cased” and “bert-base-cased”) on the selected dataset to give a clearer picture for predicting the sentiment of a text if is is POSITIVE or NEGATIVE.
- Use Confusion matrix and Accuracy scores to confirm the effectiveness of the models.
- Employ different Machine Learning Models used in NLP for displaying the outcome of various use cases popular among educational products.

## Installation
**To run the application, follow the steps below.**
It is expected that python is already installed on your system (Minimum Python version is 3.6.6).
-  If you are interested in running the Jupyter notebook on your local system, you can follow the below steps otherwise upload the notebook files to Google Colab. **Installing Jupyter with pip. Open command prompt or terminal and type the following: 
`pip3 install --upgrade pip`; to ensure that you have the current version of pip;
`pip3 install jupyter`; to install Jupyter Notebook.**
- Clone or download the repository into your system.
- Navigate or cd into the folder containing the Jupyter notebook files 'notebook_files' in command prompt or terminal.
- Install the required libraries needed for the application if they are not already installed (See libraries section.
- Run the command: `jupyter notebook` or python `python -m notebook` to open the notebook in the browser. Select the jupyter file to see the program and to start running the application 'CETM46_NLP_tasks_with_Transformers.ipynb', 'CETM46_text_classification_bert.ipynb' and 'CETM46_text_classification_distilbert.ipynb'. 

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

