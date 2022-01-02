# Baltimore-Education

<img width="435" alt="Baltimore_Common_Education_Attainment" src="https://user-images.githubusercontent.com/45469389/147863037-459e1334-9cf8-412b-8e95-b3459eb34ed6.png">


Using Census Bureau's API to create a Choropleth Map using Geopandas.

In this example, we're going to use Census Bureau's application programming interface (API) to pull certain education variables to create a choropleth map to show common education attainment in all census tracts of Baltimore City, MD.

The Census Bureau's API is just a more streamlined way to access data without opening large or multiple datasets. Also, the API allows users to create their own datasets specifying the specific variables of interest. Most of the Census tract data is from the American Community Survey (ACS).

To use Census Bureau's API, we have to request an API key from the Census Bureau's website. The will allow you to pull data via the API. You can request the API here: https://api.census.gov/data/key_signup.html. Also, the API User Guide is a good resource on how to use your API key to pull data (https://www.census.gov/content/dam/Census/data/developers/api-user-guide/api-guide.pdf).

When using the API, you have to must know the Census variable names for the data of interest. Please keep in mind that Census variable names are not uniform. It depends on which data you are using (ACS, Dicennial Census, Economic Census). In this example, our data will be based on the ACS 5-year data profiles for 2017. The Census variable names for those data are listed here: https://api.census.gov/data/2017/acs/acs5/profile/variables.html.

