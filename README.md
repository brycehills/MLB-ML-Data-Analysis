# cs105-prj-phase3-data-boys
cs105-prj-phase3-data-boys created by GitHub Classroom

## The Dataset and Problem:
After starting our project and reading in our data set, we were not sure on exactly what we wanted to try to predict using ML. Once we read in the data and thought about it, we decided to go with predicting a team's season-long number of homeruns, since this is probably one of the most exciting stats surrounding the sport of baseball. After reading in our data, along with homeruns, we had 28 other features and over 3000 rows spanning years 1980 - 2019.
Our problem was to find the best features to test our training data with. After running some scatter plots to find the best data, we were able to filter out some features to reduce the size down to 25 features. 
## Phase 1 and 2 Contributions
In Phase 1, we began by obtaining the datasets from the MLB website of all the years available. We used BeautifulSoup to scrape the data and combined it into a single dataframe.
We then took it to Phase 2, with cleaning up the data; dropping columns we did not need. We also added in the visualizations needed for the project,
including scatterplots, box plots, and a parallel coordinates plot. 
Our histogram provides us with an evenly distributed bell-curve for the data on homeruns, with only a few outliers. 
And team data shows many more outliers in catagories like doubles, triples, and RBI's. 
It was interesting to find that there was almost no correlation between the team avg age and the number of homeruns hit.
## Summary of Phase 3:
In phase 3, the machine learning models were contructed and ran with training and test data. The test data used to predict a single teams season number of homeruns was one row. For the team selected, the actual statisic showed that that team hit 127 homeruns, while our models predicted 133 and 144, which are pretty close. In summary, the linear regression was our most accurate predictor, and the result was very close to the actual season outcome. 

