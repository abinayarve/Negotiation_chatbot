💼 Python Price Negotiation System with Sentiment Analysis and AI Suggestions


📜 Project Overview


This project is a Python-based negotiation system that simulates a real-world price bargaining scenario. It integrates sentiment analysis using the TextBlob library and AI-generated suggestions to assist users during negotiations. The goal is to provide a dynamic negotiation experience where the user’s emotional responses influence the outcome.



🚀 Features


Dynamic Price Negotiation: Simulates a negotiation process where the user makes offers, and the supplier provides counter-offers based on a predefined discount.
Sentiment Analysis: Analyzes the user's sentiment (positive, neutral, or negative) using TextBlob, which influences future discounts.
AI Suggestions: When the user declines an offer, the system calls an AI API to provide negotiation strategies based on user input.
Incremental Discounts: Discounts increase based on the user’s sentiment, offering more attractive deals to encourage acceptance.


🛠️ How It Works


The system starts with an original price and a discount percentage.
The user is prompted to provide an offer in the format (e.g., I can offer $80).
The supplier makes a counter-offer based on the current discount.
The user can accept the offer or reject it and negotiate further.
The system uses sentiment analysis to adjust the discount:
Negative responses increase the discount by 3%.
Neutral or positive responses increase the discount by 2%.
AI suggestions are fetched to help the user negotiate better if they reject the offer.
The process repeats until a final deal is accepted.


🧰 Requirements


Python 3.x
Libraries:
requests
textblob
