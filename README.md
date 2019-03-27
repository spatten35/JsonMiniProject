# JsonMiniProject
JSON examples and exercise
get familiar with packages for dealing with JSON
study examples with JSON strings and files
work on exercise to be completed and submitted
reference: http://pandas.pydata.org/pandas-docs/stable/io.html#io-json-reader
data source: http://jsonstudio.com/resources/


JSON exercise
Using data in file 'data/world_bank_projects.json' and the techniques demonstrated above,

Find the 10 countries with most projects
Find the top 10 major project themes (using column 'mjtheme_namecode')
In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.

# APIMiniProject
Qaundl has a large number of data sources, but, unfortunately, most of them require a Premium subscription. Still, there are also a good number of free datasets.

For this mini project, we will focus on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. We'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.

You can find the detailed Quandl API instructions here: https://docs.quandl.com/docs/time-series

While there is a dedicated Python package for connecting to the Quandl API, we would prefer that you use the requests package, which can be easily downloaded using pip or conda. You can find the documentation for the package here: http://docs.python-requests.org/en/master/

Finally, apart from the requests package, you are encouraged to not use any third party Python packages, such as pandas, and instead focus on what's available in the Python Standard Library (the collections module might come in handy: https://pymotw.com/3/collections/). Also, since you won't have access to DataFrames, you are encouraged to us Python's native data structures - preferably dictionaries, though some questions can also be answered using lists. You can read more on these data structures here: https://docs.python.org/3/tutorial/datastructures.html

Keep in mind that the JSON responses you will be getting from the API map almost one-to-one to Python's dictionaries. Unfortunately, they can be very nested, so make sure you read up on indexing dictionaries in the documentation provided above.


# Mean Human Body Temperature mini project
What is the True Normal Human Body Temperature?
Background
The mean normal body temperature was held to be 37 ∘ C or 98.6 ∘ F for more than 120 years since it was first conceptualized and reported by Carl Wunderlich in a famous 1868 book. But, is this value statistically correct?


# Examining Racial Discrimination in the US Job Market
Background
Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers.

Data
In the dataset provided, each row represents a resume. The 'race' column has two values, 'b' and 'w', indicating black-sounding and white-sounding. The column 'call' has two values, 1 and 0, indicating whether the resume received a call from employers or not.

Note that the 'b' and 'w' values in race are assigned randomly to the resumes when presented to the employer.
