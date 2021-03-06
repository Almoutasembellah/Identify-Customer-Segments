# Identify Customer Segments
**In this project, we will work with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution.** The data here concerns a company that performs mail-order sales in Germany. **Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign.** Your job as a data scientist will be to use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, you will also need to assess and clean the data in order to convert the data into a usable form.

**And the project is divided as follows:**
- Step 0: Load The data
- Step 1: Preprocessing
  -  Assessment - Cleaning - Re-encoding
  -  Feature engineering
- Step 2: Feature Transformation
  - Feature scaling and Perform the PCA
  - Interpret Principal Components
- Step 3: Clustering
  - Apply clustring
  - Compare Customer Data to Demographics Data

## Requirements
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE.
The following libraries are expected to be used in this project:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Sklearn/scikit-learn](http://scikit-learn.org/stable/)
- [Matplotlib](http://matplotlib.org/) (for data visualization)
- [Seaborn](https://seaborn.pydata.org/) (for data visualization)

 It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks.

## Data
The actual data was removed due to terms and conditions of AZ Direct GmbH which prohibits of using data in any other content rather than Udacity course.

## Results
Cluster 3 is overrepresented in the customers data compared to general population data, we can describe some segments of the population that are relatively popular with the mail-order company as follows :
People with age older than 60 years old is higher (ALTERSKATEGORIE_GROB = 3.444134) Females (ANREDE_KZ = 1.266893)

Cluster 2 is underrepresented in the customers data compared to general population data, we can illustrate some segments of the population that are relatively unpopular with the company:

People with age of 46 - 60 years old is lower (ALTERSKATEGORIE_GROB = 2.701163)

Females (ANREDE_KZ = 1.603958)




