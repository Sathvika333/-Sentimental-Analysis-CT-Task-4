*COMPANY* : CODTECH IT SOLUTIONS  
*NAME* : R Sathvika teja 
*INTERN ID* : CT12WVZF 
*DOMAIN* : Data Analytics  
*DURATION* : 12 weeks  
*MENTOR* : Neela Santhosh Kumar 

# -Sentimental-Analysis-CT-Task-4

Task Description:
The objective of this task was to perform a sentiment analysis on a dataset comprising blog texts written by different individuals. The aim was to classify the emotional tone conveyed in the text into one of three categories: positive, negative, or neutral, and to analyze these sentiments with respect to various demographic features such as age group, gender, and zodiac sign.

The analysis was implemented using Python with the support of several data analysis and visualization libraries including pandas, matplotlib, and seaborn. The core of the sentiment classification was built using the TextBlob library, which offers a simple API for common natural language processing tasks such as sentiment analysis.

The dataset used in this task, named blogtext.csv, contained blog entries along with corresponding metadata such as author age, gender, and zodiac sign. Initially, the blog text data was cleaned and passed through a custom function that used TextBlob to calculate the polarity score of each text. Based on the polarity score, sentiments were classified: a positive score indicated a "positive" sentiment, a negative score implied "negative" sentiment, and a score of zero was categorized as "neutral".

After sentiment labeling, the data was exported into a CSV file for potential downstream analysis and reporting. To gain meaningful insights, exploratory data analysis (EDA) was conducted on the sentiment distributions. Visualizations were generated to represent the number of blog posts falling into each sentiment category using bar charts. The sentiment trends were further segmented by age groups, which were created using binning logic and labeled by decades (e.g., 10s, 20s, 30s, etc.).

Additional stratified visualizations were performed to understand sentiment variation across zodiac signs, and a grouped bar chart was created to illustrate how individuals with different astrological signs expressed emotions in their writings. Similarly, gender-based analysis was conducted in conjunction with age groups to understand sentiment patterns across demographic combinations. The percentage of sentiments across gender and age groups was calculated and plotted using a catplot from the Seaborn library, which allowed a comparative analysis across multiple dimensions.


Some of the outputs:



