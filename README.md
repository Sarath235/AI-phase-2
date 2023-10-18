from textblob import TextBlob

# Sample text
text = "I love this product! It's amazing."

# Analyze sentiment
analysis = TextBlob(text)
sentiment = analysis.sentiment.polarity  # sentiment ranges from -1 to 1

if sentiment > 0:
    print("Positive sentiment")
elif sentiment < 0:
    print("Negative sentiment")
else:
    print("Neutral sentiment")
    




