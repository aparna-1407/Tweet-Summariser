# Tweet-Summariser
 Developed a crowd-sourced summarizer for sports events that extracts Tweets, preprocesses them and identifies highlights of the match and ranks corresponding tweets in order of how informative they are, and produces a chronological and cogent summary. This is run on the India Vs England Match of 23rd march 2021. 


# Working:
<img width="405" alt="Screenshot 2021-11-01 at 6 51 56 PM" src="https://user-images.githubusercontent.com/93538009/139701016-cd6bdba3-b928-4422-a67b-0f77eac6c6b8.png">

# How to access Repository
## Data acquisition:
Data extraction folder contains the code files used in this phase to extract tweets related to the match. INDvsENGds.csv is the original data collected from twitter before pre processing. 
## Preprocessing:
Data Preprocessing folder contains code for preprocessing and INDvsENGds_updated3.csv is the preprocessed dataset. BCCI.csv is the file containing tweets from BCCI(Credited source) alone.
## Named Entity Recognition:
Statistics Generation contains code for named entity recognition and the gazette files used are Players.txt, Teams.txt and Venue.txt
## Event Detection and Summarisation
Three methods are used for event detection and summarisation- TFIDF, Frequency based scoring and finally Textrank algorithm. The output summaries of each of these methods are evaluated using rogue scores and the best summary is improved by incorporating tweets from credible source- BCCI. 
The codes for these modules are in Burst Detection & Summarisation and Testing.

Peer Reviewed publication related to this project can be found here: https://www.irjmets.com/uploadedfiles/paper/volume_3/issue_9_september_2021/16192/final/fin_irjmets1631785095.pdf 
