# A novel machine learning approach for detecting events from social media platform - Twitter
During my undergraduate last year capstone design project/thesis work, I (with my group) have implemented this system that can detect events from social media dataset. This is a novel machine learning approach for detecting events from social media.  

First, data is scraped from twitter using 'tweepy' library ranges from January 2020 to January 2021. News data from official twitter pages - BBC, CNN, Al-Jazeera, Reuters have been chosen as primary corpus. Then, data is annotated and labeled as 'yes' and 'no', where 'yes' indicates a valid event and 'no' indicates a non-event.  
After annotating, pre-trained BERT classification model is trained further and evaluated with that labeled dataset. Then a binary classification model under simple transformers package is used to classify and detect events. 
