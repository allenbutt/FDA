# FDA
Project to gather reports out of publicly available adverse events data for medical devices.

open.fda.gov/data/downloads/

## Background
Medical Device reports are sent to the FDA from across the country. These reports are gathered and reviewed by experts in the FDA, and are also made available to the public. At the moment, there is only one easy way to retrieve MDRs from the FDA, which is to use the MAUDE database (https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfmaude/search.cfm). However, this database suffers from a poor interface, few search features, and a limitation of only 500 reports retrievable at a time. Therefore, the MAUDE database is only suitable for analyzing small numbers of reports, and a new way of extracting and using device report data is needed.

The FDA has a second repository of medical device reports, kept as raw data in JSON format on another site (https://open.fda.gov/data/downloads/). This site has the opposite problem from the first, in that the data is completely unstructured and extremely time-consuming to obtain.

## Goals
The goal of this project is three-fold:
1. Web Scraping to gather relevant data from the FDA website
2. Text analysis to determine key words from report descriptions
3. Visualizations to find interesting trends or areas needing further analysis

## Outcome
I will be posting a summary of the project and its outcomes as posts on my site: https://allenbutt.github.io/

## Contact
If you have any questions for me, please email me at: allenbutt1122@hotmail.com
