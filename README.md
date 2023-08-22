
<!-- PROJECT LOGO -->

<div id="header" align="center">
  <img src="https://www.thetimes.co.uk/imageserver/image/%2Fmethode%2Fsundaytimes%2Fprod%2Fweb%2Fbin%2F585c7df6-09d8-11e9-b1bd-14088db4a37a.jpg?crop=2667%2C1500%2C0%2C0&resize=1200" width="480" height="339" />
  <h1>
<h3 align="center">Recession to Recovery?</h3>

  <p align="center">
    Economic growth and social decline in post-recession Dublin.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#what">What?</a></li>
         <li><a href="#why">Why?</a></li>
        <li><a href="#how">How?</a></li>
      </ul>
    </li>
    <li><a href="#conclusions">Conclusions</a></li>
    <li><a href="#sources">Sources</a></li>
    <li><a href="#feedback">Feedback</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- WHAT -->
### What?
An analysis of social and economic trends in Dublin city since the beginning of the millenium, in an attempt to contextualise and therefore better understand the current housing crisis.

<!-- WHY -->
### Why?
* As an Irish person I often have conversations with my family and friends about this topic, as it's widely discussed in news media and has recently gained momentum due to housing protests in the city. I have felt increasingly motivated to investigate the numbers for myself, comparing social and economic factors to shed light on how this dire situation came to be.
  
* I have also dealt with similar themes in the past; in 2016 my Bachelor's thesis examined the dwindling cultural landscape of the city as a direct result of foreign multinational investment and un-checked property development. However, at this time I didn't have the tools required to do an in-depth analysis using raw data, which limited in my scope.
  
* This is no longer the case. In this project I have used my recently acquired Data Analysis tools to source and process government datasets, revealing my own findings. 

<!-- HOW -->
### How?

I sourced ~65 raw datasets, which I cleaned and wrangled using Python and Pandas in Jupyter Notebooks. 

The datasets followed a range of different methodologies, often with differing measure values, formats and timeframes within the same data series. 

For example, some were number counts (homeless adults at a given time, or number of people in specific age groups etc.), whereas others were percentages of the total population, or percentages of a total in a given measure (percentage of recipients of social housing referred by homeless services, percentage of people living at risk of poverty who are renting at market rates, etc.)

In light of this the data preparation process was long and arduos, but also extremely rewarding. 

The clean datasets were divided into the following categories:
#### Population
- Total population per Census Year by age group. 
- Percentage change per Census Year.
#### Economic
- Annual average rent.
- Annual average income.
- Annual corporation tax revenue.
#### Housing
- Social housing program statistics.
- Homelessness reports.
- Percentage of Young Adults living at home.
#### Poverty
- Poverty risk and tenure status.
- Poverty risk and economic status.
- Poverty risk and age group.

  
I used Tableau to further investigate and visualise these datasets, then collected and presented my findings in an animated slide format using Keynote. 
This can be viewed in the [Presentation folder.](https://github.com/KatyAnnG/recession_to_recovery/tree/main/Presentation)
The visualisations shown in the presentation can be examined more closely in the [Visualisations folder.](https://github.com/KatyAnnG/recession_to_recovery/tree/main/Visualisations)

I did not use every dataset in the resulting presentation, however I now have a mine of information on file for further investigation.

<!-- INVESTIGATED WITH -->
## Investigated With

* ![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
* ![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
* ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
* ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONCLUSIONS -->
## Conclusions

* Ireland has changed irrevocably since the advent of the 1999 Finance Act, which changed corporate tax policy to allow foreign multinationals to reroute funds through the country at a negligible rate of 2.5-4.5%. This policy has led to massive foreign investment.

* Dublin City has experienced rapid growth and development due to the influx of foreign multi-national HQs. Resulting rent price increases make it extremely difficult to start out as a young adult in rented accommodation.
  
* The COVID-19 pandemic was instrumental in showing that measures can be taken to apprehend or reverse the situation; however these measures were abandoned as soon as it was deemed reasonable to do so. As a result, homelessness rates have increased at record levels since the pandemic receded.
  
* Those that have the privilege of a stable family home are often staying there into their 30’s. 
Those that can move abroad, do so.
Those that can do neither become homeless.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SOURCES -->
## Sources

* [Population](https://data.cso.ie/table/FY001)
* [Population Percentage Change](https://data.cso.ie/table/FY003B)
* [Corporation Tax Revenue](https://data.cso.ie/table/ITXS01)
* [Average Rent](https://data.cso.ie/table/RIA02)
* [Average Income](https://stats.oecd.org/viewhtml.aspx?datasetcode=AV_AN_WAGE&lang=en#)
* [Young Adults Living at Home](https://ec.europa.eu/eurostat/databrowser/view/ILC_LVPS08$DV_1041/default/table?lang=en&category=yth.yth_demo)
* [Homelessness Reports](https://data.gov.ie/organization/department-of-housing-planning-community-and-local-government?tags=homelessness&_tags_limit=0)
* [Social Housing](https://data.cso.ie/product/hhwl)
* [Poverty](https://data.cso.ie/table/SIA32)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Feedback -->
## Feedback

Any feedback is **greatly appreciated**. You can contact me via the links below, or simply open an issue with the tag "feedback".

Thanks again, and don't forget to give the project a star!

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Katy Gaffney 
<div id="badges">
  <a href="https://www.linkedin.com/in/katyanngaffney/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:katyanngaffney@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge"/>
  </a>
</div>

Project Link: [https://github.com/KatyAnnG/recession_to_recovery](https://github.com/KatyAnnG/recession_to_recovery)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Thank you to Aga and Alex, my wonderful tutors, and to [Blindboy Boatclub](https://www.theblindboypodcast.ie/) for [his work on the topic](https://play.acast.com/s/blindboy/howtosolvethehousingcrisis). 

<p align="right">(<a href="#readme-top">back to top</a>)</p>
