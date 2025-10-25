# Internship-project
Google Play Store Analytics Dashboard

Google Play Store Analytics Dashboard
 Project Overview



This project analyzes the Google Play Store dataset to uncover insights about app performance, installs, user ratings, and revenue trends.
Interactive visualizations are built to highlight patterns and KPIs across different app categories.




The dashboard includes:

Dynamic filters for category, rating, and time.
Intelligent visibility rules (e.g., visuals shown only during specific IST hours).
Translated category names for better global understanding.




Key Attributes:

App, Category, Rating, Reviews, Size, Installs, Price, Type, Content Rating, Genres, Last Updated, Current Ver, Android Ver
🔧 Data Processing & Transformations

Data Cleaning
Removed duplicates, nulls, and invalid entries.
Handled inconsistent formats (e.g., size in MB, installs with commas).

Filtering
Included apps meeting quality and performance thresholds:
Ratings ≥ 4.0
Installs ≥ 10,000
Size ≥ 15 MB
Android Version > 4.0
Reviews > 500

Enhancements
Added month-based growth metrics.
Translated category names:
Beauty → सौंदर्य (Hindi)
Business → வணிகம் (Tamil)
Dating → Dating (German: Verabredung)
Travel & Local → Voyage et local (French)
Productivity → Productividad (Spanish)
Photography → 写真撮影 (Japanese)

Integration
Joined with user reviews dataset to compute average sentiment and subjectivity.
📈 Key Performance Indicators (KPIs)
Total Installs & Revenue by Category
Month-over-Month Growth (%)
Average User Rating by Type (Free vs Paid)
Sentiment Analysis (Polarity & Subjectivity)
Category-wise Market Share

🎨 Visualizations & Dashboards
Visualization Type	Description	Visibility Time Window (IST)
Grouped Bar Chart	Compare Avg Rating vs Total Reviews (Top 10 Categories)	3 PM – 5 PM
Choropleth Map	Global Installs by Category (Top 5, Highlight >1M)	6 PM – 8 PM
Dual-Axis Chart	Avg Installs vs Revenue (Free vs Paid)	1 PM – 2 PM
Time Series Line Chart	Growth Trend of Installs by Category	6 PM – 9 PM
Bubble Chart	Size vs Rating vs Installs	5 PM – 7 PM
Stacked Area Chart	Cumulative Installs over Time	4 PM – 6 PM



Each visualization includes hover tooltips, legends, category translations, and highlighting for significant trends.

💻 Tools & Technologies Used
Python: Pandas, Plotly, Dash, NumPy
Visualization: Plotly Express, Dash Core Components
Data Source: Kaggle, CSV Files
Version Control: GitHub
Environment: Jupyter Notebook 

🚀 How to Run the Project
Clone the repository:
git clone https://github.com/yourusername/google-play-store-analytics.git
cd google-play-store-analytics

Install dependencies:
pip install -r requirements.txt

Launch the notebook or dashboard:
jupyter notebook analysis.ipynb



 Live Dashboard / Repo Link
GitHub Repository: 🔗 Click Here

🧾 Insights Summary
Free apps dominate installs, but paid apps yield higher average revenue per user.
“Beauty” and “Entertainment” categories show strong seasonal growth.
Sentiment analysis reveals that user satisfaction strongly correlates with app updates frequency.

👤 Author
Name: Aniket Chopade
Role: Data Analytics Intern
Institution: IICT, MGM University
Contact: LinkedIn • GitHub
