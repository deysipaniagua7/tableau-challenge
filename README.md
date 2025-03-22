# tableau-challenge

This is the repository that holds my Module 18 tableau-challenge

Module Overview: Citi Bike is the largest bike-sharing program in the United States. While monthly data is collected, organized, and made publicly available on the program’s webpage, no dashboard or advanced reporting system exists. Our objective was to develop a Tableau report that provides key program insights for city officials.

Data Retrieval and Cleaning: The data for this report was obtained from the Citi Bike’s Data webpage. Four datasets (July 2023, December 2023, July 2024, and December 2024) were downloaded, cleaned, and merged using Python. The final merged dataset was then used to generate visualizations in Tableau.

Tableau Visualizations Note: Ride IDs corresponding to June and November data were excluded from the analysis to ensure a consistent comparison between summer (July) and winter (December). Thus, the final report is based on 331,276 Ride IDs. Dashboards contain a Year filter which allows for customizable visualizations.

Public Tableau Workbook: https://public.tableau.com/app/profile/deysi.paniagua/viz/tableau-challenge_17426222424350/CitiBikeStory?publish=yes
The link above contains my public Tableau Workbook. It contains several sheets, dashboards, and a story for City Officials.

The main “tableau-challenge” repo contains a 1) “citi_tranform .ipynb” file which was used to clean and merge the four datasets, 2) a “merged_data.csv” file, and 3) a “tableau-challege.twb” file which contains my Tableau sheets, dashboards, and story.

The “Resources” subfolder contains 1) 2 PNG files which were used to make the Tableau story more visually appealing, a 2) “Tableau Analysis Text File” which explains the story, and 3) the four datasets: “JC-202307-citibike-tripdata”, 2) “JC-202312-citibike-tripdata”, 3) “JC-202407-citibike-tripdata”, and “JC-202412-citibike-tripdata”. 

Please note, I used in-class activities/notes and the following resource to complete my assignment:

*https://community.tableau.com/s/question/0D54T00000C6goRSAR/total-distance-traveled
