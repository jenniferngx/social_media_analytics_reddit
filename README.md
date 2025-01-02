# Reddit Substance Use Analysis  

This project uses data scraping, sentiment analysis, and topic modeling to analyze discussions on Reddit about substance use, addiction, and related topics. 

---
## 📂 Project Structure  
- **Data Collection**:  
  - Scraping Reddit posts from targeted subreddits and queries using the `PRAW` API.  
  - Filtering relevant posts through subreddit and keyword searches.  
  - Storing data in JSON/CSV format to avoid duplicates.

- **Data Preprocessing**:  
  - Cleaning post content by removing empty entries and applying NLP techniques (lemmatization, stopword removal).  
  - Custom stopword lists filter out irrelevant filler words (e.g., "like", "know").  

- **Sentiment Analysis**:  
  - Polarity and subjectivity of posts are analyzed using `TextBlob`.  
  - Histograms visualize the distributions.   
  - **T-tests** determine if posts are significantly positive, negative, or neutral.  

- **Topic Modeling**:  
  - `Latent Dirichlet Allocation (LDA)` extracts key topics from posts.  
  - Topics are exported into categorized CSV files.  

- **Visualization & Interpretation**:  
  - Subreddit-level sentiment analysis and correlation tests are applied (Spearman correlation).  
  - Topic distributions are visualized using `pyLDAvis` for interactive exploration.  

---
##  📈 Topic Modeling Results
- **Topic 1: General Life & Family Dynamics**:  
  - Posts explore personal experiences, family, and social life
  - May highlight indirect links between substance use and personal struggles

- **Topic 2: Medical & Prescription Use**:  
  - Focuses on medications (opioids, painkillers) and prescriptions experiences
  - Provides insights into how medical treatments may evolve into addiction
    
- **Topic 3: Addiction & Overdose**:
  - Discusses severe substance use, highlighting heroin, fentanyl and overdoses
     
