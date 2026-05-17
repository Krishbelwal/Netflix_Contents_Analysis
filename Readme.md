# Netflix Content & Genres Analysis

![Content Type Overview](Netfllix_Content_Type_overview.png)  
![Genres Overview](Netfllix_Geners_overview.png)  

## 1. Project Overview
This project analyzes Netflix content data to identify trends and user preferences in content type and genres based on release patterns. The goal is to support strategic content planning and decision-making.  

## 2. Key Metrics 
- Total shows per content type  
- Content vs release year trend (last 10 years)  
- Content vs average duration  
- Content vs rating  
- Top producing countries vs content  
- Year-over-Year (YoY) growth trend (last 10 years)  
- Total shows per genre  
- Top producing countries vs genres  
- Trend of top 5 genres (last 5 years)  
- Genre distribution  
- Rating vs genres  
- Content vs duration
- Yoy Trend for Genres (last 5 years)

## 3. Dataset
- **Source:** Kaggle  
- **Total Records:** 24,000  
- **Columns:** 12  

## 4. Tools & Technologies
- **Excel:** Data cleaning & analysis  
- **Power BI:** Dashboard development & visualization  

## 5. Data Cleaning Steps
- Convert the names of column in capatilize columns to improve the readability.  
- Handled missing values in `Director`, `Cast`, and `Country` columns using the "Go - Special" method.  
- Split multiple values in `Genres` and `Country` columns using **Split Column by Delimiter** in Power Query.  
- Applied the **Unpivot Columns** feature in Power Query for row format.   

## 6. Dataset Links
- **Original Dataset:** [Download CSV](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Original_dataset.csv)  
- **Cleaned Dataset:** [Download Excel](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Cleaned_dataset.xlsx)  

## 7. Dashboard Previews
- **Content Type Overview:** [View Dashboard](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Netfllix%20Content%20Type%20overview.png)  
- **Genres Overview:** [View Dashboard](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Netfllix%20Geners%20overview.png)  

## 8. Project Workflow
1. **Data Import:** Imported Excel dataset from Kaggle.  
2. **Understand Business Problem** Analysed strategic content planning needs.  
3. **Define Key Metrics & KPIs:** Total shows, movies vs TV shows, top genres, top countries, YoY trends, and more.  
4. **Data Cleaning & Transformation:** Cleaned data in Excel and Power Query.  
5. **Data Analysis:** Used pivot tables and charts in Excel to identify patterns and trends.  
6. **Power BI Import:** Imported cleaned data for visualisation.  
7. **DAX Measures:** Created measures like Total Shows, Total Movies, Total TV Shows, YoY Growth, and Top Countries.  
8. **Dashboard Development:** Built interactive dashboards with charts, tables, slicers, and KPIs.  
9. **Insights & Recommendations:** Derived actionable insights to support business decisions.  

## 9. Key Insights & Business Recommendations

**1. Popular Content**  
- Netflix has a total of **24,000 shows**, with **Movies making up 71% and TV Shows 29%**.  
- This shows that movies dominate, so Netflix could **focus more on TV shows to increase long-term user engagement**.  

**2. Popular Genres**  
- The most popular genres are **International Movies and Dramas**, This indicates internatinal with story-driven contents.  
- The platform should continue to invest in high quality internatinal drama series.

**2. Top Producing Countries**  
- The **USA leads with ~6,700 shows** around 42%. This indicates strong production in the usa.
-  Netflix can **invest more in India and the UK to attract more users subscribers**.  

**3. Content Trends**  
- Both Movie and Tv show shows an increasing Trend up to 2018 and 2018 is peak year for movie and 202o is peak year for TV show,s after i steady deacresed may be due to changing user prefence and content saturation.
- Netflix should understand the user viewing prefernce.

**4. Ratings Distribution**  
- Most content is targeted toward **(TV-MA, TV-14)** for both movie and tv show and internaltinal movie genre has been most popular among viewwrs.which indicates global   audenice are more intrested mature and internatinal relatble contents.
- Plartform shoud continue inversting in TV-MA, TV-14 contents with expanding intenatinal movie libary.

**4. YoY  Trends**  
- The year-over-year content growth has been **fluctuating**, with some years higher and others lower.  
- This suggests that Netflix should **plan content production more strategically** to maintain consistent growth.  
