# CC_Covid19_Graphs
(Italian version [here](README_IT.md))

To navigate through the plots, go to:

[EN]
https://crlclgrs.github.io/CC_Covid19_Graphs/

[IT]
https://crlclgrs.github.io/CC_Covid19_Graphs/it/index.html

If you have any question, feel free to ask on Twitter:
[@ClgClgrs](https://twitter.com/intent/tweet?screen_name=CrlClgrs&ref_src=twsrc%5Etfw)

## Updated to 18-Apr-2020

This is a simple project that takes data from
[Dati COVID-19 Italia](https://github.com/pcm-dpc/COVID-19).

The plots are made with great [plot.ly](https://plotly.com/) library.

You can find plots related to:
- NATION / ITALY
- GEO / NORTH-CENTER-SOUTH
- REGION / All Italian Regions


## Plots Explanation

### ABSOLUTE_STACKS
#### CASES
The total number of cases until now (positives + deceased + healed)
#### POSITIVES
The current number of positive people
#### HOSPITALIZED
The current number of people in hospital
#### HEALED
The number of people healed until now
#### DECEASED
The number of people deceased until now
#### INTENSIVE CARE
The current number of people in intensive care
#### CASES EST WITH [DAY DELTA(CASES)<GAUSS FIT>]
The today value of CASES is recalculated using the value of yesterday for CASES + the difference estimation found with DAY DELTA(CASES)<GAUSS FIT>
#### POSITIVES<GAUSS FIT>
A gaussian fitting of POSITIVES
#### HEALED EST WITH [DAY DELTA(HEALED)<GAUSS FIT>]
The today value of HEALED is recalculated using the value of yesterday for HEALED + the difference estimation found with DAY DELTA(HEALED)<GAUSS FIT>
#### DECEASED EST WITH [DAY DELTA(DECEASED)<GAUSS FIT>]
The today value of DECEASED is recalculated using the value of yesterday for DECEASED + the difference estimation found with DAY DELTA(DECEASED)<GAUSS FIT>
### RELATIVE_CHARTS_1
#### DECEASED / POSITIVES
Value of DECEASED / Value of POSITIVES --- both at the value of the current day
#### HEALED / POSITIVES
Value of HEALED / Value of POSITIVES --- both at the value of the current day
#### POSITIVES OF DAY / POSITIVES
Value of POSITIVES OF DAY / Value of POSITIVES --- both at the value of the current day
#### DAY DELTA(POSITIVES) / POSITIVES
Value of DAY DELTA(POSITIVES) / Value of POSITIVES --- both at the value of the current day
### RELATIVE_CHARTS_2
#### POSITIVES / TESTS
Value of POSITIVES / Value of TESTS --- both at the value of the current day
#### POSITIVES / TESTS<GAUSS FIT>
A gaussian fitting of POSITIVES / TESTS
#### POSITIVES OF DAY / DAY DELTA(TESTS)
Value of POSITIVES OF DAY / Value of DAY DELTA(TESTS) --- both at the value of the current day
#### DAY DELTA(POSITIVES) / DAY DELTA(TESTS)
Value of DAY DELTA(POSITIVES) / Value of DAY DELTA(TESTS) --- both at the value of the current day
### NEW_VALUES_IN_DAY
#### POSITIVES OF DAY
The number of people found positive in this day
#### DAY DELTA(HEALED)
Value of HEALED of today - Value of HEALED of yesterday
#### DAY DELTA(DECEASED)
Value of DECEASED of today - Value of DECEASED of yesterday
#### DAY DELTA(HOSPITALIZED)
Value of HOSPITALIZED of today - Value of HOSPITALIZED of yesterday
#### DAY DELTA(INTENSIVE CARE)
Value of INTENSIVE CARE of today - Value of INTENSIVE CARE of yesterday
#### DAY DELTA(HEALED)
Value of HEALED of today - Value of HEALED of yesterday
#### DAY DELTA(HEALED)<GAUSS FIT>
A gaussian fitting of DAY DELTA(HEALED)
#### DAY DELTA(DECEASED)
Value of DECEASED of today - Value of DECEASED of yesterday
#### DAY DELTA(DECEASED)<GAUSS FIT>
A gaussian fitting of DAY DELTA(DECEASED)
### NEW_VALUES_ON_TOT_POSITIVI
#### DAY DELTA(POSITIVES) / POSITIVES
Value of DAY DELTA(POSITIVES) / Value of POSITIVES --- both at the value of the current day
#### DAY DELTA(HOSPITALIZED) / POSITIVES
Value of DAY DELTA(HOSPITALIZED) / Value of POSITIVES --- both at the value of the current day
#### DAY DELTA(HEALED) / POSITIVES
Value of DAY DELTA(HEALED) / Value of POSITIVES --- both at the value of the current day
#### DAY DELTA(INTENSIVE CARE) / POSITIVES
Value of DAY DELTA(INTENSIVE CARE) / Value of POSITIVES --- both at the value of the current day
#### DAY DELTA(DECEASED) / POSITIVES
Value of DAY DELTA(DECEASED) / Value of POSITIVES --- both at the value of the current day
#### DAY DELTA(POSITIVES) / POSITIVES - POLY FIT ORD 3
A polynomial fitting of DAY DELTA(POSITIVES) / POSITIVES estimated with order 3
#### DAY DELTA(HOSPITALIZED) / POSITIVES - POLY FIT ORD 3
A polynomial fitting of DAY DELTA(HOSPITALIZED) / POSITIVES estimated with order 3
#### DAY DELTA(HEALED) / POSITIVES - POLY FIT ORD 3
A polynomial fitting of DAY DELTA(HEALED) / POSITIVES estimated with order 3
#### DAY DELTA(INTENSIVE CARE) / POSITIVES - POLY FIT ORD 3
A polynomial fitting of DAY DELTA(INTENSIVE CARE) / POSITIVES estimated with order 3
#### DAY DELTA(DECEASED) / POSITIVES - POLY FIT ORD 3
A polynomial fitting of DAY DELTA(DECEASED) / POSITIVES estimated with order 3
#### DAY DELTA(POSITIVES) / POSITIVES - POLY FIT ORD 2
A polynomial fitting of DAY DELTA(POSITIVES) / POSITIVES estimated with order 2
#### DAY DELTA(HOSPITALIZED) / POSITIVES - POLY FIT ORD 2
A polynomial fitting of DAY DELTA(HOSPITALIZED) / POSITIVES estimated with order 2
#### DAY DELTA(HEALED) / POSITIVES - POLY FIT ORD 2
A polynomial fitting of DAY DELTA(HEALED) / POSITIVES estimated with order 2
#### DAY DELTA(INTENSIVE CARE) / POSITIVES - POLY FIT ORD 2
A polynomial fitting of DAY DELTA(INTENSIVE CARE) / POSITIVES estimated with order 2
#### DAY DELTA(DECEASED) / POSITIVES - POLY FIT ORD 2
A polynomial fitting of DAY DELTA(DECEASED) / POSITIVES estimated with order 2
#### DAY DELTA(POSITIVES) / POSITIVES - POLY FIT ORD 1
A polynomial fitting of DAY DELTA(POSITIVES) / POSITIVES estimated with order 1
#### DAY DELTA(HOSPITALIZED) / POSITIVES - POLY FIT ORD 1
A polynomial fitting of DAY DELTA(HOSPITALIZED) / POSITIVES estimated with order 1
#### DAY DELTA(HEALED) / POSITIVES - POLY FIT ORD 1
A polynomial fitting of DAY DELTA(HEALED) / POSITIVES estimated with order 1
#### DAY DELTA(INTENSIVE CARE) / POSITIVES - POLY FIT ORD 1
A polynomial fitting of DAY DELTA(INTENSIVE CARE) / POSITIVES estimated with order 1
#### DAY DELTA(DECEASED) / POSITIVES - POLY FIT ORD 1
A polynomial fitting of DAY DELTA(DECEASED) / POSITIVES estimated with order 1
### NEW_VALUES_STACKS
#### DAY DELTA(POSITIVES)
Value of POSITIVES of today - Value of POSITIVES of yesterday
#### POSITIVES OF DAY
The number of people found positive in this day
#### -DAY DELTA(DECEASED)
Negation of DAY DELTA(DECEASED)
#### -DAY DELTA(HEALED)
Negation of DAY DELTA(HEALED)
### NEW_VALUES_DIFF_TO_YESTERDAY
#### DAY DELTA(DAY DELTA(POSITIVES))
Value of DAY DELTA(POSITIVES) of today - Value of DAY DELTA(POSITIVES) of yesterday
#### DAY DELTA(DAY DELTA(HEALED))
Value of DAY DELTA(HEALED) of today - Value of DAY DELTA(HEALED) of yesterday
#### DAY DELTA(DAY DELTA(DECEASED))
Value of DAY DELTA(DECEASED) of today - Value of DAY DELTA(DECEASED) of yesterday
#### DAY DELTA(DAY DELTA(INTENSIVE CARE))
Value of DAY DELTA(INTENSIVE CARE) of today - Value of DAY DELTA(INTENSIVE CARE) of yesterday
### FORECASTS_ON_SPEED
#### POSITIVES
The current number of positive people
#### POSITIVES EST WITH COEFF [DAY DELTA(POSITIVES) / POSITIVES - POLY FIT ORD 2]
The today value of POSITIVES is recalculated using the value of yesterday for POSITIVES * the factor estimated with DAY DELTA(POSITIVES) / POSITIVES - POLY FIT ORD 2
#### HOSPITALIZED
The current number of people in hospital
#### HOSPITALIZED EST WITH COEFF [DAY DELTA(HOSPITALIZED) / POSITIVES - POLY FIT ORD 2]
The today value of HOSPITALIZED is recalculated using the value of yesterday for HOSPITALIZED * the factor estimated with DAY DELTA(HOSPITALIZED) / POSITIVES - POLY FIT ORD 2
#### HEALED
The number of people healed until now
#### HEALED EST WITH COEFF [DAY DELTA(HEALED) / POSITIVES - POLY FIT ORD 3]
The today value of HEALED is recalculated using the value of yesterday for HEALED * the factor estimated with DAY DELTA(HEALED) / POSITIVES - POLY FIT ORD 3
#### DECEASED
The number of people deceased until now
#### DECEASED EST WITH COEFF [DAY DELTA(DECEASED) / POSITIVES - POLY FIT ORD 2]
The today value of DECEASED is recalculated using the value of yesterday for DECEASED * the factor estimated with DAY DELTA(DECEASED) / POSITIVES - POLY FIT ORD 2
#### INTENSIVE CARE
The current number of people in intensive care
#### INTENSIVE CARE EST WITH COEFF [DAY DELTA(INTENSIVE CARE) / POSITIVES - POLY FIT ORD 2]
The today value of INTENSIVE CARE is recalculated using the value of yesterday for INTENSIVE CARE * the factor estimated with DAY DELTA(INTENSIVE CARE) / POSITIVES - POLY FIT ORD 2
