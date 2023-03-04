# Module 2: Data Three Ways

for COMP 590 - Data Visualization @ UNC-CH  
by Kevin Chen

A remix of this article from the Pew Research Center: https://www.pewresearch.org/social-trends/2023/03/01/the-enduring-grip-of-the-gender-pay-gap/

See online here! https://comp790-infovis.github.io/module-two-data-three-ways-kekevi/

## Data

According to the article, the data was obtained from "Pew Research Center analysis of the Current Population Survey outgoing rotation group files (IPUMS)", however, there is no link to the actual dataset they used with the variables they used. 

Instead, I went to ipums.org and used the 2021 ACS (1-year) survey, choosing the variables as listed in `data/usa_00002.xml`. I then processed (cleaning up and aggregating) the data using **R**, with the **tidyverse** library. The resulting datasets are also in the `data` folder. 

To use, please uncompress the `.dat.gz` file.

