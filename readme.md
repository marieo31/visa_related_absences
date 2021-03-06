# visa_related_absences

Class activities for the sessions I will miss

## Session: Saturday 09/15/2018 - 5.3 Real-World Data Visualization with Matplotlib

### Ppt: “Intro to statistics.pptx”

### Notions and related python methods:
* **Measures of Central tendency:** MODE, MEDIAN, MEAN
* **Spread of the Data:** Variance, Standard deviation (quartiles), Z-score, Outliers
* **Bias related to sampling of the data:** standard error (sem) and error bars
* **Student’s t-test:** indicator of distance between two populations of data
* **Regression:** quantify the correlation between parameter and forecast
 
### In-class activities:
- 04-Stu_Quartiles_and_Outliers/quartile_outliers.ipynb
  - Use of np.percentile() to determine the upper and lower quartile
  - IQR (interquartile range) and identification of upper and lower outliers
  - Box plot (=boite à moustache)
- 06-Stu_Standard_Error/samples.ipynb
  - Building samples of data contained in a dataframe (I did a little differently from the solution, distributing the sample regularly along the dataset)
  - Calculating properties of each sample: mean and standard error
  - Building plots with error bars
- 08-Stu_Students_t_test/ttest.ipynb
  - Using the Student’s t-test to compare the height of women in general population and within WBA players
  - Using box plot to illustrate the disparities between the two populations
- 10-Stu_Fits_and_Regression/crime.ipynb
  - Using the linear regression function of scipy to quantify the evolution of crime rate along the years and give prediction.

## Session Tuesday 09/18/2018 - 6.1 Working with Web Data (API Requests)

### ppt: "Intro to APIs.pptx"

### Notions and related python methods:
* **APIs request:** request package, get
* **json format:** Structured text -> Python dico, json.dumps()
* **API keys** 
* **Iterative requests**

### In-class activities:
- 02_Stu_SpaceX.ipynb
  - Go through API documentation 
  - Make request and format and print json dictionary
- 03_Ins_Manipulating_JSON.ipynb
  - accessing values from the json structure
- 04_Stu_FarFarAway.ipynb
  - "Nested" requests: use a url obtained from an API request to get other API url and get other info.
- 05_Par_NumberFacts.ipynb
  - Build API urls with user input
- 08_Stu_MovieQuestions.ipynb
  - Use API request with more complex url (API keys)
- 10_Stu_MovieLoop.ipynb
  - Use loop to performed repeated requests
- 12_Stu_Retrieve_Articles.ipynb
  - Sign up for the NYT API key and use gitignore file to store it
  - handle multiple query criteria in the url
  - looping on the query criteria to obtain more results


## Session Thursday 09/20/2018 - 6.2 JSON Traversal and Data Parsing

### ppt: Working with Weather & City APIs.pptx

### Notions and related python methods:
* **json:** Importing and geting info from json files
* **API requests**
* **try/except:** Handle bugs and exceptions gracefully
* **Combined use of API request, Pandas dataframe, Matplotlib**
* ** API wrappers:** Easier API requests configurations with settings dict instead of query url specific syntax
* ** API documentation**

### In-class activities:
- 01_Stu_JSON_Traversal.ipynb
  - Manipulating json imported dictionary
- 02_Stu_RequestReview.ipynb
  - List of dict from API request
- 04_Stu_Bujumbura.ipynb
  - Complex request (several parameters)
- 06_Stu_TVRatings.ipynb
  - Using API request, Pandas and Matplotlib
- 08_Stu_MakingExceptions.ipynb
  - try/except with specification of error type
- 10_Stu_MapWrap.ipynb
  - Using API wrapper to ease the configuration of the resquest (settings) and the extraction of information from the API data
- 12_Stu_TwoCalls.ipynb
  - Use API documentation
  - Obtain information from a first call to make other API requests

## Session Saturday 09/20/2018 - 6.3 Visualizing Financial Deserts with Google Places and Census


### In-class activities:
- 03_Google_That.ipynb
- 05_Airport_Ratings.ipynb
- 07_airport_heatmap.ipynb
- 09_Census_States.ipynb


