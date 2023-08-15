# EDA
Data cleaning and visualization in python libraries using numpy,pandas, matplotlib and seaborn.

Today i will be presenting some techiniques to how to present the data cleaning and visualization using python libraries such as numpy,pandas, matplotlib and seaborn.this presentation aims us to demonstrate how to handle the raw data, missing data,clean data,proving a clear understanding of the data and insightful visualization.

step-1: DATA LOADING AND EXPLORATION: we start loading the dataset using pandas libraries pd.read_excel function. the key methods used to gain some extra information about the data includes shapes, len, info(),isnull(),sum() this functions helps us to understand the size,structure and presence the missing values in the dataset.

step - 2 : DATA CLEANSING - REMOVING THE SPECIAL CHARACTERS AND EXTRACTING THE NUMERICAL VALUES : To clean the data, we utlize the pandas libraries string methods. specifically, we use str.replace(r''\W'',") means to remove any special characters. Additionally, str.extract('(\d+)') means to extract numerical values from the relevant columns,if neccesary.

step-3 MISSING VALUE TREATMENT USING NUMPY : To handle the missing data , first we import the numpy library. we make use some functions to know the basic information of the data such as info() - to get information to the data set. head() - is used for top five records to the dataset. fillna() - is used to replace the missing values from the data . astype() - means this method allows us to convert data from one type to another . and we use os.getcwd() - is a function provided by the 'os' module, which stands for "Operating System Interface." It is used to get the current working directory (CWD) of the Python script or application.

step - 4 : DATA VISUALISATION USING MATPLOTLIB AND SEABORN : Nest, we deploy into data visualisation to gain valuable information from the cleaned dataset . we used to matplotlibfor basic visualisations like histograms and seaborn fro more advanced visualisations. Before we proceeding we import warnings.. warnings filterwarnings("ignore") to surpress the unwanted warnings.

step - 5 : BASIC VISUALIZATION WITH MATPLOTLIB : Using matplotlib, we explore visualisations like sns.distplot - means distribution plot ,rcParams for figure and figsize control , and the histogram function. These visualisations helps to understand the distribution of variables and identify patterns or anomalies.

Step-6 ADVANCED VISUALIZATION WITH SEABORN : Moving on to seaborn, we learn hhow to create advanced visualizations that offer depper insights into the data. Some of the functions we are sns.lmplot, which plots regression lines on scatter plots, and other customizations to enhance the visualiztion further.

Step-7 DATA MANIPULATION WITH SCLICING and INDEPENDENT VARIABLE AND DEPENDENT VARIABLES : To extract Specific Information from the dataset, we employ slicing techniques. Additionally, we discuss the significance of distinguishing between dependent variable and independent variables and how to handle them using Pandas.

Step-8 DATA ENCODING WITH pd.get_dummies : Data encoding is an essential step in preparing data for machine learning models. We demonstrate how to convert categorical_variables into numerical representations using the pd.get_dummies function.
