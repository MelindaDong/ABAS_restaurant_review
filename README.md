# aspect_based_sentiment_analysis

The aim of this project is to build an aspect-based sentiment analysis (ABSA) system based on syntactic parsing. 
The aspect-based sentiment analysis tries to analyse the sentiment, positive, negative, and neutral. 
Because if one aspect term is not positive, it will not necessary be negative or neutral, that’s why we do these 3 parts separately.

There are 2 common syntactic parsing method: dependency parsing and constituency parsing. 
Dependency parsing tends to capture more fine-grained relationships between words. 
Constituency parsing, on the other hand, provides a higher-level view of the sentence structure, focusing on larger constituent phrases. Therefore, the project chooses dependency parsing, because it’s more suitable for analysing specific aspects or entities within a sentence.

The project built 3 rules for positive sentiment detection.  4 rules for negative and 4 rules for neutral sentiment detection.  
Since all the rules are manually build and there are various sentence expressions, it’s difficult to cover all those expressions, the result didn’t work as better as other machine learning method, the final F1 sore for positive sentiment detection is 0.716, for negative sentiment detection is 0.446 and 0.431 for neutral.

__detailed information see `ABSA.pdf`__

