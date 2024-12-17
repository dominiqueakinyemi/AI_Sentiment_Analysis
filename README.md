#  Sentiment Analysis: AI in Filmmaking and Creative Media  

**Click here to download the full project documentation as a PDF file: [ai_sentiment_analysis.pdf](https://github.com/user-attachments/files/18160110/ai_sentiment_analysis.pdf)**

## Overview  
The rise of **Artificial Intelligence (AI)** in creative fields such as **filmmaking, screenwriting, and visual media creation** has generated significant public conversation. This project investigates public sentiment and emotional responses toward AI's influence in these creative spaces, analyzing comments and discussions from **YouTube**, **Reddit**, and **Twitter/X**.

The goal is to uncover **what people feel** about AI: excitement for innovation, skepticism, ethical concerns, or fear of creative loss.  

---

## Objectives  
- **Analyze Sentiment**: Detect and categorize sentiment as positive, neutral, or negative.  
- **Understand Emotions**: Identify deeper emotional responses, such as trust, fear, anticipation, or joy.  
- **Visualize Patterns & Trends**: Plot sentiment and emotion trends over time across platforms.  
- **Highlight Platform Differences**: Compare how AI discussions vary across Reddit, YouTube, and Twitter.  

---

## Tools and Libraries  
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, WordCloud  
- **NLP Tools**: TextBlob, Hugging Face Transformers, NRCLex  
- **Data Collection**: Reddit API, YouTube API, Twitter API  
- **Visualization**: Matplotlib, Seaborn, WordCloud

---

## Methodology  

### 1. **Data Collection**  
Data was collected using platform-specific APIs and scraping tools:  
- **Reddit**: Subreddits discussing AI and creativity (e.g., *r/Filmmakers*, *r/Screenwriting*).  
- **YouTube**: Comments from videos addressing AI tools for filmmaking and media production.  
- **Twitter/X**: Tweets containing keywords *AI movies*.  

### 2. **Data Cleaning & Preprocessing**  
- Removed URLs, special characters, and irrelevant text.  
- Standardized text (lowercase, whitespace removal).  
- Parsed time data for temporal analysis.  
- Handled missing values and duplicates.  

### 3. **Sentiment Analysis**  
Two approaches were used for a comprehensive view:  
- **TextBlob**: A rule-based tool for broad sentiment classification (polarity and subjectivity).  
- **Hugging Face Transformers**: A deep learning model for nuanced sentiment detection.  

### 4. **Emotion Analysis**  
Using **NRCLex**, emotions like joy, trust, fear, and anger were identified to explore deeper perceptions.  

### 5. **Visualizations**  
Key visualizations include:  
- **Scatterplots**: Sentiment trends over time.  
- **Emotion Bar Charts**: Breakdown of emotions across platforms.  
- **Word Clouds**: Common words and themes in public discussions.  

---

## Results  

### **Sentiment Analysis**  
- **YouTube**: Exhibited the **highest positive sentiment** driven by *trust* and *joy*. Viewers expressed excitement for AI tools and their applications.  
- **Reddit**: Discussions revealed **higher skepticism** and **fear**, focused on ethical concerns and the threat to human creativity.  
- **Twitter/X**: Sentiment was largely **neutral**, reflecting broader, surface-level opinions.  

### **Emotion Analysis**  
- **Positive Emotions**: *Trust*, *anticipation*, and *joy* dominated across all platforms, indicating optimism for AI's potential.  
- **Negative Emotions**: *Fear* and *anger* appeared prominently on **Reddit**, highlighting polarized discussions and concerns about AI's societal impact.  

### **Key Insights**  
- YouTube audiences engage positively, reflecting enthusiasm for AI's practical uses.  
- Reddit serves as a platform for critical discussions, where fear and ethical concerns dominate.  
- Twitter provides a snapshot of generalized discourse, with lower emotional intensity.  

---

## Key Visualizations 

- **Emotion Distribution:** Allows you to see dominant emotions and compare by platform.
![output_75_0](https://github.com/user-attachments/assets/eff66ed3-8174-4b86-89d8-61f0c3c63781)

- **Sentiment Polarity Over Time (TextBlob):** Shows sentiment polarity for each platform.
![output_64_1](https://github.com/user-attachments/assets/e4a0ab48-189c-47e7-9bcb-69fa6c0db639)

- **Sentiment Proportions (Hugging Face Transformers Labeling):** Shows sentiment polarity for each platform.
![output_65_0](https://github.com/user-attachments/assets/da34617e-f621-4f45-a019-ac7efbae8a20)

To view more visualizations, access the "visuals" folder in the repository files.

---

## Challenges  
- **Data Imbalance**: Twitter data was limited to 100 tweets due to API restrictions.  
- **Model Variance**: TextBlob and Transformers provided differing results, requiring deeper emotion analysis to resolve conflicts.  
- **Platform Differences**: Tailoring preprocessing and analysis techniques to each platform's data format.  

---

## Future Work  
- **Expand Dataset**: Include more platforms (e.g., Instagram or Threads) for a broader analysis.  
- **Topic Modeling**: Use tools like LDA to identify recurring themes in AI discussions.  
- **Temporal Analysis**: Analyze long-term trends to track changing public perceptions.  
- **Geographic Insights**: Explore regional variations in AI sentiment and emotions.  
