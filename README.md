# kovai_task2

# Video Game Sales Analysis 🎮

![Video Game Controller](add_image_url_here)

Welcome to the exploration of video game sales data from around the world. This dataset offers insights into the gaming industry, covering various aspects such as platforms, genres, publishers, and regional sales. Dive into our analysis to uncover what makes a game successful and discover other valuable information hidden within this dataset.

## Setup Requirements

1. Load the dataset using Python and Pandas.
   
   ```python
   import pandas as pd
   data = pd.read_csv("Video Games Sales.csv")
   ```
2.Check for missing values in the dataset.

```python
  Copy code
  missing_values = data.isnull().sum()
```

3.Remove duplicate entries to ensure data integrity. 

```python
Copy code
data.drop_duplicates(inplace=True)
```

4.Standardize data types as needed. For example, convert the 'Year' column to datetime.
```python
Copy code
data['Year'] = pd.to_datetime(data['Year'], errors='coerce')
```

# Use Matplotlib and Seaborn to create visualizations and explore the data.  
 
Visualize the distribution of global sales.  
Explore the distribution of sales by genre.  
Analyze the distribution of sales by platform.  
Investigate the distribution of sales by region (e.g., North America, Europe, Japan, Rest of World).    
# Key Insights  
🌐 Insight 1: The average global sales of games is approximately 2.49 million, with a standard deviation of 3.56 million.

📈 Insight 2: The highest global sales for a game is approximately 81.12 million.

🎮 Insight 3: The most common genre among games in the dataset is 'Sports' with 308 games.

🎯 Insight 4: The most common gaming platform in the dataset is 'PS2' with 372 games.

🔥 Insight 5: Games that fall within the top 10% of global sales are considered successful.

🕰️ Insight 6: Games' global sales have seen significant variations over the years, reflecting evolving trends in the gaming industry.

📊 Insight 7: There is a correlation of approximately 0.18 between game review scores and global sales.

🌍 Insight 8: Different regions have distinct preferences in game genres. For example, in North America, 'Action' games are highly popular.

🏢 Insight 9: The most prolific publisher in the dataset is 'Electronic Arts' with 341 games.

# Top 10 Games of All Time
Explore the top 10 games of all time by global sales.

# Attributes of Successful Games
Analyze the attributes of successful games, including genres, platforms, and publishers.

# Get Started
Clone this repository.
Load the dataset using the provided code.
Start exploring and analyzing the video game sales data.
Discover more insights and trends in the gaming industry.


