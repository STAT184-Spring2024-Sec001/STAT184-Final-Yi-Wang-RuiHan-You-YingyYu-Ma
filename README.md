# Stat 184 - yi Wang, YingYu Ma, Ruihan You (Spring 2024) Final Project

This repo will serve as the template file for the course project. Further, this README file will contain the project specifications (details), checkpoints, and the list of learning outcomes being assessed. Be sure to read through all portions of the README carefully.

## 1. INTRODUCTION
The dataset presented here offers a comprehensive analysis of the theatrical market performance of movies released since 1995 within the North American movie region, encompassing the United States, Canada, Puerto Rico, and Guam. Compiled from The Numbers' unique categorization system, this dataset provides valuable insights into movie attributes crucial for market understanding.

1.1 Market Analysis Criteria
Movies in this dataset are categorized based on six key attributes: Creative type (including factual, contemporary fiction, fantasy, etc.), Source (such as book adaptations, original screenplays, etc.), Genre (spanning drama, horror, documentary, and more), MPAA rating, Production method (including live action, digital animation, etc.), and Distributor.

1.2 Fair Comparison of Movies
To ensure fairness in comparisons across different years, all rankings are rooted in ticket sales data, calculated using average ticket prices as reported annually by the MPAA in their state of the industry reports.

1.3 Dataset Contents
Contained within are multiple files revealing statistics such as annual ticket sales trends, the highest-grossing movies each year since 1995, top-performing creative types, distributors, genres, MPAA ratings, sources, production methods, and the number of wide releases each year by various distributors.

1.4 Data Source
This dataset is sourced from The Numbers website, focusing specifically on domestic theatrical market performance. The Numbers' theatrical market pages concentrate on the North American movie region, ensuring a detailed analysis of this specific market.
For further details and a deeper exploration of this dataset, please visit The Numbers Market Analysis.

## Question:
General questions:
What makes the movie earn more money? 
To be more specific:
What genres of movies are popular and earning more money?
Do more movie releases lead to a higher total gross? Of the “Big Six” movie studios, Walt Disney, Warner Bros., Paramount, 20th-century Fox, Universal, and Sony, which has a higher number of wide-release movies (when a film plays in most cinemas across a country at the same time)?
What movie production method is most profitable?

## EDA
<img width="561" alt="截屏2024-04-24 下午1 35 19" src="https://github.com/STAT184-Spring2024-Sec001/STAT184-Final-Yi-Wang-RuiHan-You-YingyYu-Ma/assets/119536824/7d472ec5-cb63-4af7-a616-58e3935fd730">
Graph1 : pie chart of genres of movie
To find out what kind of movie genres are more popular. I decided to first check the popularity share of different movie genres in the market. Therefore pie charts are a good choice for visualization. Pie charts show how different categories relate to each other as parts of a whole. Each slice of the pie represents a category, and Each slice of the pie represents a category, and its size shows the proportion or percentage of that category relative to the entire dataset. To have a more visual view of the market share of each movie genre I chose to use different colors to represent the different genres. Based on the pie chart, the genre of Adventure has the highest market popularity. However, genres of black comedy, documentary, and musical are the less popular.

<img width="864" alt="截屏2024-04-25 下午10 03 39" src="https://github.com/STAT184-Spring2024-Sec001/STAT184-Final-Yi-Wang-RuiHan-You-YingyYu-Ma/assets/119536824/ee8e4d53-b467-4ef7-a179-9093f6eb2756">
Graph2 : The total gross of movies in billion of dollars by genres of movie.
However, based on the pie chart could not generate further summary about the money making based on movie genres. Hence, I create a bar graph about the total gross price in billions of dollars of genres of movies. Bar graphs are a versatile and commonly used type of chart that helps to visually represent data. They can be very effective for displaying and comparing information across different categories. To more visually see the market share of movie genres, I've arranged the bar charts from largest to smallest and added black lines to better visualize specific box office amounts. For adventure genres, it has the highest gross at more than 6000 billion dollars. Second, is action, which has almost 5000 billion dollars. Thirdly is drama, which has about 3800 billion dollars as a total gross. 

## RESULTS
For question one, adventure movies are the most popular and earn the most money comparing other genres.
 


## CONCLUSION
Based on our exploratory data analysis (EDA), we tentatively hypothesized that live-action adventure films produced by Disney World are likely to be the most profitable. However, as diligent statisticians, we must acknowledge that relying solely on charts and graphs for making predictions is methodologically insufficient. For more precise forecasts, it is essential to develop specialized models that can determine which attributes significantly influence a movie's financial success. Unfortunately, our current analysis may be constrained by limited data and a lack of comprehensive knowledge in this area, which might restrict our ability to draw definitive conclusions at this stage. 


