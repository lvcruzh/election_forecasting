This repository includes the essential files from the project 'Unveiling the Power of Live Chat Comments in Election Periods: A Comparative Study Using GPT Models'.

**About the project:**

This research project explores the potential of utilizing social media data to pre- dict election outcomes, with a focus on the context of the 2018 Mexican general elec- tion. Through an analysis of YouTube live chat comments during presidential debates streams and employing large language models, the study pursues two primary objec- tives. Firstly, it aims to evaluate the accuracy of electoral outcome predictions using social media data and GPT models within the Mexican context. Secondly, the project aims to establish a comparative analysis between the forecasts derived from YouTube live chat comments and the predictions generated through conventional public opin- ion polls that were published during the campaign period. The findings of this study unveil intriguing outcomes: while social media comments demonstrate proficiency in identifying leading candidates, they encounter challenges when it comes to accurately predicting the precise ranking of candidate preferences and approximating vote per- centages. This outcome underscores the complexities inherent in achieving representa- tive samples from social media data, highlighting the significance of diversifying data sources in election forecasting with social media data.


**Files in this repository:**

- Youtube Comments Retrieval: Utilize 'youtube_comments.ipynb' to effortlessly collect comments from YouTube videos. Tailor this file to your specific video of interest.

- Sentiment Analysis with GPT Models: Leverage 'gpt.ipynb,' specifically targeting the 'text-davinci-003' model from the OpenAI API. Uncover sentiment insights from the video comments.

**Prerequisites:**

Ensure you have the following packages loaded in python:

- pytchat
- pandas
- openai
- time

**Usage:**

1. Start with 'youtube_comments.ipynb' to retrieve YouTube comments, customizing it for your preferred video.
2.  Perform any necessary preprocessing on the Youtube comments. 
3. Utilize 'gpt.ipynb' with the 'text-davinci-003' model to perform sentiment analysis.

**Notes:**

- An OpenAI key is indispensable for API usage.
- Craft a well-designed prompt for optimal results. 
