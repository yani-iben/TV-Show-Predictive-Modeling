# Emily in Paris Season 5: Descriptive and Predictive Analytics

## Project Overview
This project uses descriptive and predictive analytics to inform the development of *Emily in Paris* Season 5. 

### Business Understanding
We sought to address the following key questions:
- What are the dominant themes and sentiments expressed by the audience?
- How have viewer opinions changed over time?
- What factors influence positive or negative sentiment?

### Data Collection and Analysis
We collected data from *Emily in Paris* show transcripts to perform sentiment analysis and topic modeling.  
- **Sentiment Analysis**: Initial sentiment analysis revealed limited actionable insights, prompting us to conduct emotional analysis.
- **Topic Modeling**: Topic Modeling helped us understand the relationship between different emotions and how to best balance these emotions to generate viewer satisfaction.

### Predictive Models
We applied several predictive models, including time series regression, to predict audience satisfaction as measured by IMDb ratings. Our most successful model was **Random Forest**, which provided strong predictive accuracy.

The image below showcases which features were the most important when impacting IMDB Ratings

![Random_Forest](Random_Forest.png)

### Key Findings
1. **Emotions Driving Viewer Satisfaction**:
   - **Joy**, **trust**, and **surprise** were the primary emotions shaping viewer satisfaction.
   - **Fear** and **suspense** were positively correlated with higher ratings, reflecting audience engagement.  
   - **Disgust** often indicated conflict and contributed to narrative tension.

![Emotions_Across_Episodes](Emotions_Across_Episodes.png)

2. **Themes and Sentiments**:
   - Topic modeling revealed recurring themes and helped identify key areas for narrative enhancement.  
   - Emotional analysis provided a nuanced understanding of audience responses, highlighting the complex interplay of emotions with ratings.
  
![IMDB_Ratings_Sentiment](IMDB_Ratings_Sentiment.png)

### Business Recommendation

1. Focus on Positive Emotions
- Lighthearted Moments emphasize humor and joy, as these consistently resonate with viewers.
Audience preferred episodes with lighter themes and humor.

2. Balance Emotional Dynamics
- Develop Positive Emotions
     Include plots that generate certain emotions like joy, trust, and surprise as they strongly correlate with higher IMDB ratings.

- Conflict and Resolution
   Maintain conflict-driven narratives (e.g., fear, disgust, and anger) to drive higher viewership
Balance by resolving conflicts in a satisfying way. Unresolved negativity may harm viewer satisfaction.
eg) repetitive break-ups

3. Enhance Story Structure Through Characters
- Fan-Favorite Characters
   Highlight characters from most liked seasons/episodes that contributed to the success of the highest-rated episodes.

- Character Growth
   Enhance audience engagement by emotionally connecting beloved characters from certain seasons or episodes and including their development into the storyline.


### Conclusion
By leveraging descriptive and predictive analytics, we uncovered insights into the emotional and thematic elements that resonate most with viewers. These findings can guide storytelling decisions for *Emily in Paris* Season 5, enhancing audience satisfaction and ratings.

---

## Technologies Used
- **Data Collection**: Show transcripts
- **Descriptive Analytics**: Word Cloud, sentiment analysis, topic modeling
- **Predictive Analytics**: Random Forest, Time series regression
- **Metrics**: IMDb ratings as the success criterion

## Future Work
- Explore additional datasets, such as social media comments or reviews.
- Refine predictive models to incorporate more contextual features.
- Develop actionable recommendations for future seasons based on insights.

---

## Contact
For more details, feel free to reach out or explore the code repository.
