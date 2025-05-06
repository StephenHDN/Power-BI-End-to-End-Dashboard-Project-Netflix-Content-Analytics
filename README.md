# 📊 Netflix Power BI Dashboard – End-to-End Business Intelligence Project

This project showcases a full-cycle Power BI dashboard built to analyze Netflix content using publicly available data from Kaggle. It walks through the entire BI workflow—from data ingestion and transformation to modeling, DAX calculations, visualization, and design. The goal is to provide actionable insights into viewer engagement, content performance by genre and country, and trends across media types (TV Shows vs. Movies).

---

## 🚀 Project Overview

- **Objective:** Analyze Netflix’s global content performance by rating, votes, genre, country, and content type.
- **Dataset:** [Kaggle - Netflix Titles and Ratings](https://www.kaggle.com/)
- **Tools Used:** Power BI Desktop, Power Query, DAX, Azure Maps, Coolors, GitHub
- **Deliverables:** Interactive dashboard with dynamic filters, maps, slicers, KPIs, and visuals aligned with Netflix branding.

---

## 📂 Folder Structure

---

## 🧠 Key Business Questions

- Which countries produce the highest-rated Netflix content?
- What genres have the best average ratings and engagement?
- How do TV shows compare to movies in popularity and rating?
- What is the vote distribution by content type and region?

---

## 🔁 End-to-End Workflow

### 1. Define Purpose & Audience
Designed for Netflix content strategy and analytics teams to uncover insights that guide localization, marketing, and acquisition decisions.

### 2. Data Collection
Sourced from Kaggle and imported into Power BI Desktop in `.csv` format. Includes 5,500+ titles with metadata: rating, genre, country, and votes.

### 3. Data Cleaning & Transformation
Used **Power Query** to:
- Remove nulls and duplicates
- Normalize genres and country names
- Create calculated columns like rating groups

### 4. Data Modeling
Built a **star schema** with:
- Fact table: content-level metadata
- Dimension tables: genre, country, media type
- Established one-to-many relationships for optimized filtering

### 5. DAX Measures
Created custom **DAX** calculations for:
- Average rating
- Total votes
- Votes per title
- % of total votes by category

### 6. Visualizations
Used Power BI Desktop to build:
- Stacked bar and column charts
- KPI cards (avg rating, votes, # of titles)
- Azure Maps for geolocation insights
- Tables with images and conditional formatting

### 7. UX & Branding
- Designed layout using **Netflix brand assets**
- Applied custom color palettes via **Coolors**
- Used dark theme for visual clarity and consistency

### 8. Interactivity
- Integrated slicers (genre, type, country)
- Enabled drill-through and tooltips
- All visuals are fully interactive and responsive

### 9. Testing & Validation
- Cross-checked DAX calculations
- Tested slicer functionality and logic flow
- Peer feedback for usability improvements

### 10. Sharing & Documentation
- Hosted `.pbix` on GitHub
- Exported summary as PDF
- Listed in LinkedIn Projects section
- Optional: Embedded in portfolio or Notion

---

## 🖼️ Sample Visuals

![Dashboard Overview](./images/dashboard-overview.png)
![Map Visualization](./images/azure-map.png)

---

## 📥 How to Use

1. Download the `.pbix` file from this repo.
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Interact with filters, slicers, and visuals.
4. Modify or expand using your own data sources.

---

## 📌 Key Skills Demonstrated

- Business intelligence design
- Data modeling and DAX
- Power Query transformation
- Interactive data storytelling
- Dashboard UX/UI design
- Version control using GitHub

---

## 🔗 Useful Links

- [Power BI Download](https://powerbi.microsoft.com/desktop/)
- [Kaggle Dataset](https://www.kaggle.com/)
- [Coolors Gradient Tool](https://coolors.co/)
- [Netflix Brand Assets](https://brand.netflix.com/)

---

## 📧 Contact

Built by Stephen
Connect on [LinkedIn](https://www.linkedin.com/in/stephenhdn/) | [Portfolio](https://github.com/StephenHDN)

---


