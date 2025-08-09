# zomato_EDA_analysis


# 🧾 Zomato Performance Analysis 

_Analyzing zomato cusines trends and ratings to support strategic purchasing and inventory decisions using Python._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project performs an Exploratory Data Analysis (EDA) on a dataset of Indian restaurants listed on Zomato. The dataset contains detailed information such as restaurant names, locations, cuisines, ratings, price ranges, and more. The main objective is to uncover patterns, trends, and relationships within the data that can provide actionable insights for restaurant businesses, food enthusiasts, and data-driven decision-making in the F&B industry.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

The restaurant industry is highly competitive, and businesses need to understand customer preferences, pricing strategies, and quality benchmarks to stay ahead. By analyzing Zomato’s restaurant data, we aim to:

- Identify key factors influencing restaurant ratings.
- Highlight popular cuisines and their performance.
- Understand the pricing structure and its impact on customer satisfaction.
- Recognize cities with the highest market presence and competition.
These insights can help restaurant owners optimize offerings, improve customer experience, and make data-backed strategic decisions.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Multiple CSV files located in `/data/` folder (cusines,rating,cities)
- Summary table created from ingested data and used for analysis

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Excel (Exploration and understanding the dataset)
- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Canva
- GitHub

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

Steps performed to prepare the data for analysis:

-Removed duplicates – 151,527 duplicate rows were identified and dropped.
- Handled missing values –
- Dropped columns with >75% null values (zipcode) and less relevant columns (address).
- Filled missing cuisines with the mode value.
- Filled missing opentable_support with default value 1.
- Data type checks – Ensured columns had correct data types (int, float, object).
- Feature engineering – Extracted primary cuisine from multi-cuisine entries and calculated cuisine count for correlation studies.

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

The analysis focused on the following aspects:

Overall Ratings:
- Mean restaurant rating: 3.82 (excluding unrated restaurants).
- Distribution showed most ratings between 3.5–4.5.

City Insights:
- Chennai had the highest number of listed restaurants.
- Bangalore recorded the highest average ratings among the top cities.

Popular Cuisines:
- North Indian, Fast Food, and Cafe are the most common cuisines.
- Vietnamese and African cuisines scored high on ratings.

Price & Rating Relationship:
- Weak positive correlation (0.3) between price range and rating.
- Higher price ranges generally had better ratings and a higher average cost for two.

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

What is the average rating of restaurants?
- 3.82 average (excluding unrated restaurants).
- Most restaurants fall in the 3.5–4.5 range.

Which city has the highest concentration of restaurants?
- Chennai tops with over 11,000 listings.

Which cuisines are most popular?
- Top 3: North Indian, Fast Food, Cafe.

Is there a link between the variety of cuisines and ratings?
- Minimal correlation; offering more cuisines doesn’t guarantee higher ratings.

How does price range relate to ratings?
- Price range 4 (premium) restaurants have the highest average ratings and costs.

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Focus on quality and service in all price ranges; premium restaurants generally earn higher ratings.
- Prioritize popular cuisines (North Indian, Fast Food, Cafe) while using niche high-rated cuisines for uniqueness.
- Apply city-specific strategies: compete strongly in dense markets like Chennai and Bangalore; expand into smaller cities with growth potential.
- Limit menu variety to a few well-executed cuisines.
- Use customer feedback to improve and market high-rated dishes effectively.

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Ayushi Mishra**  
Data Analyst  
📧 Email: rohan112.ravi@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rohnravii/)  
