# Tweet-Summariser
Crowd sourced Summariser for highlights of a sports match using tweets corresponding to the match as the only source. This is run on the India Vs England Match of 23rd march 2021.


# Working:
<img width="405" alt="Screenshot 2021-11-01 at 6 51 56 PM" src="https://user-images.githubusercontent.com/93538009/139701016-cd6bdba3-b928-4422-a67b-0f77eac6c6b8.png">

# How to access Repository
## Data acquisition:
MODULE1_cursor.ipynb, MODULE1_jsontocsv_NEW_BCCI.ipynb and MODULE1_streamapi.ipynb the codes used in this phase to extract tweets related to the match. INDvsENGds.csv is the original data collected from twitter before pre processing and BCCI.csv is the file containing tweets from BCCI(Credited source) alone.
## Preprocessing:
MODULE2_preprocessing.ipynb contains code for preprocessing and INDvsENGds_updated3.csv is the preprocessed dataset
## Named Entity Recognition:
Module3_NER_final.ipynb contains code for named entity recognition and the gazette files used are Players.txt, Teams.txt and Venue.txt
## Event Detection and Summarisation
Three methods are used for event detection and summarisation- TFIDF, Frequency based scoring and finally Textrank algorithm. The output summaries of each of these methods are evaluated using rogue scores and the best summary is improved by incorporating tweets from credible source- BCCI. 
The codes for these modules are MODULE4&5_NEW_tfidf_withtimestamps.ipynb, MODULE4&5_NEW_tweetscoring_withtimestamps.ipynb, MODULE4&5_textranksummariser.ipynb, MODULE4_NEW_burstdetection_withtimestamps.ipynb and MODULE5_RougeScores.ipynb.

Detailed documentation of this project can be found here: https://www.irjmets.com/uploadedfiles/paper/volume_3/issue_9_september_2021/16192/final/fin_irjmets1631785095.pdf 
