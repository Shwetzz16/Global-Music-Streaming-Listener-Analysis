# Global-Music-Streaming-Listener-Analysis
Global Music Streaming Listener Preferences – Analysis
📄 Project Overview:
This project analyzes the Global Music Streaming Listener Preferences dataset from Kaggle to uncover patterns in user demographics, platform usage, genre preferences, subscription types, and listening behaviors.
Through exploratory data analysis (EDA), visualizations, and statistical investigation, the study provides insights that can help music streaming businesses better understand their global audience and optimize engagement strategies.

📂 Files in this Repository
Global_Music_Streaming_Listener_Preferences.csv – The dataset used for the analysis (5,000 entries, 12 columns).
Music_Streaming_Analysis.ipynb – The Jupyter Notebook containing data loading, cleaning, exploration, visualization, and findings.
Music_Streaming_Analysis.html – The exported HTML version of the Jupyter Notebook for quick viewing without running code.

🧠 Summary of Analysis & Findings
Key Information About the Data
Size: 5,000 entries, 12 columns
Data Types:
Integers: Age, Minutes Streamed Per Day
Floats: Discover Weekly Engagement, Repeat Song Rate
Objects: Country, Streaming Platform, Subscription Type, Genres, etc.
Data Quality: Clean dataset – no missing or inconsistent values detected.

Summary statistics show:
Average user age: 36.66 years
Average listening time: 309.24 minutes/day
Average songs liked: 253.52 songs
Discover Weekly Engagement: 50.30%
Repeat Song Rate: 42.39%

Statistically Significant Results
Correlation analysis between numerical fields (e.g., age vs. minutes streamed, songs liked vs. discover weekly engagement) revealed no strong linear relationships.
Example: Age vs. daily streaming time correlation = 0.004 → negligible relationship.
No outliers or invalid values found in numerical data.
Categorical fields (e.g., country, streaming platform) are consistent and well-structured.

Key Insights from Visualizations
Age Distribution: Normal distribution, most users between 25–49 years, mean ~36.7 years.
Streaming Platform Popularity:
Amazon Music – most popular
Tidal and Deezer – moderate audience
Apple Music – smallest user base
Top Genres: Reggae, Jazz, EDM dominate; Pop is least preferred.
Subscription Types: Premium (50.52%) vs Free (49.48%) – nearly even split.

Listening Time Preferences:
Night: 34.9%
Afternoon: 32.68%
Morning: 32.42%

🎯 Conclusion

This study identified three main music streaming patterns:
1.Demographics: Average listener age ~36.7 years.
2.Platform Preferences: Amazon Music leads, followed by Tidal and Deezer.
3.Genre Trends: Reggae and Jazz preferred globally, while Pop ranks lowest.

Additionally:
No significant correlation between age and streaming behavior.
Nearly 50/50 premium vs free split offers marketing opportunities.
Peak usage at night can inform promotional timing and platform engagement strategies.

🚀 How to Use This Project
1.Open the Jupyter Notebook (.ipynb) in Jupyter Lab, Jupyter Notebook, or VS Code to run the analysis interactively.
2.Alternatively, open the HTML file to view the analysis without execution.
3.Dataset is provided for reproducibility and further exploration.

🛠️ Technologies Used
Python
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Visualizations
Jupyter Notebook – Analysis environment
