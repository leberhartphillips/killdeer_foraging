# Overview
## Dancing in the moonlight: evidence that Killdeer foraging behavior varies with lunar cycle
#### Luke J. Eberhart-Phillips
##### *Journal of Ornithology* (2017) 158:253-262.

In this repository you can find all the necessary files needed to reproduce the analyses presented in my paper (Read it [here](http://link.springer.com/article/10.1007/s10336-016-1389-4))

* **Rcode_Killdeer_foraging.pdf** contains the documented code for all analyses, which can be implemented after downloading the datasets provided in the **`Data_files`** folder.
* **`Data_files`**
    + **behavior_data_raw.csv** contains the raw behavioral data collected from the field. Each row is a single observation of the behavior (i.e. foraging, roosting, alert, or preening) of an individual on a given date, time, and scan. Within each observation, a "1" signifies the behavior the individual was engaged in, whereas a "0" signifies the behavior the individual was not engaged in.
    + **climate_data_raw.csv** contains the raw meterological data collected between February and March, 2010, from the National Weather Service station located at the Samoa Coast Guard Station in Humboldt County, California, and operated by the National Oceanic and Atmospheric Administration.  Data describes the maximum precipitation (mm) and minimum temperature (°C) recorded during the preceding 12 hours of each survey session specified in each row.
    + **lunar_data_raw.csv** contains the raw lunar data collected from the U.S. Naval Observatory.  Data describes the proportion of the moon's disk that was illuminated the preceding night of the date specified in each row.
