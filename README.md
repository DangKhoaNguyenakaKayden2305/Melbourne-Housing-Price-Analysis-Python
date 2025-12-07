**Melbourne Housing Price Analysis (Python Project)
 Overview****

This project explores the key factors influencing Melbourne housing prices using Python-based data analytics. The analysis investigates how variables such as suburb, land size, number of rooms, car parks, and property type affect overall pricing patterns. It also studies long-term development trends across suburbs within and beyond 4 km of the CBD (1870–2020).
The goal is to uncover pricing insights, identify premium vs affordable suburbs, and provide data-driven observations for property buyers, sellers, and investors.

**Tools & Libraries Used**

Programming Language: Python

**Libraries:**

Pandas & NumPy: data cleaning and transformation

Matplotlib & Seaborn: charts and visual analysis

Statsmodels: regression analysis


**Key Findings
 Suburb Insights**

Kew and Albert Park show significantly higher median prices, driven by proximity to the CBD and premium amenities.

Melton and Reservoir remain affordable options, offering larger land sizes at lower price points.

**Car Parks & Price**

Houses with more than two car parks tend to fall in higher price brackets.

Across suburbs, properties with ≥2 parking spaces correlate positively with land size and overall value.

**Landsize & Price**

A strong positive relationship is observed between land size and price, especially in premium suburbs.

Larger suburban blocks often command a premium even when house type remains the same.

**Development Trends**

Construction activity within 4 km peaked earlier in the 20th century.

Post-1950, development beyond 4 km grew rapidly, reflecting suburban expansion.

**Analysis Sections**
**1. Price Distribution Across Suburbs**

Plots compare median and distribution of home prices across selected suburbs.
<img width="1136" height="627" alt="image" src="https://github.com/user-attachments/assets/8f80096f-66f9-47c2-9b29-89055588da8b" />

**Figure: Price Distribution Boxplot**

**2. Car Parks vs Price Brackets**

Bar charts explore how car-park capacity influences the price categories.
<img width="1129" height="640" alt="image" src="https://github.com/user-attachments/assets/7d4b06ec-0307-41fd-aa5e-3f83c60bbd98" />

**Figure: Price Brackets by Car-Park Count**

**3. Landsize vs Price Relationships**

Scatterplots with regression lines show how price scales with land size across suburbs.
<img width="788" height="422" alt="image" src="https://github.com/user-attachments/assets/a074ead6-114c-4d28-a2dc-5c0bdca195ff" />
<img width="778" height="438" alt="image" src="https://github.com/user-attachments/assets/3f72284e-8dbd-4a32-ad2c-10b891c856b6" />
<img width="839" height="425" alt="image" src="https://github.com/user-attachments/assets/a673c324-9d29-49e1-807f-2afa947a1c35" />
<img width="822" height="434" alt="image" src="https://github.com/user-attachments/assets/4c7abc6e-65c2-401d-9178-4e2df1bf7839" />
<img width="856" height="418" alt="image" src="https://github.com/user-attachments/assets/0a34734d-9f3c-4bfa-9e1a-87a1f39e68d7" />
<img width="834" height="426" alt="image" src="https://github.com/user-attachments/assets/3e6f9f6e-5766-43bd-9b47-dab4a419d00b" />
 Figure: Scatter + Trendline for Each Suburb

**4. Suburb-Level Average Price & Landsize**
Pivot tables and heatmaps visualise how property type (house / townhouse / unit) differs by suburb.
 <img width="1150" height="652" alt="image" src="https://github.com/user-attachments/assets/8ca85460-de53-4237-8021-44683bc75e3e" />

 Figure: Heatmap of Average Price by Property Type
 <img width="1096" height="646" alt="image" src="https://github.com/user-attachments/assets/e68a95ef-357f-48a6-ba5e-f8665f9014bc" />

** Figure: Bar Chart of Average Landsize**

**5. Development Growth Over Time (1870–2020)**

A historical timeline showing construction trends within vs beyond 4 km of Melbourne CBD.
** Figure: Development Trend Line Chart**

**Recommendations** 

Based on the analysis:

**For Buyers**

Consider Reservoir or Melton for affordability and larger land sizes.

Premium buyers should focus on Kew, Albert Park, Fitzroy, where price growth is historically strong.

**For Investors**

Suburbs beyond 4 km show consistent development growth, indicating future value uplift.

Properties with ≥2 car parks remain attractive in competitive markets.

**For Urban Planners**

Historical data suggests potential for renewed densification closer to the CBD.

Outer suburbs require infrastructure planning to support continued growth.
