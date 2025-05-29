# PRODIGY_DS_04
Performing sentiment analysis on a dataset of 1.6 million pre-labeled tweets to analyze public opinion about a specific brand. The sentiment is classified as either Positive or Negative.

File used: training.1600000.processed.noemoticon.csv

Steps Performed:
 1.Load the dataset using pandas and assign column names manually.
 2.Map numeric sentiment values to categorical labels: "Negative" and "Positive".
 3.Drop missing or duplicate entries and retain only text and sentiment columns.
 4.Clean tweet text by:
  Removing non-alphabet characters
  Converting text to lowercase
 5.Filter tweets mentioning a specific brand (e.g., "apple").
 6.If tweets are found:
  Count sentiment distribution (Positive vs. Negative)
  Visualize the sentiment using a bar chart via seaborn


Libraries Used:
pandas: Data loading and manipulation
matplotlib.pyplot: Plotting
seaborn: Enhanced data visualization
re (regular expressions): Text cleaning
