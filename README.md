# Major_Project
Final Year Project
PCSE23-57


The title of our Project is "SENTIMENT ANALYSIS BY AUDIO SPEECH USING TEXTBLOB", the team members are:
ANAND GUPTA
CHETAN SHUKLA
PALLAVI VERMA
VIBHANSHU VERMA


I. Introduction

Sentiment analysis is the process of determining the sentiment or emotional tone of a piece of text. It is widely used in various applications, including customer feedback analysis, social media monitoring, and market research. Traditionally, sentiment analysis has been performed on written text. However, with the advancements in speech recognition technology, it is now possible to perform sentiment analysis on audio speech as well. In this tutorial, we will explore how to perform sentiment analysis on audio speech using TextBlob, a popular Python library for natural language processing.

II. Speech-to-Text Conversion

Before we can perform sentiment analysis on audio speech, we need to convert the speech into text. This process is known as speech-to-text conversion or speech recognition. There are several speech recognition libraries available in Python, such as SpeechRecognition and Google Cloud Speech-to-Text. These libraries utilize machine learning algorithms to transcribe spoken words into written text.

III. TextBlob for Sentiment Analysis

TextBlob is a powerful Python library that provides a simple and intuitive API for natural language processing tasks, including sentiment analysis. It offers pre-trained models and methods to analyze text and extract sentiment polarity and subjectivity. Sentiment polarity indicates whether the sentiment expressed in the text is positive, negative, or neutral, while subjectivity measures the extent to which the text is subjective or objective.

IV. Integration of Speech Recognition and TextBlob

To perform sentiment analysis on audio speech, we can integrate the speech recognition library with TextBlob. The basic steps involved in this integration are as follows:

1. Convert the audio speech into text using a speech recognition library like SpeechRecognition or Google Cloud Speech-to-Text.
2. Pass the transcribed text to TextBlob for sentiment analysis.
3. Use TextBlob's sentiment analysis methods to calculate the sentiment polarity and subjectivity of the transcribed text.
4. Interpret the sentiment analysis results to gain insights into the emotional tone of the audio speech.

V. Conclusion

Performing sentiment analysis on audio speech can provide valuable insights in various applications, including customer feedback analysis, call center monitoring, and voice assistants. By combining speech recognition and TextBlob's sentiment analysis capabilities, we can extract meaningful sentiment information from audio speech data. With further advancements in speech recognition and natural language processing technologies, sentiment analysis by audio speech is expected to become even more accurate and efficient in the future.
