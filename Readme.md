# Netflix Content & Genres Analysis

![Dashboard](Netflix Content Type overview.png)

![Dashboard](Netflix Gener overview.png)

## 1. Project Overview
This project analyzes Netflix content data to identify trends and user preferences in content type and genres based on release patterns. The goal is to support strategic content planning and decision-making.

## 2. Dataset
- **Source:** Kaggle  
- **Total Records:** 24,000  
- **Columns:** 12  

## 3. Tools & Technologies
- **Excel:** Data cleaning & analysis  
- **Power BI:** Dashboard development & visualization  

## 4. Data Cleaning Steps
- Standardized text by converting columns to capitalized format.  
- Handled missing values in `Director`, `Cast`, and `Country` columns using the "Go - Special" method.  
- Used **Split Column (by delimiter)** in Power Query to separate multiple values in `Genres` and `Country` columns.  
- Applied **Unpivot Columns** to transform the data into a normalized row format for better analysis.  
- Corrected date formats (dd-mm-yy → mm-dd-yy) for consistent visualization.  

## 5. Dataset Links
- **Original Dataset:** [Download CSV](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Original_dataset.csv)  
- **Cleaned Dataset:** [Download Excel](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Cleaned_dataset.xlsx)  

## 6. Dashboard Previews
- **Content Type Overview:** [View Dashboard](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Netfllix%20Content%20Type%20overview.png)  
- **Genres Overview:** [View Dashboard](https://github.com/Krishbelwal/Netflix_Content_Analysis/blob/main/Netfllix%20Geners%20overview.png)  

## 7. Project Workflow
1. **Data Import:** Imported Excel dataset from Kaggle.  
2. **Understanding Business Problem:** Analyzed the need for strategic content planning.  
3. **Define Key Metrics & KPIs:** Total shows, movies vs. TV shows, top genres, top countries, and YoY trends.  
4. **Data Cleaning & Transformation:** Cleaned data in Excel and Power Query.  
5. **Data Analysis:** Used pivot tables and charts in Excel to identify patterns and trends.  
6. **Power BI Import:** Imported cleaned data into Power BI for visualization.  
7. **DAX Measures:** Created key measures such as Total Shows, Total Movies, Total TV Shows, YoY growth, and Top Countries.  
8. **Dashboard Development:** Built interactive dashboards with charts, tables, slicers, and KPIs.  
9. **Insights & Recommendations:** Derived actionable insights to support business decisions.  

## 8. Key Insights

**1. Content Volume**  
- Netflix has 24,000 total shows: 17,000 Movies (71%) and 7,000 TV Shows (29%).  
- Movies dominate content production, indicating a focus on one-time viewing content.

**2. Top Producing Countries**  
- The United States leads with ~6,700 shows, followed by India, the UK, and France.  
- Indicates opportunity for growth in emerging markets like India.

**3. Popular Genres**  
- Top genres: International Movies, Dramas, Comedies, Action & Adventure.  
- International Movies and Dramas have the highest number of shows and average duration.

**4. Content Trends**  
- YoY growth in total shows peaked around 2017–2018 but declined by -45% in 2021.  
- Suggests market saturation and need for diversified or high-demand content.

**5. Average Duration**  
- Movies average ~103 minutes, higher than TV Shows.  
- Longer movies encourage binge-watching; TV shows are suited for episodic engagement.

**6. Ratings Distribution**  
- Most content is targeted toward general and teen audiences (TV-MA, TV-14).  
- Focuses on broad appeal while maintaining family and teen-friendly content.

## 9. Business Recommendations

**1. Increase Localized Content**  
- Invest in producing content for high-growth markets like India and the UK to attract new subscribers.  

**2. Focus on High-Demand Genres**  
- Expand production in Dramas and International Movies due to consistent popularity trends.  

**3. Diversify Content**  
- Introduce new genres such as Documentaries or short-form series to address declining YoY growth.  

**4. Leverage Duration Insights**  
- Promote longer movies for binge-watching while optimizing TV shows for episodic engagement.  

**5. Target Family-Friendly Audience**  
- Continue prioritizing general and teen-rated content while selectively exploring niche mature content for specific segments.
