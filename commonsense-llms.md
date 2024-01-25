---
layout: page
title: Commonsense in Large Language Models
description: Commsense NLP
---

# Commonsense in GPT-2

Large language models depend on text data, and thus may lack the ability to provide information that is transferred in ways which do not involve text (ie. word of mouth), otherwise known as commonsense. 
To test this potential drawback of LLMs, I turned to a Family Feud Q&A style database where the information required to answer questions correctly closely resembles commonsense knowledge. I fine tuned GPT-2 to predict answers to Family Feud questions and tested varying grammar formats to determine optimal model performance. I then evaluated performance with Exact Match and Wordnet Similarity. 
The highest accuracy average came from using colons at the end of the questions, 72%, which shows that there is much room for improvement, but the model shows promise that with more work it will attain a decent ability to provide commonsense knowledge. The pursuit of attaining commonsense is important for these models, as the performance of AI would ideally extend beyond current human knowledge such that it helps provide a perspective when we approach new and unknown situations.
