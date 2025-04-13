# 👟 Adidas Sales Data - Exploratory Data Analysis (EDA)

Welcome to the **Adidas Sales EDA** project repository. This project focuses on performing comprehensive exploratory data analysis on Adidas product sales data, uncovering patterns and insights to support strategic decision-making.

---

## 📝 Project Overview

Adidas, being one of the world's top sportswear brands, constantly needs to assess product performance, market trends, and consumer behavior. This project uses sales data to:

- Analyze pricing structures, availability, and product ratings
- Detect outliers and patterns through statistical and visual methods
- Generate strategic recommendations for marketing, inventory, and product planning

---

## 📁 Repository Structure

| File Name             | Description                                                |
|----------------------|------------------------------------------------------------|
| `EDA_review.ipynb`   | Primary notebook containing full analysis and visualizations |
| `Eda review 2.ipynb` | Supplementary notebook with alternate views and approaches |
| `adidas.csv`         | Cleaned Adidas product sales dataset                       |

---

## 📊 Dataset Details


- **Product Metadata**: `url`, `name`, `sku`, `description`, `brand`
- **Pricing Info**: `selling_price`, `original_price`, `currency`
- **Sales & Ratings**: `availability`, `average_rating`, `reviews_count`
- **Categorical Features**: `color`, `category`, `breadcrumbs`
- **Platform Details**: `source`, `source_website`, `country`, `language`
- **Time Context**: `crawled_at`

---

## 📌 Key Insights & Visualizations

✔️ **Descriptive Analysis** of price, rating, and product availability  
✔️ **Distribution Plots** showing skewness in pricing and ratings  
✔️ **Top Products Analysis** via bar and pie charts  
✔️ **Outlier Detection** using Isolation Forest algorithm  
✔️ **Missing Values Analysis** with appropriate handling  
✔️ **Dimensionality Reduction** through Feature Selection & PCA  


---

## 🛠 Tools & Libraries Used

- `Pandas` & `NumPy` – Data manipulation
- `Matplotlib` & `Seaborn` – Static visualizations
- `Scikit-learn` – Outlier detection, PCA
- `Jupyter Notebook` – Interactive workflow
- `Plotly` *(optional)* – Interactive visuals

---

## 📈 Summary Statistics

- **Selling Price**: Mean = 52.91 | Min = 9 | Max = 240  
- **Average Rating**: Mean = 4.61 | Min = 4.5 | Max = 5.0  
- **Missing Values**: < 1% of the dataset (handled via deletion)

---

## 🔎 Key Findings

- Majority of products priced between **$10 to $70**
- Most ratings are **above 4.5**, indicating strong customer satisfaction
- **Color-based segmentation** reveals skewed distribution (e.g., Black dominates)
- **Outliers detected and visualized** with red dots via Isolation Forest
- Effective use of **feature reduction and selection** to enhance analysis clarity

---

## 🧠 Recommendations

- Focus marketing efforts on **top-selling categories**
- Adjust **pricing strategies** based on discount-performance relationships
- Leverage **customer ratings** to prioritize high-rated products for promotions
- Optimize **inventory management** based on geographic trends

---

## 📌 Limitations

- Dataset scope limited to a specific crawl window
- Possible bias in review/rating representation
- Not all external market factors (like seasonality or regional festivals) included

---

## 🤝 Contributions & Feedback

Feel free to fork the repo, raise issues, or submit PRs.  
We're open to collaboration, feedback, and enhancement ideas!

