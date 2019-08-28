# Twitter-Analysis
Text Similarity Analysis of Tweets related to the University of Chicago

# Objective 

1. To identify the profiles of Twitterers, who are tweeting about University of Chicago and compare them to the profiles of Twitterers who are tweeting about other universities.

2. Providing actionable business recommendations to help University improve the social media outreach programs.

# Steps

    0. Scraped twitter data that comes in deeply nested JSON format. Removed noisy tweets. 
    1. Identified tweets related to UChicago and 3-4 other universitiesand discard irrelevant tweets

    2. EDA to identify which variables you can use to profile the Twitterer. A lot of variables were poorly populated and hence discarded
    3. Identified the most prolific / influential Twitterers by message volume, by message retweet
    4. Discovered how much are they tweeting about the Universities vs. other topics and from where are these Twitterers located?
    5. Identified relationship between university locations and Twitterers’ locations and visualized the relationships
    6. Provided insights on what distinguishes University of Chicago Twitterers vs Twitterers who tweet about other universities. Visualized the trends
    7. Analysis on the timelines of these tweets, significant peaks and valleys
    8. Observed data collection gaps
    9. Identified the uniqueness of the messages for each of these universities. Used techniques like 
                    Jaccard similarity
                    Cosine Similarity
                    Simhash
                    Minhash 
        to measure uniqueness / similarity.
    10. Visualized message duplication for each university

