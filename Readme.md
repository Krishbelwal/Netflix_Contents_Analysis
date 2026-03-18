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
- Applied the **Unpivot Columns** feature in Power Query for row format.  .  

## 6. Dataset Links
- **Original Dataset:** [Download CSV](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Original_dataset.csv)  
- **Cleaned Dataset:** [Download Excel](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Cleaned_dataset.xlsx)  

## 7. Dashboard Previews
- **Content Type Overview:** [View Dashboard](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Netfllix%20Content%20Type%20overview.png)  
- **Genres Overview:** [View Dashboard](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Netfllix%20Geners%20overview.png)  

## 8. Project Workflow
1. **Data Import:** Imported Excel dataset from Kaggle.  
2. **Understand Business Problem & Keywords:** Analyzed strategic content planning needs.  
   - Keywords: Netflix content library, dominant genres, dominant content type, release year trends  
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

**2. Top Producing Countries**  
- The **USA leads with ~6,700 shows** around 42%.  
- This indicates strong production in the US, but Netflix can **invest more in India and the UK to attract more and user subscribers**.  

**3. Popular Genres**  
- The most popular genres are **International Movies and Dramas**, which have the highest number of shows.  
- Netflix could **also explore other genres** to diversify content and reach different audiences.  

**4. Content Trends**  
- The year-over-year content growth has been **fluctuating**, with some years higher and others lower.  
- This suggests that Netflix should **plan content production more strategically** to maintain consistent growth.  

**5. Ratings Distribution**  
- Most content is targeted toward **general and teen audiences (TV-MA, TV-14)**.  
- Since International Movies are most popular among these ratings, Netflix can **focus on producing content in this genre to attract and retain teen viewers**.  

**6. Average Duration**  
- Movies have an average duration of **~103 minutes**, longer than TV shows.  
- This allows for binge-watching, while TV shows suit episodic viewing. Netflix can **optimise content formats based on this trend**.     
