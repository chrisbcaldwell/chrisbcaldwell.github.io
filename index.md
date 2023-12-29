## Selected Projects

---

### Applying control charts to medical utilization analysis

[Control charts](https://asq.org/quality-resources/control-chart) have their origin in quality control of manufacturing processes.  In my consulting book of business we're frequently monitoring for changes in utilization, and this old QC technique works great to visually illustrate that.  Charts are generated with a few clicks from a template I created for our claims data warehouse as an Excel download.
<br>
<br>
<img src="images/controlchart.png?raw=true"/>
Note: Because this was a work project, output is based on simulated data to protect privacy. Supporting files are not available to be shared.

<img src="https://img.shields.io/badge/-Excel-white?logo=microsoftexcel&logoColor=217346">

---

### Implementing a custom data collection pipeline of American football player scouting reports using rvest

NFL.com hosts [archived scouting reports](https://www.nfl.com/prospects/richard-sherman/32005348-4566-9604-dee9-7cd0f304c5df) for college players ready to be selected in the annual NFL draft.  With an eye toward NLP analysis of words or phrases that can be linked to players who perform better or worse than their draft selection order, I built a data collecting script in R using the rvest package.
<br>
<br>
<img src="images/nfldraftdataframe.png?raw=true"/>
Note: NFL.com has changed the naming schema of these pages considerably since this project was implemented; the logic for parsing through the various pages in this repository will not work with the current format.

<img src="https://img.shields.io/badge/-R-white?logo=r&logoColor=276DC3"> <img src="https://img.shields.io/badge/-Tidyverse-white?logo=tidyverse&logoColor=1A162D">

[View code on Github](/nfl_draft)

---
