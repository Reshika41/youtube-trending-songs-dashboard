🎵 YouTube Trending Songs Analytics Dashboard – Global Music Insights 2025

This project analyzes YouTube’s Top Trending Songs in 2025 using Power BI to uncover what drives music popularity, which artists dominate, and how duration, category, and engagement metrics influence trends.

🚀 This dashboard is designed for music analysts, content creators, marketers, and data professionals who want to understand YouTube music performance trends
📊 Dashboard Preview
<img width="1002" height="495" alt="Screenshot 2025-10-22 152103" src="https://github.com/user-attachments/assets/c259cf78-bdf4-4ab6-98d0-50ea124ba575" />

✅ Business Objectives
The goal of this dashboard is to:
✔ Identify top-performing songs and channels
✔ Analyze viewership patterns
✔ Explore song duration vs popularity
✔ Categorize music trends by genre
✔ Discover hidden viral content
✔ Provide insight-driven story for music strategy

🔢 Key Metrics (KPIs)
Metric	Description
🎧 Total Songs	Total number of unique trending songs
👥 Total Channels	Number of unique music creators
🔥 Total Views	Total YouTube views
⭐ Average Views per Song	Viewership performance
⏱ Average Song Duration	Trend by length
🏆 Top Channel	Highest total views

🛠 Tools & Technologies
Power BI – Dashboard & Visualization
DAX – Metrics & Analytical Measures
Python / Pandas (Optional) – Data Cleaning
Excel – Preprocessing
GitHub – Portfolio Hosting

🧮 DAX Measures Used
Total Songs = DISTINCTCOUNT('YouTube Songs Clean'[title])
Total Channels = DISTINCTCOUNT('YouTube Songs Clean'[channel])
Total Views = SUM('YouTube Songs Clean'[view_count])
Average Views per Song = AVERAGE('YouTube Songs Clean'[view_count])
Average Duration (min) = AVERAGE('YouTube Songs Clean'[duration_min])

🚀 How to Use
Download/Clone this repo
Open dashboard.pbix in Power BI Desktop
Load dataset from /data/ folder if required
Interact with slicers (category, channel, duration)
Explore insights and trends

💡 Future Enhancements
✅ Add country-level analysis
✅ Include likes & comments engagement metrics
✅ YouTube API integration for live tracking
✅ Convert to Power BI Service report
✅ Deploy to web using Streamlit + Python

👩‍💻 Author

Reshika Miriyala
Aspiring Data Analyst | Power BI Developer | Data Storytelling
🔗 GitHub: https://github.com/Reshika41

⭐ Support My Work
If you like this project, please ⭐ star this repository and share it!
