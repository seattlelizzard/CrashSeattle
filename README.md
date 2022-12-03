# Seattle Crashdata Severity Predictor
![](https://www.accruent.com/static/65e3c5474f1c8667a38d19e94bb89c83/66fec/accruent_resources_case-studies_seattle-city-light_hero.jpg)

In 2015 Seattle created a “Vision Zero” plan to eliminate “traffic deaths and serious injuries on city streets by 2030” (City of Seattle). Vision Zero is an “international street safety movement”  (City of Seattle) that aims to prevent traffic collisions through a “safe system approach” (Vision Zero Network). The city of Seattle has adopted this approach, which emphasizes several aspects of traffic safety including controlling speeding and creating safer streets. However, in the past two years since 2022 “deaths and serious injuries from traffic collisions in Seattle have been trending up” (KUOW). This indicates that the Vision Zero initiatives implemented so far are not enough. For example, Seattle has had a 25-mile-per-hour speed limit on all arterial streets since 2020, but traffic deaths have continued to rise. Speed limits and speeding are one of the leading factors in the severity of collisions (City of Seattle), but other factors including weather, vehicle count, light condition, road condition, and location could impact collision severity. While not all of these factors are under human control, understanding the bigger picture could inform initiatives like street redesigns or programs to help people take alternative modes like transit. This project will use the City of Seattle’s collision dataset to analyze these different factors. 

## Table of contents
- [Seattle Crashdata Severity Predictor](#seattle-crashdata-severity-predictor)
- [Table of contents](#table-of-contents)
- [Dataset](#dataset)
- [Modeling Question](#modeling-question)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Authors](#authors)



## Dataset
[(Back to top)](#table-of-contents)


Dataset is taken from the City of Seattle that includes information about crashes and weather at the time of the crash. 
[Collision Data from Seattle.gov site](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::sdot-collisions-all-years/explore?location=47.641550%2C-122.345216%2C19.74&showTable=true)

To learn more about the dataset, please see the pdf.

[Dataset description](https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf)


## Modeling Question
[(Back to top)](#table-of-contents)

We will be conducting a classfication analysis on our data to try and create a predictor of the number of collisions of a given severity. We will be analyzing 5 variables with a mix of continuous and categorical values:
Vehicle Count: Continuous
Weather: Categorical with 12 variables
Light Condition: Categorical with 9 variables
Road Condition: Categorical with 9 variables
Junction Type: Categorical with 7 variables


## Methods Used
[(Back to top)](#table-of-contents)

* Data Visualization    
* Data Imputation
* Predictive Modeling
* Multi-Class Classification
* Random Search Cross Validation
* Lasso and Rigde Regression
* Random Forest Tree
* XG Boost


## Technologies
[(Back to top)](#table-of-contents)

* Python
* Seaborn
* Matplotlib
* Pandas, Jupyter
* Folium Library : To plot the longitude and latitude of the crash location on the Seattle city map



## Authors
[(Back to top)](#table-of-contents)

- [@Lizz Hunt](https://github.com/seattlelizzard)

- [@Ava Delanty](https://github.com/bobahyun)
    [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/avadelanty)
- [@Akanksha Sharma](https://github.com/akankshasharmadid)
    [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akanksha-12831bb1)
    [![Leetcode](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=LeetCode&logoColor=#d16c06)](https://www.leetcode.com/akanksha185/)

- [@Anna Tsai](https://github.com/atsai)

