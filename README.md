# Washiington DC Crime Prediction
A team repo  for  project 5 for Client with The Lab @ DC (GA-DSI)

# Settings
  1) Make sure you have `.gitignore` in your local repo by adding this line: `input/csr/*`
  2. Download  with out forking so that we can work and push on things we have done
  3) Make sure you install and track Git Large File Storage(read more: https://git-lfs.github.com)
    - `git lfs install`, `git lfs track "*.csv"`
    - this will create  `.gitattributes` in your local repository.

# Approaches
pproaches and Deliverables with DC crime Prediction 
**Approach** 
   - Determine which variables provide the highest correlation with crime incidents 
   - Visualize incidents in a map for different choices of variables and filters 
   - Heatmaps, kernel density estimate plots to correlate variables 
**Feature selection**
 - Time series analysis on variables 
  - Identify seasonal effects 
  - Determine anomalies 
  **Prediction models** 
   Regression (to determine the evolution of patterns over time) Clustering (to determine common patterns across census tracts, Wards or ANC, etc.) Classification (to predict if a given crime is likely to happen in a given time and location) 
  **Deliverables**
  -  A notebook including: Analysis of crime patterns Models for predicting crime
----------------------------------------------------
# Sources: datasets
  1) Open Data DC
    - https://opendata.dc.gov/datasets/camera-enforcement-locations
    -  https://opendata.dc.gov/datasets/traffic-camera
    - https://www.arcgis.com/home/webmap/viewer.html?webmap=c88bff76cd3e4568800a19e9f361822e
    - https://opendata.dc.gov/datasets/crime-incidents-in-2017/data
    - https://opendata.dc.gov/datasets/crime-incidents-in-2016
    - https://opendata.dc.gov/datasets/crime-incidents-in-2015
    - https://opendata.dc.gov/datasets/crime-incidents-in-2014
    - https://opendata.dc.gov/datasets/crime-incidents-in-2013
    - https://opendata.dc.gov/datasets/crime-incidents-in-2012
    - http://opendata.dc.gov/datasets/real-property-tax-assessment-neighborhoods 
    - http://opendata.dc.gov/datasets/real-property-tax-assessment-sub-neighborhoods
    - https://mpdc.dc.gov/publication/shotspotter-data-disclaimer-and-dictionary
    - https://opendata.dc.gov/datasets/specialty-lighting
    - https://datahub.io/core/house-prices-us#data


    - fetched, June, 2018

  2) City Service Requests Data, Open Data DC
  http://opendata.dc.gov/datasets?q=service%20requests
    http://opendata.dc.gov/

    - 2014: http://opendata.dc.gov/datasets/city-service-requests-in-2014
    - 2015: http://opendata.dc.gov/datasets/city-service-requests-in-2015
    - 2016: http://opendata.dc.gov/datasets/city-service-requests-in-2016
    - 2017: http://opendata.dc.gov/datasets/city-service-requests-in-2017
    - fetched, June, 2018
### Team
Client project teams !

| Team  Members |
|--------|
| Awab   | 
| James  |  
| Kiros  |
| Eric   |
|        |      


#### Additional from the Project lab
---------------------------------
### Problem Areas, Potential Questions, and Additional Resources

In consultation with the Lab @ DC, we've organized questions into three main problem areas.  You are not limited to addressing these questions, but they are some of the questions that are currently of interest to The Lab!
____________
### Problem Areas

- **Crime-Related**:
  - Does crime go up when street lights go out? (This is actually an open data science project that The Lab is working on right now, led by a volunteer. You can check out the repo [here](https://github.com/thelabdc/lights-and-crime). You could pick up an existing thread or start from the ground up!)
  - Can we predict how many people are going to be in jail or released from jail? Are there issues associated with this, such as overcrowding? Are there (evidence-based) steps that could be taken to avoid some of these issues?
  - Do wireless hotspots or security cameras reduce crime?
  - If we built similar models to predict gunshots and to predict 311 calls (using the same predictors, say) what might we learn from comparing the model parameters and predictions?
  - Using [this](https://github.com/thelabdc/NEAR-Act-Public) data:
    - Can we tell if being charged with one crime is highly predictive of also being charged with certain other crimes, or: 
    - Are there other factors that predict a combination of offenses (e.g. maybe arrests in specific locations are more likely to have specific combinations of charges)
  - DC makes available [crime incident location data](http://opendata.dc.gov/datasets/crime-incidents-in-2017). Using that data:
    - Can you build a model to predict or explain crime? (Note: you can use continuously update [2018 Data](http://opendata.dc.gov/datasets/crime-incidents-in-2018) as a real-life test set.)
    - Can you merge this dataset with another dataset to explore the relationship between crime and, e.g. house prices, parking tickets, 311 requests, or certain city infrastruture?

- **Property-Related**:
  - Can you identify different features from an [aerial image](http://opendata.dc.gov/pages/dc-from-above) in order to predict whether a house is vacant, or identify the type of property?
  - Using [Real Property Values](http://opendata.dc.gov/datasets?q=real%20property):
    - Can you estimate or assess housing values based on aerial imagery, voter file data, and other information?
    - Can we make inferences about property values or demographic trends given construction and occupancy permits?

- **Forecasting**:
  - Can we forecast service needs around DC based on [311 service calls](http://opendata.dc.gov/datasets?q=service%20requests) and other data?
  - Can we forecast [traffic accidents, moving violations, and parking tickets](http://opendata.dc.gov/datasets?q=parking%20violations&sort=-updatedAt)? Based on these forecasts, can we make policy recommendations, forecast revenue, or 
  - Can we build a voter turnout model to predict the likelihood that someone will vote. Data data are available from the Board of Elections for $5 on a CD. If you build the model before the June primary, you’ll have a built-in test set!

_____________

### Additional Resources
The [DC Open Data Portal](https://opendata.dc.gov/) is your friend.
______________

The [DC FOIA Reading Room](https://foia-dc.gov/App/ReadingRoom.aspx) gives access to documents released under the Freedom of Information Act.

___________

[The DC Policy Center](https://www.dcpolicycenter.org/) releases a lot of reports that may be of interest, including:
  - [Taking Stock of the District's Housing Stock](https://www.dcpolicycenter.org/publications/taking-stock-full-report/), with data available.
  -  [Can Neighborhood Characteristics Explain Enrollment in at In-Boundary Schools?](https://www.dcpolicycenter.org/publications/schools-in-the-neighborhood-summary/), with data from the Deputy Mayor for Education.

_____________

The [Federal Government's data portal](https://catalog.data.gov/dataset) may provide some interesting data to cross refence against.

Case-Shiller Index of US residential house prices. Data comes from S&P
Case-Shiller data and includes both the national index and the indices for 20
metropolitan regions. The indices are created using a repeat-sales methodology.

## Data

As per the [home page for Indices on S&P website][sp-home]:

> The S&P/Case-Shiller U.S. National Home Price Index is a composite of
> single-family home price indices for the nine U.S. Census divisions and is
> calculated monthly. It is included in the S&P/Case-Shiller Home Price Index
> Series which seeks to measure changes in the total value of all existing
> single-family housing stock.

Documentation of the methodology can be found at:
<http://www.spindices.com/documents/methodologies/methodology-sp-cs-home-price-indices.pdf>

Key points are (excerpted from methodology):

* The indices use the "repeat sales method" of index calculation which uses
  data on properties that have sold at least twice, in order to capture the
  true appreciated value of each specific sales unit.
* The quarterly S&P/Case-Shiller U.S. National Home Price Index aggregates nine
  quarterly U.S. Census division repeat sales indices using a base period a nd
  estimates of the aggregate value of single family housing stock for those periods.
* The S&P/Case - Shiller Home Price Indices originated in the 1980s by Case
  Shiller Weiss's research principals, Karl E. Case and Robert J. Shiller. At
  the time, Case and Shiller developed the repeat sales pricing technique. This
  methodology is recognized as the most reliable means to measure housing price
  movements and is used by other home price ind ex publishers, including the
  Office of Federal Housing Enterprise Oversight (OFHEO)

[sp-home]: http://www.spindices.com/index-family/real-estate/sp-case-shiller

## Preparation

To download and process the data do:

    python scripts/process.py

Updated data files will then be in `data` directory.

Note: the URLs and structure of the source data have evolved over time with the
source data URLs changing on *every release*.

Originally (2013) the site provided a table of links but these are not direct
file URLs and you have dig around in S&P's javascript to find the actual
download locations. As of mid-2014 the data is consolidated in one primary XLS
but the HTML you see in your browser and the source HTML are different. In
addition, the actual location of the XLS file continues to change on each
release.
### DATA DICTIONARY
#### Attributes to Remove
The below table provides a description of attributes that will be removed because they provide little to no predictive power for the Washington DC Metropolitant Police Department crime incident report.

|Attribute|Description|Removal Reason|
|:------|:----------|:-------------|
|REPORT_DAT| The date/time the offense was *reported*| When the crime was report is not a predictor of a crime.|
|SHIFT| The duty shift that responded to the call.| This is an eight hour window that is too coarse grain.|
|OFFENSE| The category of crime committed.| This attribute is redundant with OFFENSE_Code. It will be stored off for its labels.|
|METHOD| The category of the method used to commit the crime.| This attribute is redundant with METHOD_Code. It will be stored off for its labels.|
|DISTRICT| The police district.| This attribute was replaced earlier preprocessing to create DistrictID.|
|PSA| Police Service Area| This attribute was replaced earlier preprocessing to create PSA_ID.|
|WARD| The political Ward identifier.| WARD can be derived from NEIGHBORHOOD_CLUSTER which provides a smaller geographic resolution.|
|CENSUS_TRACT| Land management tract identifier.| This attribute is superceded by other geographical data.|
|VOTING_PRECINCT| Political subdivision| This attribute is superceded by other geographical data.|
|CCN| Criminal Complaint Number - unique to each report| An index for the crime report.|
|XBLOCK| Eastern coordinate of crime scene (meters)| This attribute is superceded by lattitude and longitude.|
|YBLOCK| Northern coordinate of crime scene (meters)| This attribute is superceded by lattitude and longitude.|
|START_DATE| The earliest the crime *might* have been committed.| END_DATE provides a more accurate time when considering unwitness crimes.|
|DistrictID| The police district.| Redundant with PSA_ID. DistrictID can be derived from PSA_ID.|
|SHIFT_Code| The duty shift that responded to the call.| This is an eight hour window that is too coarse grain.|
|METHOD_Code| The coded method used to commit the crime.| Over 90% of the crimes are coded OTHER so this attribute is useless.|
|CRIME_TYPE| The code for the type of crime. This attribute can be determined from OFFENSE_Code.|
|AGE| The difference in end data and start date of the crime.| This attribute is unreliable due to the discrepency in start dates.|
|TIME_TO_REPORT| The time it took for the police to report the crime.| This attribue represents action after the crime.|


#### Attributes to Keep
The below table provides a description of attributes that will be used for predicting crimes in DC.

|Attribute|Description|Role|
|:------|:----------------|:----:|
|ANC| Advisory Neighborhood Commission that is a geo-political grouping. This is our target attribute for task 2.| Feature and Target|
|NEIGHBORHOOD_CLUSTER|Neighborhood identifier that subdivides police wards.| Feature|
|END_DATE| The latest the crime *might* have been committed. This attribute will be broken down into day of week, month of year, and hour of the day.| Features|
|PSA_ID| Police Service Area that breaks down WARDS differently than ANC and NEIGHBORHOOD_CLUSTER.| Feature|
|OFFENSE_Code| The category code of crime committed. This is our target attribute for task 1.| Feature and Target|
|Latitude| The angular distance of the crime North of the earth's equator| Feature|
|Longitude| The angular distance of the crime West of the meridian at Greenwich, England| Feature|



#### Attributes  Added to the crime incident report from different sources

Our team was able to acquire data on the unemployment rates and housing prices for each of the 8 wards based on year. Of course, no data comes into play without the need for sufficient munging! A separate excel file was created to help fill the gaps with a multitude of INDEX/MATCH functions accross several sheets. The unemployment rates were also incomplete in a sense it was only yearly for the 8 wards only, but the housing prices data  we were using different informations for cross validation. 

Our team felt it was important to bring to light a characteristic about Theft and Robbery which may not be so apparent just by looking at the data set. It is important to take note that while Theft and Robberies may have a higher rate in certain neighborhoods, it is likely that those who are committing the crime most likely live in a completely separate region. It is highly unlikely that a suspect would steal from their neighbors, risking the higher chance of being caught with readily recognizable stolen goods. On the other hand, those areas which may have a higher drug use may experience exactly this as the neighborhood may have a different dynamic with respect to a communal mindset which may exist in other neighborhoods. As is usually the case, if there were more data readily available about the suspect as well as the victimology involved, there very well may be the possibility of being able to measure these aspects.

![Ward Map](images/ancMapExample.png "ANC Map") 
<p style='text-align: center;'>
Imputed data for ANC Map
</p>

The below table provides a description of attributes that will be added for predicting crimes in DC. Do these features help us predic a class of a crime?

|Attribute|Description|Type|Role|
|:------|:----------------|:---|:----:|
|Housing_Prices| Sales prices of the homes per WARD | Continuous| Feature|
|Unemployment| Unemployment rate per WARD | Continuous| Feature|
|CRIME_MONTH|The latest month the crime was comitted.| Ordinal| Feature|
|CRIME_DAY| The latest day the crime was committed.| Ordinal| Feature|
|CRIME_HOUR| The latest hour the crime was committed.| Oridinal| Feature|


#### Dataset Explanations
we have two potential response variables: Crime_Type (nonviolent crime vs. Violent crime), and Offense_Code (The more specific type of offense: Homicide, Robbery, Theft, Arson, etc.). The goal is to provide the Metropolitant police Department with a model that can predict or classify a crime based on the available explanatory variables.

One problem with this data is that the victim profile data is missing (due to privacy concerns, and the fact that non violent crimes are not necessarily because of the owner's profile). The explanatory variables for this dataset focus on time and locations. We believe that the detection/classification of a Violent crime would be based primarily on the victim's characteristics, and not exclusively on the location or time. The other problem with this data is that (fortunately) there are far fewer violent crimes than there are nonviolent crimes (approximately 83% of the 36000+ crime reports are against nonviolent rather than persons), so we have very imbalanced classification task.

Our exploration of the variables seem to indicate that time (not necessarily the day, but the time during the day) is one of the more significant factors. We saw this in the SHIFT variable (which gives the Police duty shift that responded to the call). When we broke the time down into individual hours of the day, we saw a pronounced cyclic effect, where night-time crimes were far more likely than daytime crimes. Weekend crimes were slightly more likely than crimes during the work week, and monthly trends appeared to be opposite intuition (fall crimes were more likely than winter or summer crimes).

Location also appeared to have some influence, but the way the locations were grouped altered the effect significantly. Different political areas (Wards and the subordinate Association Neighborhood Committees) showed a different trend than using global locations (Latitude and Longitude). Police districts (and their subordinate Police Service Areas(PSA) showed a different trend than the Ward/ANC grouping. This tells us that there are some location effects, but it is difficult to separate them out due to the correlation between geo-physical areas and the different (but overlapping) political mappings.

From what we can tell,the existing variables are not able to properly perform the classification tasks alone. As such, we have looked at including other data to attempt to fill in the picture more completely. As mentioned before, victim profile would be interesting and probably very helpful, but we would not be able to get access to that due to privacy concerns.  For this lab, the focus will be on classifying the Offense_Code (type of offense) classification instead of the type of crime, Crime_Type (nonviolent vs. Violent crime)  and classifying the ANC classification . Our tasks for this lab will be to leverage the crime data plus other supplimental data to predict the class of crime and the ANC where the crime was comitted.