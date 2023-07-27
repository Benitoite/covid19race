# Covid-19 & Race
## Notebooks comparing U.S. Census Bureau demographic and County of Santa Clara Covid-19 health data

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Benitoite/covid19race/HEAD)

<img src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/maps.gif" height="310" /><img height="310"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figs.gif" />

## Richard Eldon Barber | [`kd6kxr@gmail.com`](mailto:kd6kxr@gmail.com)
### 11 September 2021 | `/DTG//110630USEP21  //RB21911001/`

#### Sources:

* #####     [https://data.sccgov.org/](https://data.sccgov.org/) *via* Socrata API
* #####     [https://data.census.gov/](https://data.census.gov/) *via* python API 
   * Table Elements [B02001_002E](https://api.census.gov/data/2016/acs/acs5/groups/B02001.html), [B03001_003E](https://api.census.gov/data/2016/acs/acs5/groups/B03001.html), [B02015_001E](https://api.census.gov/data/2016/acs/acs5/groups/B02015.html)
 
#### Census Tract Reference Plot:

* ##### [https://www2.census.gov/geo/maps/DC2020/PL20/st06_ca/censustract_maps/c06085_santa_clara/DC20CT_C06085.pdf](https://www2.census.gov/geo/maps/DC2020/PL20/st06_ca/censustract_maps/c06085_santa_clara/DC20CT_C06085.pdf)

#### Licensing:

* ##### [GNU Affero V3 2017](https://raw.githubusercontent.com/Benitoite/covid19race/main/LICENSE)

<hr>

|   Contents:   |
| -----  |
|  [Covid-19 Mapping](#covid-19-mapping)  |
|     |
|  [Covid-19 Racial Analyses](#covid-19-racial-analyses)  |
 
<hr>

## Covid-19 Mapping

#### [https://github.com/Benitoite/covid19race/blob/main/covid19map.ipynb](https://github.com/Benitoite/covid19race/blob/main/covid19map.ipynb)
#### [https://github.com/Benitoite/covid19race/blob/main/covid19map-asia.ipynb](https://github.com/Benitoite/covid19race/blob/main/covid19map-asia.ipynb)

* Notebook generating maps for Covid-19 Positivity, Case Rate, Race Demographics by Census Tract
    
| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/map5.png"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/map9.png"> |
| :---: | :---: |
| *Figure M1. Case Rate* | *Figure M2. Test Positivity Rate* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/map6.png"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/map8.png"> |
| :---: | :---: |
| *Figure M3. Percent Hispanic Responses* | *Figure M4. Percent White-Only Responses* |


| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mapcase.png"> |
| :---: |
| *Figure M1a. Case Rate Contextual Map* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mappos.png"> |
| :---: |
| *Figure M2a. Test Positivity Rate Contextual Map* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/maphisp2.png"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/maphisp.png"> |
| :---: | :---: |
| *Figure M3a. Percent Hispanic Responses Contextual Map* | *Figure M3b. Percent Hispanic Responses Topo Map* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mapwhite2.png"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mapwhite.png"> |
| :---: | :---: |
| *Figure M4a. Percent White-Only Responses Contextual Map* | *Figure M4b. Percent White-Only Responses Topo Map* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mapasia2.png"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mapasia.png"> |
| :---: | :---: |
| *Figure M6a. Percent Asian Responses Contextual Map* | *Figure M6b. Percent Asian Responses Topo Map* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/map7.png"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/mappopden.png"> |
| :---: | :---: |
| *Figure M5. Population Density* | *Figure M5a. Population Density Topo Map* |

<hr>

## Covid-19 Racial Analyses

|   [White](#white-only)  |  [Hispanic](#hispanic-analysis)   |   [Asian](#asian-analysis)   |
|:--:|:--:|:--:|
| [B02001_002E](https://api.census.gov/data/2016/acs/acs5/groups/B02001.html) | [B03001_003E](https://api.census.gov/data/2016/acs/acs5/groups/B03001.html) | [B02015_001E](https://api.census.gov/data/2016/acs/acs5/groups/B02015.html) |

<hr>

### White-only

#### [https://github.com/Benitoite/covid19race/blob/main/covid19race.ipynb](https://github.com/Benitoite/covid19race/blob/main/covid19race.ipynb)

* Notebook comparing Covid-19 Positivity, Case Rate, and Vacc12 Rates per Census Tract by Percent White Only

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure1.svg"> |  <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure2.svg"> |
| :---: | :---: |
| *Figure 1. Unsorted plot of Case and Positivity Rate data* | *Figure 2. Sorted plot of Case and Positivity Rate data* |
 
| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure2a.svg"> |
| :---: |
| *Figure 2a. Sorted plot of Case Rate data: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure2b.svg"> |
| :---: |
| *Figure 2b. Sorted plot of Positivity Rate data: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure3.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure4.svg"> |
| :---: | :---: |
| *Figure 3. Unsorted plot of Vacc12 data* | *Figure 4. Sorted plot of Vacc12 data* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure4a.svg"> |
| :---: |
| *Figure 4a. Sorted plot of Vacc12 data: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure5.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure6.svg"> |
| :---: | :---: |
| *Figure 5. Unsorted plot of Testing Rate data* | *Figure 6. Sorted plot of Testing Rate data* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure6a.svg"> |
| :---: |
| *Figure 6a. Sorted plot of Testing Rate data: Linear Regression* |

<hr>

### Hispanic Analysis

#### [https://github.com/Benitoite/covid19race/blob/hisp/covid19race.ipynb](https://github.com/Benitoite/covid19race/blob/hisp/covid19race.ipynb)

* Notebook comparing Covid-19 Positivity, Case Rate, and Vacc12 Rates per Census Tract by Percent Hispanic

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure1.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure2.svg"> |
| :---: | :---: |
| *Figure 1h. Unsorted plot of Case and Positivity Rate data* | *Figure 2h. Sorted plot of Case and Positivity Rate data* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure2ha.svg"> |
| :---: |
| *Figure 2ha. Unorted plot of Case Rate data: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure2hb.svg"> |
| :---: |
| *Figure 2hb. Sorted plot of Positivity Rate data: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure3.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure4.svg"> |
| :---: | :---: |
| *Figure 3h. Unsorted plot of Vacc12 data* | *Figure 4h. Sorted plot of Vacc12 data* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure4ha.svg"> |
| :---: |
| *Figure 4ha. Sorted plot of Vacc12 data: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure5.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure6.svg"> |
| :---: | :---: |
| *Figure 5h. Sorted plot of Testing Rate data* | *Figure 6h. Sorted plot of Testing Rate data* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure6ha.svg"> |
| :---: |
| *Figure 6ha. Sorted plot of Testing Rate data: Linear Regression* |

<hr>

### Asian Analysis

#### [https://github.com/Benitoite/covid19race/blob/main/covid19race-asia.ipynb](https://github.com/Benitoite/covid19race/blob/main/covid19race-asia.ipynb)

* Notebook comparing Covid-19 Positivity, Case Rate, and Vacc12 Rates per Census Tract by Percent Asian

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure1aa.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure2aa.svg"> |
| :---: | :---: |
| *Figure 1aa. Unsorted Covid-19 Case and Positivity Rates Per Tract % Asian* | *Figure 2aa. Sorted Covid-19 Case and Positivity Rates Per Tract % Asian* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure3aa.svg"> |
| :---: |
| *Figure 3aa. Covid-19 Case Rates Per Tract % Asian: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure4aa.svg"> |
| :---: |
| *Figure 4aa. Covid-19 Positivity % Per Tract % Asian: Linear Regression* |

| <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure7aa.svg"> | <img width="900px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure10aa.svg"> |
| :---: | :---: |
| *Figure 7aa. Covid-19 Vacc12 Rates Per Tract % Asian: Linear Regression* | *Figure 10aa. Covid-19 Test Rates Per Tract % Asian: Linear Regression* |

<hr>

### Background
The County of Santa Clara is well known for its diverse population. Statistical data regarding certain Covid-19 health markers are made available by the County for analysis through a system of application programming interfaces, or APIs, among other access methods like web apps, comma-separated values, and more. Some data made available by the County are recorded per Census Tract. The information currently available for the County by tract are test rate, positivity rate, case rate, and vacc12 rate (over age 12 vaccinations per population).

### Analysis
Covid-19 Positivity and Case Rate is seen to be inversely correlated to the curve of population who indicated White Alone as their racial identity (Fig. 2).  There appears strong corellation between positivity and case rate with the percent who indicated Hispanic origin (Fig. 2h). There is a spike in cases in some tracts approaching and exceeding 70% White Alone, against the inverse correllation (Fig 2). Vacc12 and testing rates are seen to be definitely not correllated to the race-origin categorizations (Fig. 3-6, 3h-6h).

### Results
These data show us that the County Health educational campaigns for Covid-19 testing and vaccinations most likely did achieve equity. The County may not have fully met Health equity standards vital for moving forward with general economic recovery in terms of test positivity and case rate per populated tract. (ref. https://covid19.ca.gov/equity/)  It is important to identify the factors which cause racial inequities seen graphically in the analysis, and adopt practices moving forward with the goal of saving lives by health equity.

\####
