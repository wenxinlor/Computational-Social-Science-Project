# Computational-Social-Science-Project (Year 2 Sem 1) (2022)
## Project Summary: Sentiment Analysis on the Legalization of Marijuana in the US

This project aims to analyze public sentiments towards the legalization of recreational marijuana in the United States using text data from Reddit and Twitter. We conducted sentiment analysis using two different tools: VADER and Empath. The dataset was cleaned and preprocessed, including tokenization and keyword filtering to focus on US-related posts. Our analysis focused on understanding overall sentiment trends and whether social factors affected these sentiments.

### Key components of the project include:

1. **Data Collection**:
   - Scraped Reddit and Twitter posts related to marijuana legalization using relevant keywords (e.g., “usa”, “america”, “legalize marijuana”).
   - Used the “r/politics” subreddit to increase the likelihood of gathering US-centric posts.

2. **Data Preprocessing**:
   - Cleaned the text data by removing stopwords, punctuation, and applying tokenization.
   - Filtered and processed tweets and Reddit posts for further analysis.

3. **Sentiment Analysis**:
   - **VADER Analysis**: Utilized the VADER sentiment scoring to classify texts into positive, negative, and neutral categories. However, limitations such as inability to detect sarcasm and contextual understanding resulted in some misclassifications.
   - **Empath Analysis**: Implemented the Empath tool to categorize text into 200+ semantic categories. Encountered challenges with word disambiguation (e.g., “bill” referring to both money and legislation).

4. **Results and Insights**:
   - The sentiment analysis suggests that Americans generally have a positive attitude towards the legalization of recreational marijuana.
   - Social factors (e.g., demographic information) did not significantly alter the overall sentiment trends.

5. **Challenges**:
   - Lack of location metadata in Reddit posts, making it hard to confirm the geographical relevance of the data.
   - Limitations of VADER and Empath in contextual sentiment analysis, resulting in potential inaccuracies.

6. **Conclusion**:
   - Despite the limitations, our findings align with past research indicating that the US public is generally supportive of legalizing recreational marijuana.
