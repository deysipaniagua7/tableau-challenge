# **Tableau Challenge**

This is the repository that holds my Module 18 tableau-challenge.

## **Module Overview**
Citi Bike is the largest bike-sharing program in the United States. While monthly data is collected, organized, and made publicly available on the program’s webpage, no dashboard or advanced reporting system exists.  

Our objective was to develop a Tableau report that provides key program insights for city officials.

## **Data Retrieval and Cleaning**
The data for this report was obtained from the Citi Bike’s Data webpage.  
Four datasets were downloaded, cleaned, and merged using Python:  
- July 2023
- December 2023
- July 2024
- December 2024

The final merged dataset was then used to generate visualizations in Tableau.

## **Tableau Visualizations**
- **Note:** Ride IDs corresponding to June and November data were excluded from the analysis to ensure a consistent comparison between summer (July) and winter (December). The final report is based on 331,276 Ride IDs. Dashboards contain a Year filter, allowing for customizable visualizations.

## **Public Tableau Workbook**
🔗 **[Citi Bike Tableau Story](https://public.tableau.com/app/profile/deysi.paniagua/viz/tableau-challenge_17426222424350/CitiBikeStory?publish=yes)**  
The link above contains my public Tableau Workbook, which includes:
- Several sheets
- Multiple dashboards
- A story for City Officials

## **Repository Structure**
### **Main "tableau-challenge" Repo Contains:**
1. **`citi_transform.ipynb`** – Used to clean and merge the four datasets.  
2. **`merged_data.csv`** – The final cleaned and merged dataset.  
3. **`tableau-challenge.twb`** – Tableau workbook containing sheets, dashboards, and story.

### **"Resources" Subfolder Contains:**
1. **2 PNG files** – Used to enhance Tableau story visuals.  
2. **`Tableau Analysis Text File`** – Explains the Tableau story.  
3. **Four datasets:**
   - `JC-202307-citibike-tripdata.csv`
   - `JC-202312-citibike-tripdata.csv`
   - `JC-202407-citibike-tripdata.csv`
   - `JC-202412-citibike-tripdata.csv`

## **References**
I used in-class activities/notes and the following resource to complete my assignment:  
🔗 *[Tableau Community - Total Distance Traveled](https://community.tableau.com/s/question/0D54T00000C6goRSAR/total-distance-traveled)*
