Spotify Data Analysis – Project Report
📌 Objective
To analyze a Spotify dataset to uncover insights about song characteristics, artist popularity, trends across years, and audio features influencing track success. The goal was to create a dashboard that allows users to explore music data interactively and support data-driven decisions in the music industry.
🛠️ Tools & Technologies Used
- Power BI – for data modeling, transformation, and visualization
- Power Query Editor – for data cleaning and shaping
- DAX (Data Analysis Expressions) – for calculated columns and KPIs
- Data Source – CSV file (Spotify dataset with track-level audio features)
📂 Data Understanding
The dataset included:
- Track name, Artist name
- Year of release
- Popularity score
- Audio features: danceability, energy, acousticness, loudness, tempo, valence, speechiness, duration
🧹 Data Cleaning & Preparation (Power Query)
1. Column Renaming
   - Renamed columns to be more readable.
2. Data Type Conversion
   - Ensured correct data types.
3. Null Value Handling
   - Removed rows with missing or corrupted values.
4. Filtering
   - Removed tracks with popularity = 0.
📊 Data Modeling
1. Maintained flat table structure.
2. Created Calculated Columns / Measures using DAX:
   - Top Artists Count
   - Average Popularity
   - Track Duration in minutes
   - Custom Flags for High Energy, Danceable, etc.
📈 Dashboard Design & Visualizations
1. KPIs:
   - Total Tracks, Average Popularity, Top Artist, Year Range
2. Trend Analysis:
   - Line Chart for Popularity over Time, Bar Charts for Top Artists
3. Audio Feature Analysis:
   - Radar/Bar/Scatter plots of features vs popularity
4. Interactive Filters:
   - Year, Artist, Popularity Slicers
5. Heatmap (if present):
   - Showed correlation between features and popularity
📊 Key Insights Derived
- Identified most prolific artists
- Observed popularity trends over time
- High danceability and energy linked to popularity
- Duration not clearly linked to popularity
💡 Business Use Case
- Record Labels: Identify hit song features
- Music Apps: Enhance recommendation engines
- Artists: Understand what makes songs popular
📁 Project Challenges
- Handling missing or zero popularity values
- Defining feature thresholds (e.g., high energy)
- Balancing depth with dashboard clarity
✅ Outcome
Created an interactive dashboard providing actionable insights into track and artist trends. Demonstrated skills in Power BI, DAX, data cleaning, and storytelling for real-world analytics.
