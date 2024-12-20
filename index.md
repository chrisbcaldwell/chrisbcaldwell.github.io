## Selected Projects

---

### Building a graph database using EdgeDB

I built a graph database in EdgeDB from Yelp data of Chicago business reviews.  Data was supplemented with Google Maps location data using the Google Maps API.
<br>
<br>
<img src="images/schema.png?raw=true"/>

<img src="https://img.shields.io/badge/-EdgeDB-white"> <img src="https://img.shields.io/badge/-Python-white?logo=python&logoColor=3776AB"> <img src="https://img.shields.io/badge/-pandas-white?logo=pandas&logoColor=150458">

[View code on Github](https://github.com/chrisbcaldwell/Chicago_Yelp_EdgeDB)

---

### Implementing a custom data collection pipeline of American football player scouting reports using rvest

NFL.com hosts [archived scouting reports](https://www.nfl.com/prospects/richard-sherman/32005348-4566-9604-dee9-7cd0f304c5df) for college players ready to be selected in the annual NFL draft.  With an eye toward NLP analysis of words or phrases that can be linked to players who perform better or worse than their draft selection order, I built a data collecting script in R using the rvest package.
<br>
<br>
<img src="images/nfldraftdataframe.png?raw=true"/>
Note: NFL.com has changed the naming schema of these pages considerably since this project was implemented; the logic for parsing through the various pages in this repository will not work with the current format.

<img src="https://img.shields.io/badge/-R-white?logo=r&logoColor=276DC3"> <img src="https://img.shields.io/badge/-Tidyverse-white?logo=tidyverse&logoColor=1A162D">

[View code on Github](https://github.com/chrisbcaldwell/nfl_draft)

---

### Sentiment analysis project: Can consumer reviews be used to predict sentiment of other natural language applications?

Undergraduate capstone project training a SVM model with sentiment-graded reviews from IMDB, Amazon, and Yelp.  It was great at detecting negative sentiment but not so great at detecting positive sentiment.  There are probably just more ways to say you like something than to say you don't like something, so the negative words bear greater weight.
<br>
<br>
Top 10 most influential words in the model:
<img src="images/topinfluentialterms.png?raw=true"/>


<img src="https://img.shields.io/badge/-R-white?logo=r&logoColor=276DC3"> <img src="https://img.shields.io/badge/-Tidyverse-white?logo=tidyverse&logoColor=1A162D">

[View code on Github](https://github.com/chrisbcaldwell/SVM_Sentiment_Analysis)

---

### Applying control charts to medical utilization analysis

[Control charts](https://asq.org/quality-resources/control-chart) have their origin in quality control of manufacturing processes.  In my consulting book of business we're frequently monitoring for changes in utilization, and this old QC technique works great to visually illustrate that.  Charts are generated with a few clicks from a template I created for our claims data warehouse as an Excel download.
<br>
<br>
<img src="images/controlchart.png?raw=true"/>
Note: Because this was a proprietary project, output is based on simulated data. Supporting files/methods are not available to be shared.

<img src="https://img.shields.io/badge/-Excel-white?logo=microsoftexcel&logoColor=217346">


---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
