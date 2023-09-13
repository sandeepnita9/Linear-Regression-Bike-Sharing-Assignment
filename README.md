# Project : Bike Sharing Demand Prediction
> Bike Sharing Demand Prediction using Linear Regession.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.So they decided to go with data based analysis approach to figure out what is impacting Shared Bike Demands.
- We have received a Survey data which covers a lots of informations about the Bike Sharing Deamnd and associated factors across US
- Business Objective
    - Prepare a Model using the survey data
    - Model will be used to analyze factors that affects Bakie Sharing Demand
    - Business will take help of this Model to plan the activites to manage Future Demands


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Final Modal Equation
- count= 0.5886+(0.2481*yr)-(0.1889*windspeed)-(0.2599*Spring)-(0.0396*Summer)-(0.0764*Winter)-(0.1034*Jan)+(0.0697*Sep)-(0.0462*Tuesday)-(0.2986*Light_Snow)-(0.0859*Mist)

## Top 3 Factor that are affecting Bike Sharing Demand:
- Season : ‘Spring’, ‘Summer’ & ‘Winter’ is having negative coefficient with BikeSharing demand, it indicates that these season have low demand of Bike sharing.
- Month : ‘January’ month is having negative coefficient; it indicates that Bike Sharing demand decreases during Jan month where ‘September’ month is having positive coefficient and have maximum demand of Bike sharing.
- Weather Situation : ‘Light Snow with rain’ and ‘Mist’ weather having negative coefficient which indicates bike sharing demands decreases during these weather conditions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Stats Model (Python Library)
- SkLearn (Python Library)
- Seaborn (Python Library)
- MatPlotLib (Python Library)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@sandeepnita9] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
