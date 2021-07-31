# Day One Relief - Call For Code
### Day One Relief Solutions - Risk Analysis, Prediction and Preparedness for Disaster Relief

<img src="readme/day1call.png" />

### Day One Relief - Supporting community resiliency through all stages of disaster
 
<img align="right" width="375" height="250" src="readme/day1pics.png">
 
Through strong community relationships, Day One Relief serves disaster-impacted populations. Since each disaster is unique, a relief solution that is predictable, repeatable and systematic in nature has been identified as what�s needed to make an improved impact.

Day One Relief was founded in September 2018, during Hurricane Florence, in order to rapidly source and deliver supplies via air and road to those affected by the storm. Our formation came as a result of our efforts spearheading the rapid response at the TAC AIR terminal at RDU. We brought together volunteer pilots and NGOs who have been on the ground in eastern NC, some for 45+ years. We raised the supply and engaged the community, resulting in 1500 volunteers throughout the week.

We are working on creating racial equity in the vaccine rollout. We are phonebanking, canvassing, and helping organize vaccine clinics with vaccine providers, HBCUs and DHHS. 




## Contents

- [Day One Relief Solutions](#project-name) 
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [IBM Services Used](#iBM-services-used)
  - [Open Data Sources used](#open-data-sources-used)
  - [The architecture](#the-architecture)
  - [Long description](#long-description)
  	- [Web Based Dashboard](#web-based-dashboard)
  	- [Jupyter Notebook Analysis](#jupyter-notebook-analysis)  
  	- [Data extract scripts](#data-extract-scripts)
  - [Demo video](#demo-video) 
  - [Project roadmap](#project-roadmap)
  - [Getting started](#getting-started)
  - [Built with](#built-with)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  

# Project Name
### Day One Relief Solutions


## Short description

### What's the problem?

When hurricanes strike, large relief organizations are too cumbersome  to meet the rapidly shifting demands of a disaster scenario and often fail to reach the most vulnerable communities in time. Day One focuses on BIPOC and other underserved communities, using IBM technology to determine where relief is needed. Most often, that relief takes the form of drinkable water . The solution we�ve designed  cuts to the heart of the clean water issue, identifying the regions where clean water access is lacking and then facilitating distribution of drinking water to the BIPOC communities hardest hit by the disaster.

The scope of the disaster is usually larger than the hurricane itself. Flooding may continue for days or weeks, stranding communities and contaminating water bodies and groundwater. Hurricane Floyd (1999) demonstrated how environmentally destructive this phenomenon can be. The floods killed millions of farm animals and flushed millions of tons of animal waste from lagoons into the water supply, polluting tributaries and the Cape Fear River. The state was forced to order portable incinerators be flown in from out of state in order to deal with all the rotting animal carcasses.

For Day One Relief and its partner NGOs, toughest challenge, however, might be coming up. COVID-19 is surging in the South. And this year�s hurricane season, which started in June and continues through November, is predicted to be harsher than usual. 

<b>How do you not only keep people safe after their homes have been destroyed, but also keep them socially distant? And how do you keep your volunteers safe when they enter coronavirus hotspots? <br />How do you provide drinking water to the communities in need in the aftermath of a natural disaster?</b>


### How can technology help?

Fatalities and injuries from natural disasters can be reduced if the disaster can be predicted and advance warning given to people in the danger zone. I
In recent times, technology has been employed to fast track disaster relief efforts.Awareness, education, preparedness, and prediction and warning systems can reduce the disruptive impacts of a natural disaster on communities. Technology can also help identify the most vulnerable communities, relief organizations will have the ability to prioritize the most vulnerable without spending precious hours on manual risk assessment.

Gaining access to clean, safe water is one of the first priorities after a natural disaster. During a natural disaster, water supplies including drinking water wells can be contaminated with anything from livestock waste to chemicals. Technology can help evaluate where and when water and other supplies are required, getting there just after the storm does.It can also reduce the frequency of wasteful response efforts.

### The idea

<img align="right"   src="readme/cleanwater.png"> 

A web based dashboard which show all data points, forecasts, power outages - everything is in one place, constantly updating, so that decisions can be made faster and smarter. Other disaster relief groups can customize this platform to better understand their respective geographical regions by tracking weather patterns, COVID-19 cases and locations of the poorest, most vulnerable people, as well as sites of hospitals, airports, private airstrips and warehouses.


We intend to allow easy integration of new data so that stakeholders may prioritize hazards or distribution points most crucial to them. For example, concentrated animal feeding operations, or hog farms, which are ubiquitous in North Carolina, can become severe risks during flood events when tons of manure and waste water are discharged into clean water sources. The EPA provides data and locations for the whole state and once these data sets are loaded, Watson could tell us which zones are likely to face contamination of drinking water, often a major issue in the aftermath of heavy storms.  

##### Clean water after heavy rains or floods

Day One Relief Solutions addresses the problem of providing clean water by creating insights as to where clean water will be needed in the aftermath of a natural disaster. Day One�s experience shows many impacted communities will lack access to drinkable water and means of proper sanitation�made even more important by the surge in cases of the Covid-19 Delta variant. The platform consolidates thousands of static data sets with multi-hazard dynamic risk analysis onto an easily digestible web dashboard that disaster response leaders can use to prioritize the most vulnerable during relief efforts. DORS use Watson Studio to analyze weather forecasts in conjunction with our county level data, (e.g., local power outages, elevation, CDC SVI (Social Vulnerability Index), and the FEMA NRI (National Risk Index)) in order to determine which counties will be most impacted by a storm. Day One integrates statewide animal feed operations locations, as well as dams and watersheds, to better understand which communities are most susceptible to prolonged flooding and water contamination. In the future, Day One intends to develop a more sophisticated algorithm to output our own index of social vulnerability which updates in sync with our dynamic layers.

Using the insights our platform provides, relief efforts will be far more organized than was previously possible. With access to high-quality weather data and forecasts from TWC APIs and Watson�s predictive modeling, we can readily identify which communities will be in the path of the storm and notify them ahead of time. Day One knows exactly which shelters will be safe for emergency and the process of getting them supplied is expedited significantly. DORS also will reduce the frequency of wasteful relief efforts in cases where the storm�s path changes.

In Summary, by applying IBM Watson, TWC and Machine Learning technologies, the Day One Relief Solution will prioritize disaster response efforts and the distribution of clean water when and where these are urgently required to save lives of the most vulnerable communities.  


## IBM services used

<ol>
<li>IBM Cloud for Web-App Deploy</li>
<li>IBM Websphere Liberty web server</li>

<li>IBM Cloud PAK For Data
<ul>
<li>Watson Studio - Jupyter Notebook for data extraction, cleansing and prediction analysis</li>
<li>Auto-AI for analyzing  weather forecast data and generating candidate machine learning models </li>
</ul>
</li> 

<li>The Weather Company (TWC) Apis for Storm/Hurricane Forecasts</li>
</ol>
 
 
## Open data sources used
<ul><li><a href="https://www.atsdr.cdc.gov/placeandhealth/svi/index.html">CDC/ATSDR Social Vulnerability Index</a></li></ul>
<ul><li><a href="https://www.fema.gov/flood-maps/products-tools/national-risk-index">FEMA National Risk Index for Natural Hazards & Flood Index</a></li></ul> 
<ul><li><a href="https://deq.nc.gov/about/divisions/water-resources/water-quality-permitting/animal-feeding-operations">Animal feeding operations across North Carolina provide by The North Carolina Department of Environmental Quality</a></li></ul> 
<ul><li><a href="https://www.usgs.gov/core-science-systems/ngp/national-hydrography/watershed-boundary-dataset?qt-science_support_page_related_con=4#qt-science_support_page_related_con">Wastershed data provided by USGS.gov</a></li></ul> 

<ul><li><a href="https://api.weather.gov/alerts/active?area=NC">NWS - Current Alerts For North Carolina</a></li> </ul>
<ul><li><a href="https://api.weather.gov/alerts">NWS - Current Temperatures & Forecast for North Carolina Cities</a></li> </ul>
<ul><li><a href="https://www.usgs.gov/core-science-systems/national-geospatial-program/national-map">USGS - Elevation Data for North Carolina</a></li> </ul>
<ul><li><a href="https://data.cdc.gov/resource/8xkx-amqh.json?recip_state=NC">Vaccination Data from CDC for North Carolina</a></li> </ul>
<ul><li><a href="https://developer.foursquare.com/docs/places-api">Four-Square APIs for North Carolina Venues</a></li></ul>


## The architecture
<img src="readme/arch.png" />


## Long description


### Day One Relief - Call for Code submission contains below projects 

1.	A Interactive Web Based Dashboard of North Carolina
2.	Jupyter Notebook based prediction - Predict which NC counties will be most at risk from a Hurricane or Tropical Storm 
3.  Data Extract Scripts


### Web Based Dashboard

Success of disaster preparedness in sometime depends more on effective local response. With that in mind, we created a State/County Dashboard For North Carolina. User can select a county, and- the dashboard will be customized for that selection.
State view will have the ability to select all alerts for the state, points of interest, and various indexes by county. 
County view will provide all indexes and alerts, as well as relevant information like population and population density. In addition, users can select venues such as parks and schools.
 
Currently we have only North Carolina and its counties enabled but we are in the process of adding other states, starting with Florida, Texas.

In the Situational awareness you can see SVI. Social vulnerability refers to the potential negative effects on communities caused by external stresses on human health. Such stresses include natural or human-caused disasters, or disease outbreaks. Reducing social vulnerability can decrease both human suffering and economic loss. The <a href="https://www.atsdr.cdc.gov/placeandhealth/svi/index.html">CDC/ATSDR Social Vulnerability Index (CDC/ATSDR SVI)</a> uses 15 U.S. census variables to help local officials identify communities that may need support before, during, or after disasters

<img src="readme/svi.png" />

FEMA calculated NRI - The National Risk Index  to help illustrate the nation�s communities most at risk of natural hazards. It is made possible through a collaboration between FEMA and dozens of partners in academia; local, state and federal government; and private industry.  The Index leverages best available source data to provide a holistic view of community-level risk nationwide by combining multiple hazards with socioeconomic and built environment factors. It calculates a baseline relative risk measurement for each United States county and census tract for 18 natural hazards, based on Expected Annual Loss, Social Vulnerability, and Community Resilience. We are also showing flood index calculated by FEMA based on historic flood loss in that region.

<img src="readme/nri.png" />


The dashboard also shows shows a heatmap of current Covid Numbers by county, and the percentage of eligible population fully vaccinated - data provided by CDC.

<img src="readme/cdc.png" />


When it comes to Flooding due to heavy rains or storms, elevation of the location plays a major role, so we are also showing elevation data for North Carolina provided by USGS, 

<img src="readme/ele.png" />

And Critical locations, Venues and current temperatures & daily forecast for top cities for each county.
<img src="readme/loc.png" />
<img src="readme/ven.png" />
<img src="readme/tem.png" />

##### Animal Farm locations provided by NC.Gov's Department of Environmental Quality's Animal Feeding Operations Program 

The N.C. Department of Environmental Quality's Animal Feeding Operations Program has regulated animal operations (swine, cattle, horses and liquid waste treatment system poultry) and established siting requirements for application setbacks from property boundaries and perennial streams since 1992.  In order to protect North Carolina�s waters from pollution, the state Environmental Management Commission (EMC) supports the evaluation of potential impacts from many different sources. We intend to use this locations to determine which zones are likely to face contamination of drinking water, often a major issue in the aftermath of heavy storms.  

<img src="readme/animalfarms.png" />



And Watershed locations provided by USGS.gov

<img src="readme/watershed.png" />



### Jupyter Notebook Analysis

In the IBM Cloud Pak for Data - IBM Watson Studio, you can create Python, Scala, and R notebooks to analyze your data.Jupyter notebooks provide an interactive computational environment for developing Python based Data Science applications. Jupyter notebooks can illustrate the analysis process step by step by arranging the stuff like code, images, text, output etc. in a step by step manner. We are using Watson Studio Jupyter Notebook for predicting which NC counties will be most at risk from a Hurricane or Tropical Storm.

With all the data and indexes available , we  can calculate which areas will need more attention in case of a hurricane,  We are doing this for a Zip code level, North Carolina has 802 zip codes, based on SVI, NRI, Population and the elevation data, we can calculated the most vulnerable areas. Next based on 15 day Forecast from National Weather Service and National Hurricane Service, we can calculate the areas that will need more focus. Finally, if any ot the areas is facing power outages, we can highlight that.

#### Unclassfied alerts for North Carolina from National Weather Service
<img src="readme/unclassf.png" width="1000px" height="400px" />


### For analyzing  weather forecast data and generating candidate machine learning models, we used Watson Studio AutoAI Experiment
##### AutoAI Experiment Recommended LGBM Classfier
<img src="readme/modelrecm.png"  /> 


#### Custom built LogisticRegression Model provided better accuray, 
##### LogisticRegression Model Accuracy, Precision, Recall, Confusion matrix
<img src="readme/modelacc.png"  width="500px" height="400px" />


#### Classfied alerts for North Carolina from National Weather Service, drawn over current power outages
<img src="readme/classf.png" />


### Data extract scripts

For this project, we are using data from many datasources, in different formats like csv, json etc. To generate high-quality analysis we need to ensure that we are cleaning data in order to accurately represent the dataset. Pandas offer a diverse range of built-in functions that can be used to clean and manipulate datasets prior to analysis. It can allow you to drop incomplete rows and columns, fill missing values and improve the readability of the dataset through category renaming.

Foursquare API provides a range of tools for developers to incorporate the up-to-date location data to enhance their projects. The Places API offers real-time access to Foursquare�s global database of rich venue data and user content to power location-based experiences in app. In this project, we are using the Places API for extracting venues like Parks, Schools, Churches in North Carolina.

Python Web scraping is a technique to automatically access and extract large amounts of information from a website. In this project, we are using web scraping to extract power outage information for North Carolina


## Demo video  
[![Demo](readme/nrithumb.png)](https://www.youtube.com/watch?v=8TwQTW77duA)


## Project roadmap

Our state dashboard consolidates thousands of static data sets with multi-level dynamic risk analysis onto an easily digestible dashboard that disaster response leaders can use to prioritize the most vulnerable during relief efforts. 

Moving forward: With IBM�s powerful cognitive computing technology, we aim to utilize Watson�s machine learning capabilities to generate a single composite metric of risk based on the numerous variables specific to each zone on the state dashboard�counties or zip codes in the future. Then, at the time of a risk event, Watson�s algorithm will provide the user with a score for each zone, highlighting those areas which are most at risk, and allowing users to spend precious hours on directing relief efforts rather than losing time on complex risk assessment done manually. 

We intend to allow easy integration of new data so that stakeholders may prioritize hazards or distribution points most crucial to them. For example, concentrated animal feeding operations, or hog farms, which are ubiquitous in North Carolina, can become severe risks during flood events when tons of manure and wastewater are discharged into clean water sources. The EPA provides data and locations for the whole state and once these data sets are loaded, Watson could tell us which zones are likely to face contamination of drinking water, often a major issue in the aftermath of heavy storms. 

With enough data, Watson should be able to produce a more accurate index of social vulnerability than is displayed by either the CDC�s SVI or FEMA�s NRI, due to the thoroughness and speed by which risk assessment may be calculated algorithmically. 

<img  src="readme/c4croadmap.png" width="600px" height="1500px" />



## Getting started

### Developing and Deploying using Eclipse

IBM� Eclipse Tools for Bluemix� provides plug-ins that can be installed into an existing Eclipse environment to assist in integrating the developer's integrated development environment (IDE) with Bluemix.

1. Download and install  [IBM Eclipse Tools for Bluemix](https://developer.ibm.com/wasdev/downloads/#asset/tools-IBM_Eclipse_Tools_for_Bluemix).

2. Import this app into Eclipse using `File` -> `Import` -> `git import` -> `clone url` option.

3. Create a Liberty server definition:
  - In the `Servers` view right-click -> `New` -> `Server`
  - Select `IBM` -> `WebSphere Application Server Liberty`
  - Choose `Install from an archive or a repository`
  - Enter a destination path (/Users/username/liberty)
  - Choose `WAS Liberty with Java EE 7 Web Profile`
  - Continue the wizard with default options to Finish

4. Run your application locally on Liberty:
  - Right click on the `stateori`  and select `Run As` -> `Run on Server` option
  - Find and select the localhost Liberty server and press `Finish`
  - In a few seconds, your application should be running at http://localhost:9080/stateori/

5. Create a Bluemix server definition:
  - In the `Servers` view, right-click -> `New` -> `Server`
  - Select `IBM` -> `IBM Bluemix` and follow the steps in the wizard.\
  - Enter your credentials and click `Next`
  - Select your `org` and `space` and click `Finish`

6. Run your application on Bluemix:
  - Right click on the application and select `Run As` -> `Run on Server` option
  - Find and select the `IBM Bluemix` and press `Finish`
  - A wizard will guide you with the deployment options. Be sure to choose a unique `Name` for your application
  - In a few minutes, your application should be running at the URL you chose.


7. To deploy the application on IBM Cloud:
	
	[![Deploy to IBM CLOUD](readme/ibmcloud.png)](https://bluemix.net/deploy?repository=https://github.com/IBM-Bluemix/java-helloworld)
	

## Authors

1. Jil Christensen
2. Nikita Nangia
3. Zachary Haugan
4. Isshaan Oren Pilant

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
- How to create and deploy a simple [webapp on IBM Cloud](https://github.com/IBM-Cloud/java-helloworld).








 
 
  