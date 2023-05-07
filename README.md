# KostasMarkou_Thesis
In this repository you can find my final code of implementation. 
<br>
<br>
To Run my notebook please follow below instructions:
<br>
1) Download Miniconda from https://docs.conda.io/en/latest/miniconda.html
<br>
2) After installing Miniconda open Miniconda prompt and run "conda install -c conda-forge notebook" or "pip install notebook" commands to install Jupyter.
<br>
3) After installing Jupyter in Miniconda prompt, run "jupyter notebook" and jupyter should open in your browser.
<br>
4) Download FinalMethods.ipynb notebook and tweets.csv file in a folder in your local disk.
<br>
5) Go to Jupyter in your browser and locate the folder that you created and open the notebook.
<br>
<br>
Please find below description for each cell #
<br>
1 Cell--> Importing all necesarry libraries.
<br>
2 Cell--> Reading "tweets.csv" input file
<br>
3 Cell--> Droping "spam" labeled tweets and reset index
<br>
4 Cell--> Combining "abusive" and "hateful" labeled tweets to one label named "harmful"
<br>
5 Cell--> Maping harmful to 0 and normal to 1
<br>
6 Cell--> Removing Twitter Handles
<br>
7 Cell--> Remove links
<br>
8 Cell--> Removing Punctuations, Numbers, and Special Characters
<br>
9 Cell--> Removing Short Words 
<br>
10 Cell--> Tokenization
<br>
11 Cell--> Stemming
<br>
12 Cell--> Combining stemmed tweets to dataset
<br>
13 Cell--> Declaring preprocessing function which works as an extra layer to clean the input
<br>
14 Cell--> Retrieve tweets text and apply the preprocessing function
<br>
15 Cell--> Convert text to vector with CountVectorizer
<br>
16 Cell--> Printing info on vectorised text
<br>
17 Cell--> Check for PCA
<br>
18 Cell--> Create PCA model and transform the data (The PCA model is created using 50 components to keep at least a 70% similarity to the original data, and be able to reduce the time that each algorithm would require to finish)
<br>
19 Cell--> Retrieve labels
<br>
20 Cell--> Create KMeans Model
<br>
21 Cell--> Create Agglomerative Clustering Model
<br>
22 Cell--> Create OPTICS Model
<br>
23 Cell--> Create Birch Model
<br>
24 Cell--> Create DBScan Model
<br>
25 Cell--> Retrieving Rand index metrics for each algorithm
<br>
26 Cell--> Retrieving Mutual Information based scores metrics for each algorithm
<br>
27 Cell--> Retrieving Homogeneity metrics for each algorithm
<br>
28 Cell--> Retrieving Completeness metrics for each algorithm
<br>
29 Cell--> Retrieving V-measure metrics for each algorithm
<br>
30 Cell--> Retrieving Fowlkes-Mallows metrics for each algorithm
<br>
31 Cell--> Retrieving Silhouette Coefficient metrics for each algorithm
<br>
32 Cell--> Retrieving Calinski-Harabasz Index metrics for each algorithm
<br>
33 Cell--> Retrieving Davies-Bouldin Index metrics for each algorithm
<br>
34 Cell--> Contingency Matrix for K-Means
<br>
35 Cell--> Contingency Matrix for Agglomerative Clustering
<br>
36 Cell--> Contingency Matrix for OPTICS
<br>
37 Cell--> Contingency Matrix for Birch
<br>
38 Cell--> Contingency Matrix for DBScan
<br>
39 Cell--> Combine the results into one dataframe
<br>
40 Cell--> Plotting bar plot for Rand index results
<br>
41 Cell--> Plotting bar plot for Mutual Information based scores results
<br>
42 Cell--> Plotting bar plot for Homogeneity results
<br>
43 Cell--> Plotting bar plot for Completeness results
<br>
44 Cell--> Plotting bar plot for V-measure results
<br>
45 Cell--> Plotting bar plot for Fowlkes-Mallows scores results
<br> 
46 Cell--> Plotting bar plot for Silhouette Coefficient results
<br>
47 Cell--> Plotting bar plot for Calinski-Harabasz Index results
<br>
48 Cell--> Plotting bar plot for Davies-Bouldin Index results
