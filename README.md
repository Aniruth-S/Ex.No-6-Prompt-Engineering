## Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

## Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

**Explanation:**

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.

## Program
Code Used for Positive Output:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "This smartphone offers outstanding battery life and an intelligent AI camera that captures stunning photos."

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
Code Used for Negative Output:
```
from nltk. sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "This smartphone battery is very bad and it couldn't hold for 2 hours."

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive👍 and suitable for marketing promotion📈.")
else:
    print("\nInsight: The review tone is neutral or negative🫠.")
```
## OUTPUT:

**Positive**

<img width="1078" height="198" alt="Screenshot 2026-03-18 102600" src="https://github.com/user-attachments/assets/ee5e9f98-2d3d-4b64-8f71-33483e100e79" />

**Negative**

<img width="773" height="194" alt="Screenshot 2026-03-18 103257" src="https://github.com/user-attachments/assets/757ff658-e02c-4fa0-8d74-d09995739fb6" />

## Result: 
Thus, the Python code that integrates with multiple AI tools to automate the task of interacting with APIs was run successfully and the output was compared.
