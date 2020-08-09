**Source:** \
State-wise top baby names in the US from the Social Security administration website. The dataset is hosted by the Social Security Administration (SSA) and is intended for public access and use. The dataset was downloaded from https://catalog.data.gov/dataset/baby-names-from-social-security-card-applications-national-level-data as a 21 MB zip file.

**About Dataaset:** \
The zip file contains individual state-wise text files of top baby names in that particular state from 1910 to 2018. Each text file contains 5 features - state postal code, gender, year of birth, first name and number of samples of the name. The data (as claimed by the website) was sampled by the SSA from 100% of all social security card applications. 

**Motivation:** \
To visually explore this dataset and build a simple model to predict and individual's gender based on his/her name.

**Libraries:** 
- numpy and pandas for data structure manipulation
- matplotlib and seaborn for data visualisation
- sklearn for building a logistic regressor and support vector classifier
