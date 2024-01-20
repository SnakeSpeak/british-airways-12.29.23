# British Airways Web Scraping for Forager

## As part of the job simulation that can be found on Forager, British Airways tasks you with webscraping SkyTrax reviews about them.
## The "getting_started.ipynb" was provided by them, and is unaltered.
## The "real_scrape.ipynb" is what I created to finely scrape SkyTrax for all possible ratings and strings for each category of a review, allowing for quick, in depth analyses.
### I hope to improve the code by condensing it further, but this'll do for now.
## The "analysis.ipynb" is what I used to analyze the resulting "BA_reviews_v2.csv" file from the "real_scrape.ipynb"
### I perform sentiment analysis using VADERS and create Word Clouds
## Contained in "task_2" folder is "machine_learning.ipynb" and "customer_booking.csv"
### "customer_booking.csv" is data provided by British Airways that is used to train the model in "machine_learning.ipynb"
### "machine_learning.ipynb" contains starter code from British Airways that I modified and added to. 
#### I trained a logistic regression binary classification model using scikit-learn after preprocessing the data w/ LabelEncoder. It results in a model w/ 85% accuracy.
