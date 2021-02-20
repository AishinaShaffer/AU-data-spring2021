[Crime incidents in DC in 2021](https://github.com/AishinaShaffer/AU-data-spring2021/blob/main/Crime_Incidents_in_2021-EDITED.csv)

1. What is the most prevalent crime in DC?
   - Theft of items other than automobiles is the most prevalent crime in DC, with most offenses occuring in Wards 2 and 5
     - Ward 5 beats 2 by exactly one offense at 220
   - But neighborhood cluster 2 in Ward 1, which covers Columbia Heights, Mt Pleasant, Pleasant Plains and Park View, has the most reported cases of theft at 97
1. Which wards see the most violent crime?
   - Unsurprisingly, Wards 7 and 8 see the most violent crimes
   - However this count does not include burglary, as it isn't always a violent crime, so there may be variation in the actual number
1. Which neighborhood has the most violent crime in DC?
   - Neighborhood cluster 39, which is in Ward 8 and includes Congress Heights, Bellevue and Washington Highlands with 43 offenses
   - Cluster 2 in Ward 1, which covers Columbia Heights, Mt. Pleasant, Pleasant Plains and Park View, comes in second with 38 reported offenses

Cleaning data:
1. Resized column width
2. Split Column D in two, separating the date and time
3. Named new Column E REPORT_TIME
4. Split Column W in two, separating date and time
5. Named new Column X START_TIME
6. Split Column Y in two, separating date and time
7. Named new Column Z END_TIME
9. Used regex in Sublime to fix blank values in Column V to read N/A
