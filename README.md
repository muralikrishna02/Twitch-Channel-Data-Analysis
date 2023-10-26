## Twitch Channel Data Analysis

### Project Overview

This project focuses on analyzing data from Twitch channels using the livestreaming platform. The dataset contains information about various channels, including their watch time, stream time, peak viewers, average viewers, followers, and more. The goal of this analysis is to gain insights into the performance and characteristics of these channels.

## Dataset

The dataset includes the following columns:

- **Channel:** The title of the Twitch channel.
- **Watch Time:** The total amount of minutes spent watching the channel's videos.
- **Stream Time:** The total amount of time spent broadcasting the content by the channel.
- **Peak Viewers:** The number of people who watched the stream.
- **Average Viewers:** The average number of people who watch a certain station.
- **Followers:** The total number of people who follow a specific channel.
- **Gained Followers:** The number of subscribers obtained by a channel throughout time.
- **Views Gained:** The increase in the number of views of content on a specific channel throughout time.
- **Partnered:** Indicates whether the channel partnered with another channel in a video.
- **Mature:** Indicates if the channel's material is intended for adults or children.
- **Language:** Specifies the primary language of the channel.


### Project Highlights

- **Exploratory Data Analysis (EDA)**: Several visualizations were created to better understand the data, including:
  - A pie chart showing the percentage of channels intended for adults or children.
  - A bar chart displaying the number of channels based on their specific language, with English being the dominant language.
  - A bar plot illustrating the top 20 channels based on stream time in minutes.
  - Line plots exploring relationships between stream time, views gained, and watch time.
  - A scatter plot showcasing the relationship between views gained and followers gained.
  - A bar plot highlighting the top 10 channels based on followers count.

### Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook


### Findings
- The analysis revealed that English channels are the most popular, with a significant majority of channels being in the English language.

- Correlations were observed, particularly between watch time and followers, suggesting that channels with more watch time tend to have more followers.

- An outlier channel with exceptionally high views gained was detected and subsequently removed to prevent skewing the analysis.

## Conclusion

In summary, the Twitch data analysis project involved cleaning the dataset, performing exploratory data analysis, creating various visualizations, and identifying key findings. English channels are dominant, and significant correlations exist in the dataset, particularly between watch time and followers. An outlier channel was removed to ensure the accuracy of the analysis. 


For a detailed view of the analysis and code, please refer to the Notebook
