<H2>Maven Store data analyses / Tableau Dashboards</H2>

<H3> Brief </H3>

Maven Analytics educational company created a fictitious eCommerce retail store named
Maven Factory with a database storing 32k orders within 3 years of business data. I will
act as a data analyst to investigate their performance and offer
some recommendations based on my findings.


I will split up the analyses into two sections:

1)  First 18 months: '2012-04-01' to '2013-09-31'

2)  Full \~ 3 years : '2012-04-01' to '2014-12-31'


I have commented throughout my SQL scripts to show my analytical thought
process.

-   Most of the data outputs will be trending on a quarterly basis to
    maintain a reasonable frame size of data


**For the first 18 months of data (SEGMENT 1), I investigated exploratory
trends including:**

-   Trending website traffic, orders, and session-to-order conversion
    rates

-   Trending website traffic and sales broken out by advertising
    campaigns

-   Hour of day sales analysis

-   Website pages funnel analysis

-   Landing page click through rate analysis

-   Device type sales comparison


**For the full \~ 3 years of data (SEGMENT 2), I provided some
comprehensive analysis that the company owner might present to investors
to demonstrate long term growth. Analyses include:**

-   Trending website traffic, orders, conversion rates, revenue per
    order, and revenue per session

-   Trending organic search volume vs. paid search volume

-   Product cross sell analysis

-   Trending for repeat vs. first time website visitors on sessions,
    order conversion rate, and revenue per visit


<H3> Data Set </H3>

-   Created 6-table relational database with key mapping, EER diagram, constraints -- see project files

-   CSV zip file -- see project files


<H3> Tools </H3>

-   MySQL -- [view SQL
    scripts](https://github.com/nickrspence/eCommerce-company-performance-analysis/blob/main/FINAL_maven_sql_project.sql)

-   Tableau: ETL, key mapping, EER diagram, dynamic dashboard, KPIs, slicers


<H3> Tableau Visualizations </H3>


-   [Sales dashboard
    here](https://public.tableau.com/app/profile/nick.spence3425/viz/Maven_Sales_Dashboard/Dashboard1?publish=yes)
-    [Website Activity dashboard
    here](https://public.tableau.com/app/profile/nick.spence3425/viz/Maven_WebsiteActivity_Dashboard/Dashboard2?publish=yes)
