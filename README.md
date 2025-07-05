# Airline-Review-Scraper-Sentiment-Analysis
Project: British Airways Review Scraper + Sentiment Dashboard
Author: Manishankerreddy Sanampudi
Tools Used: Python · BeautifulSoup · Pandas · Matplotlib · Seaborn
📬 Scenario
A client requested a full report on passenger satisfaction for British Airways. They shared a web resource: https://www.airlinequality.com/airline-reviews/british-airways and asked for insights into what customers are saying—both good and bad.

I used Python with BeautifulSoup to scrape reviews across 10 pages (~1,000 reviews), processed the content, cleaned noise like "✅ Trip Verified", and stored the results in BA_reviews.csv.

I later applied sentiment classification and created visual reports highlighting sentiment distribution and the most mentioned topics in positive vs. negative reviews.

⚙️ Features
Collected 1,000+ authentic reviews

Cleaned and stored data in CSV format

Performed keyword extraction on sentiments

Built enhanced visual dashboards with Seaborn

📈 Insights
48% Neutral · 36% Positive · 16% Negative

Positives: Crew service, food, comfort

Negatives: Delays, customer support, baggage issues

🔍 Image Keywords for Thumbnail
Search using these phrases:

web scraping

text sentiment analysis

customer feedback data

airline passenger experience

python bs4 dashboard

🔮 Project 2: Flight Booking Prediction
🔖 Title: Customer Booking Predictor
📝 Short Description:
A machine learning project that predicts if a flight booking will be completed using features like purchase lead time, passenger preferences, and booking origin.

📄 Full README Description:
Project: Predictive Modeling of Booking Completion
Author: Manishankerreddy Sanampudi
Tools Used: Python · Pandas · Scikit-learn · Google Colab
📬 Scenario
A client in the travel sector shared a dataset named customer_booking.csv containing 50,000 flight inquiries. They wanted a predictive model to identify whether a customer will complete their booking or not.

I started with exploratory data analysis, feature transformation (e.g., mapping days to numbers), and proceeded to train a classification model based on user preferences, travel details, and intent indicators.

⚙️ Features
Data cleaning and preprocessing

Exploratory statistics and visualizations

Conversion of categorical variables

Feature engineering and model training

Classification target: booking_complete

📈 Insights
Most users book via Internet (~60%)

Many bookings are dropped after selection (~85%)

Preferred seat, in-flight meal, and baggage strongly influence conversions

