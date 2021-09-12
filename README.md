# covid19race
## Notebooks comparing Census data and County of Santa Clara Covid-19 health data
### Richard Eldon Barber `kd6kxr@gmail.com` 2021 September 11
#### Sources:
##### https://data.sccgov.org/ *via* Socrata API
##### https://data.census.gov/ *via* python API
<hr>

### https://github.com/Benitoite/covid19race/blob/main/covid19race.ipynb
    Notebook comparing Covid-19 Positivity, Case Rate, and Vacc12 Rates per Census Tract by Percent White Only


| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure1.svg"></img> |
| :---: |
| *Figure 1. Unsorted plot of Case and Positivity Rate data* |


 
| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure2.svg"></img> |
| :---: |
| *Figure 2. Sorted plot of Case and Positivity Rate data* |
 
| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure3.svg"></img> |
| :---: |
| *Figure 3. Unsorted plot of Vacc12 data* |


| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure4.svg"></img> |
| :---: |
| *Figure 4. Sorted plot of Vacc12 data* |

| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure5.svg"></img> |
| :---: |
| *Figure 5. Sorted plot of Testing Rate data* |


| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/main/Resources/figure6.svg"></img> |
| :---: |
| *Figure 6. Sorted plot of Testing Rate data* |

<hr>

### https://github.com/Benitoite/covid19race/blob/hisp/covid19race.ipynb
    Notebook comparing Covid-19 Positivity, Case Rate, and Vacc12 Rates per Census Tract by Percent Hispanic

| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure1.svg"></img> |
| :---: |
| *Figure 1h. Unsorted plot of Case and Positivity Rate data* |


 
| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure2.svg"></img> |
| :---: |
| *Figure 2h. Sorted plot of Case and Positivity Rate data* |
 
| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure3.svg"></img> |
| :---: |
| *Figure 3h. Unsorted plot of Vacc12 data* |


| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure4.svg"></img> |
| :---: |
| *Figure 4h. Sorted plot of Vacc12 data* |

| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure5.svg"></img> |
| :---: |
| *Figure 5h. Sorted plot of Testing Rate data* |


| <img width="640px"  src="https://raw.githubusercontent.com/Benitoite/covid19race/hisp/Resources/figure6.svg"></img> |
| :---: |
| *Figure 6h. Sorted plot of Testing Rate data* |


<hr>

### Background
The County of Santa Clara is well known for its diverse population. Statistical data regarding certain Covid-19 health markers are made available by the County for analysis through a system of application programming interfaces, or APIs, among other access methods like web apps, comma-separated values, and more. Some data made available by the County are recorded per Census Tract. The information currently available for the County by tract are test rate, positivity rate, case rate, and vacc12 rate (over age 12 vaccinations per population).

### Analysis
Covid-19 Positivity and Case Rate is seen to be inversely correlated to the curve of population who indicated White Alone as their racial identity.  There appears strong corellation between positivity and case rate with the percent who indicated Hispanic origin. There is a spike in cases in some tracts approaching and exceeding 70% White Alone, against the inverse correllation. Vacc12 and testing rates are seen to be definitely not correllated to the race-origin categorizations.

### Results
These data show us that the County Health educational campaigns for Covid-19 testing and vaccinations most likely did achieve equity. Where the County may not have fully met Health equity standards vital for moving forward with general economic recovery in terms of test positivity and case rate per populated tract. (ref. https://covid19.ca.gov/equity/)  It is important to identify the factors which cause racial inequities seen graphically in the analysis, and adopt practices moving forward with the goal of saving lives by health equity.
