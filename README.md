# opinion-classifier
## Structure matters: Feature selection for transformer-based news and opinion classification
For my final project for CS224N, Natural Language Understanding (part of the Stanford Professional Certificate in Artificial Intelligence), I investigated something I had been curious about for a long time - how using different parts of news articles in training affects performance for news vs opinion classification. The project was selected as an [example for future cohorts](https://drive.google.com/drive/folders/1E9fKOxRen5y61XgoYtpYN80tnJxJ0pi4?usp=drive_link).

### Abstract
The ability to detect whether a news article is a straight news story or an opinion piece is a valuable task for media research. News articles are structured pieces of writing, but past approaches to news vs. opinion classification have largely ignored that structure. I hypothesize that features that incorporate the parts of articles most likely to aid in news vs. opinion differentiation will improve classifier performance. 

To explore this question, I use labeled data drawn from a large, proprietary dataset of English-language news articles. I engineer contextual representation features that draw on different parts of a news article (start, end and metadata) and use them to fine tune a BERT model. I find that features that incorporate article metadata and the end of the article result in better performance than features that rely only on the start of the article.  

