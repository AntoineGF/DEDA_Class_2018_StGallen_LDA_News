# University Project - Smart Data Analytics

## Goal 

During a week, the goal has been the explore the possibilities offered in R with regards to sentiments analysis and topic modelling. To do so, we used a Latent Dirichlet Allocation model. 

## Data

The data is freely available at the following link: https://www.kaggle.com/astoeckl/newsen
Note that an account must be created. 

## Files 

There are three R files in the repo: 
  - LDA_singlewords.R:  this script produces descriptive information about the data set, a short sentiment analysis and an LDA model. All of these were produced using stop words and single words, considered to be a good benchmark model to be compared with more sophisticated techniques. 
  - LDA_improvements.R: this script is an exploration of the possible improvements over the aforementioned method. Namely, the use of frequencies instead of stop words (to filter out the most common and rare words), and bigrams have been explored. 
  - LDA_Sentiments.Rmd: this R markdown simply puts together the two previous scripts to offer a report and some comments about our findings. 
  
 ## Note
 
 Unfortunately, due to time constraints, we have not been able to fit LDA models to bigrams or to frequency-based fitlering method. This would be a great area for further analysis.

## Authors

Jonas Clemens (MBF), Marco Hassan (MBF), Antoine Gex-Fabry (MECON)
